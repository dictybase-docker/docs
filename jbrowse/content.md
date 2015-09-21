
%%LOGO%%

# Using the image
The image is primarilly meant to be use as an base image to create other final
usable images.  The image contains ..

* An unmodified version of decompressed [Jbrowse](http://jbrowse.org) release at `/usr/src/jbrowse`. The folder is also set as a docker [working directory](http://docs.docker.com/reference/builder/#workdir).
* A command line application to serve all static files(js/css/html/images etc.) from jbrowse folder by default.
* Default port exposed at `9595`
* No default `CMD` or `ENTRYPOINT`

All the docker commands below are expected the image to be created under dictybase namespace.

## Command line help from the container

    docker run --rm dictybase/jbrowse app help

    NAME:
       jbrowse - A new cli application

    USAGE:
       jbrowse [global options] command [command options] [arguments...]

    VERSION:
       1.0.0

    COMMANDS:
       serve	A http static file server for jbrowse
       help, h	Shows a list of commands or help for one command
       
    GLOBAL OPTIONS:
       --help, -h		show help
       --version, -v	print the version

Now help for the subcommand `serve`

    docker run --rm dictybase/jbrowse app serve -h
       
    NAME:
       serve - A http static file server for jbrowse

    USAGE:
       command serve [command options] [arguments...]

    DESCRIPTION:
       

    OPTIONS:
       --jbrowse-folder, --jf 		Location of jbrowse source folder [$JBROWSE_FOLDER]
       --port, -p '9595'			http port, default is 9595
       --log-folder, -f '/log/jbrowse'	Folder where the log file will be kept
       --log-file, -l 'frontend.log'	Name of the log file, the logging is done in apache combined log format
       --no-stderr				Turn off stderr logging, on by default

## Starting a container
The is mainly given as an example, it might not be very useful

    docker run --rm -v /log -p 9595:9595 dictybase/jbrowse app serve

The above command will start a static file server for default jbrowse folder and will log all request in `/log/jbrowse/frontend.log` file in `/log` data volume.

## Jbrowse container with flat file backend
It needs bunch of containers working together ..

* A data container for hosting the json formatted custom data for jbrowse. A
  host folder or file containing the data should be mapped to this container.
  However, instruction for preparing jbrowse data is outside the scope of this
  document. 
* A custom jbrowse container that extends this image and symlinks its data
  folder to the previous data container.


### Create custom jbrowse image

`Dockerfile` to extend this image

    FROM dictybase/jbrowse
    VOLUME /data
    RUN cd jbrowse && mkdir -p data && ln -sf /data data 

Build it

    docker build --rm -t dictybase/jbrowse-frontend .

The above will create an image whose default data container will be symlnked to `/data` folder.

### Create data container for jbrowse data

    docker run -v /home/user/jbrowse_data:/data progirum/busybox 


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
