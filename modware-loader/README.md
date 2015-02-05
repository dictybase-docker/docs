# Supported tags and respective `Dockerfile` links

- [`devel` (*devel /Dockerfile*)](https://github.com/dictybase-docker/modware-loader/blob/3000d46/devel /Dockerfile)

For more information about this image and its history, please see the [relevant
manifest file
(`library/modware-loader`)](https://github.com/docker-library/official-images/blob/master/library/modware-loader)
in the [`docker-library/official-images` GitHub
repo](https://github.com/docker-library/official-images).


modware-loader is a collection of command line applications to export and
import biological data from [chado](http://gmod.org/wiki/Introduction_to_Chado)
database.

> https://github.com/dictyBase/Modware-Loader

# Using the image

This image includes a full installation of **modware-loader** including all of
its commands are exposed to run through docker `run` command. This image is
solely intended for data load and unloading purposes and therefore is not
expected to run in detached(background) mode. All of its commands are expected
to be executed like a command line prompt through docker `run` command.


## Using the container

Any of one of the modware-loader command could be executed through docker `run` command.

* modware-import
* modware-export
* modware-update
* modware-dump
* modware-load
* modware-transform


List all subcommands of modware-export

    docker run --rm dictybase/modware-loader:devel modware-export

Get command line usage of `chado2fasta` subcommand

    docker run --rm dictybase/modware-loader:devel modware-export chado2fasta --usage


For details visit [here](https://github.com/dictyBase/Modware-loader)

# Supported Docker versions

This image is officially supported on Docker version 1.4.1.

Support for older versions (down to 1.0) is provided on a best-effort basis.

# User Feedback

## Issues

If you have any problems with or questions about this image, please contact us
 on the [issue tracker](https://github.com/dictyBase/Modware-Loader/issues) or through a [GitHub issue](https://github.com/docker-library/modware-loader/issues).

You can also reach many of the official image maintainers via the
`#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small;
we are always thrilled to receive pull requests, and do our best to process them
as fast as we can.

Before you start to code, we recommend discussing your plans on the [issue tracker](https://github.com/dictyBase/Modware-Loader/issues) or 
through a [GitHub issue](https://github.com/docker-library/modware-loader/issues), especially for more ambitious
contributions. This gives other contributors a chance to point you in the right
direction, give you feedback on your design, and help you find out if someone
else is working on the same thing.
