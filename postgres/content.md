
%%LOGO%%

# Using the image
This image is based on a forked version of [official](https://registry.hub.docker.com/_/postgres/) image with few modifications.

* Use of [data container](http://docs.docker.com/userguide/dockervolumes/) to manage the postgresql data(PGDATA) folder.
* Extend the image using custom configuration files.
* Allow to create additional admin superuser during container creation.


## Staring an container

    docker run --name pgdata -v /var/lib/postgresql/data busybox echo data only container for postgresql

    docker run --name some-postgres --volumes-from pgdata \ 
    -p 5432:5432 -e ADMIN_USER=admin -e ADMIN_PASS=admin \
    ADMIN_DB=admin -d postgres

This above commands will 
* Initialize the default setup in the given data container folder
  `/var/lib/postgresql/data`
* Create the default postgresql user with password `postgresql`
* Create another superuser along with its default database that could be used
  for further database administration
* Exposes port `5432`
* Includes a `pg_hba.conf` file that make postgresql` user accessible only
  through unix socket. The additional superuser can access it from anywhere
  with password.


## Using the container

### From the host of the container
    
    psql -U $ADMIN_USER $ADMIN_DB

## Link it to another application container

    docker run --name some-app --rm  --link some-postgres:postgres -d application-that-uses-postgres

Now the application container can access the postgres database using the
environment variables and container name(through /etc/hosts). For details
about linking of docker containers look
[here](http://docs.docker.com/userguide/dockerlinks/) 

## Environment Variables

The PostgreSQL image uses several optional environment variables which are
handy for communicating with the database.

### `POSTGRES_PASSWORD`

This environment variable sets the **postgres** superuser  password for
PostgreSQL.  The default password will be **postgres**. Remember the `postgres`
user will only be accessible locally through unix socket. It means you can
login only from inside a running container.


    docker run --name pgdata -v /var/lib/postgresql/data busybox echo data only container for postgresql

    docker run --name some-postgres --volumes-from pgdata \ 
    -p 5432:5432 -e POSTGRES_PASSWORD=zombie postgres

### `ADMIN_USER`, `ADMIN_PASS`, `ADMIN_DB`

Use these variables to setup an additional superuser. This superuser will be
accessible from anywhere and therefore could be used for administrative purpose.
If `ADMIN_DB` is unset, the value of `ADMIN_USER` is by default.


    docker run --name pgdata -v /var/lib/postgresql/data busybox echo data only container for postgresql

    docker run --name some-postgres --volumes-from pgdata \ 
    -p 5432:5432 -e ADMIN_USER=admin -e ADMIN_PASS=admin \
    ADMIN_DB=admin -d postgres

    docker run --name some-postgres --volumes-from pgdata \ 
    -p 5432:5432 -e ADMIN_USER=admin -e ADMIN_PASS=admin \
    -d postgres


# Extending this image

## Initialization

If you would like to do additional initialization in an image derived from this
one, add a `*.sh` script under `/docker-entrypoint-initdb.d` (creating the
directory if necessary). After the entrypoint calls `initdb` to create the
default `postgres` user and database, it will source any `*.sh` script found in
that directory to do further initialization before starting the service. If you
need to execute SQL commands as part of your initialization, the use of
Postgres'' [single user
mode](http://www.postgresql.org/docs/9.3/static/app-postgres.html#AEN90580) is
highly recommended.

    # Example Dockerfile
    FROM dictybase/postgres:latest
    MAINTAINER Siddhartha Basu
    RUN mkdir -p /docker-entrypoint-initdb
    COPY custom_init.sh /docker-entrypoint-initdb/

## Configuration

To change the behavior or running server, custom config file(s) could be added
to any of the derivative image. The config file(s) will be sourced by the
default `postgresql.conf` file and will override any default settings. 

### For versions `9.3` and `9.4`

Add any number of `*.conf` file under `/conf` folder. All the `*.conf` files
will be moved to `conf.d` folder under `$PGDATA` which in turned will be
sourced by the `include_dir` directive in `postgresql.conf` file. For an
ordered loading of config files, prepend numbers in their names, like
`00first.conf`, `02second.conf` etc.

    # Example Dockerfile
    FROM dictybase/postgres:latest
    MAINTAINER Siddhartha Basu
    RUN mkdir -p /conf
    COPY *.conf /conf/

### For versions below `9.3`

These versions do not `include_dir` directive, so only a hardcoded list of
config files are supported. The following named config files are supported.  

    shared.conf
    server.conf
    memory.conf
    query.conf
    log.conf
    statistics.conf
    vaccuam.conf
    custom.conf

Place any one or more of the config files(s) under the `/conf` folder in any of
the derivative image. The config files are loaded in the order given above.

    # Example Dockerfile
    FROM dictybase/postgres:9.2
    MAINTAINER Siddhartha Basu
    RUN mkdir -p /conf
    COPY memory.conf /conf/
    COPY log.conf /conf/
 

# Caveats

If there is no database when `postgres` starts in a container, then `postgres` will
create the default database for you. While this is the expected behavior of
`postgres`, this means that it will not accept incoming connections during that
time. This may cause issues when using automation tools, such as `fig`, that
start several containers simultaneously.
