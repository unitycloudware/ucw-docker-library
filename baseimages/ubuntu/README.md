# Ubuntu Base Image for UCW Platform

## Quick links

* [UCW Platform][1]

## Description

The UCW Docker Library provides set of images and maintenance scripts for development, deployment, and testing of the [UCW Platform](https://unitycloudware.com). See [the Docker Hub page](https://hub.docker.com/r/unitycloudware) for the full list of available Docker images for the UCW Platform and for information regarding contributions and issues.

[1]: https://unitycloudware.com

## Docker image unitycloudware/ubuntu

* Includes updates
* [Dockerfile and source code](https://github.com/unitycloudware/ucw-docker-library)

### Build the Image

~~~~
$ docker build -t unitycloudware/ubuntu .
~~~~

### Run the Image

~~~~
$ docker run -it --rm unitycloudware/ubuntu /bin/bash
~~~~