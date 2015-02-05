
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

