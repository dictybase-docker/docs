# Supported tags and respective `Dockerfile` links

-	[`9.0.22`, `9.0` (*9.0/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.0/Dockerfile)
-	[`9.1.18`, `9.1` (*9.1/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.1/Dockerfile)
-	[`9.2.13`, `9.2` (*9.2/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.2/Dockerfile)
-	[`9.3.9`, `9.3` (*9.3/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.3/Dockerfile)
-	[`9.4.4`, `9.4`, `9`, `latest` (*9.4/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.4/Dockerfile)
-	[`9.5-alpha2`, `9.5` (*9.5/Dockerfile*)](https://github.com/docker-library/postgres/blob/cd294bf8dfdf4a74b2077aa6413fa579f9bf07de/9.5/Dockerfile)

For more information about this image and its history, please see [the relevant manifest file (`library/postgres`)](https://github.com/docker-library/official-images/blob/master/library/postgres). This image is updated via pull requests to [the `docker-library/official-images` GitHub repo](https://github.com/docker-library/official-images).

For detailed information about the virtual/transfer sizes and individual layers of each of the above supported tags, please see [the `postgres/tag-details.md` file](https://github.com/docker-library/docs/blob/master/postgres/tag-details.md) in [the `docker-library/docs` GitHub repo](https://github.com/docker-library/docs).


![logo](https://raw.githubusercontent.com/docker-library/docs/master/postgres/logo.png)

# Using the image
This image is based on a forked version of [official](https://registry.hub.docker.com/_/postgres/) image with few modifications.

* Use of [data container](http://docs.docker.com/userguide/dockervolumes/) to manage the postgresql data(PGDATA) folder.
* Extend the image using custom configuration files.
* Allow to create additional admin superuser during container creation.


## Staring a container

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

## Kubernetes secrets
The container support use of [kubernetes](http://kubernetes.io)
[secrets](http://kubernetes.io/v1.0/docs/user-guide/secrets.html#secrets)
to set up the values of environment variables. To use it in kubernetes pod
creation...

* Mount the secrets under `/secrets` folder
* Use the following keys for matching the environmental variables

    POSTGRES_PASSWORD : pgpass
    ADMIN_USER : adminuser
    ADMIN_PASS : adminpass
    ADMIN_DB : admindb


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

# Supported Docker versions

This image is officially supported on Docker version 1.8.2.

Support for older versions (down to 1.0) is provided on a best-effort basis.

# User Feedback

## Documentation

Documentation for this image is stored in the [`postgres/` directory](https://github.com/docker-library/docs/tree/master/postgres) of the [`docker-library/docs` GitHub repo](https://github.com/docker-library/docs). Be sure to familiarize yourself with the [repository's `README.md` file](https://github.com/docker-library/docs/blob/master/README.md) before attempting a pull request.

## Issues

If you have any problems with or questions about this image, please contact us on the [mailing list](http://www.postgresql.org/community/lists/subscribe/) or through a [GitHub issue](https://github.com/docker-library/postgres/issues).

You can also reach many of the official image maintainers via the `#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans on the [mailing list](http://www.postgresql.org/community/lists/subscribe/) or through a [GitHub issue](https://github.com/docker-library/postgres/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.
