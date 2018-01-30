# Apache2 Docker Container for WPLib Box
This is the repository for the [Apache2](http://apache.org/) Docker container implemented for [WPLib-Box](https://github.com/wplib/wplib-box).
It currently provides versions 2.4.27 2.4.29


## Supported tags and respective Dockerfiles

`2.4.29`, `2.4`, `latest` _([2.4.29/Dockerfile](https://github.com/wplib/apache2-docker/blob/master/2.4.29/Dockerfile))_

`2.4.27` _([2.4.27/Dockerfile](https://github.com/wplib/apache2-docker/blob/master/2.4.27/Dockerfile))_


## Using this container.
If you want to use this container as part of WPLib, then use the Docker Hub method.
Or you can use the GitHub method to build and run the container.


## Using it from Docker Hub

### Setup from Docker Hub
A simple `docker pull wplib/TEMPLATE_PACKAGE` will pull down the latest version.


### Runtime from Docker Hub
start - Spin up a Docker container with the correct runtime configs.
`start`


stop - Stop a Docker container.
`stop`


run - Run a Docker container in the foreground, (all STDOUT and STDERR will go to console). The Container be removed on termination.
`run`


shell - Run a shell, (/bin/bash), within a Docker container.
`shell`


rm - Remove the Docker container.
`rm`


## Using it from GitHub repo

### Setup from GitHub repo
Simply clone this repository to your local machine

`git clone https://github.com/wplib/apache2-docker.git`


### Building from GitHub repo
`make build` - Build Docker images. Build all versions from the base directory or specific versions from each directory.


`make list` - List already built Docker images. List all versions from the base directory or specific versions from each directory.


`make clean` - Remove already built Docker images. Remove all versions from the base directory or specific versions from each directory.


`make push` - Push already built Docker images to Docker Hub, (only for WPLib admins). Push all versions from the base directory or specific versions from each directory.


### Runtime from GitHub repo
When you `cd` into a version directory you can also perform a few more actions.

`make start` - Spin up a Docker container with the correct runtime configs.


`make stop` - Stop a Docker container.


`make run` - Run a Docker container in the foreground, (all STDOUT and STDERR will go to console). The Container be removed on termination.


`make shell` - Run a shell, (/bin/bash), within a Docker container.


`make rm` - Remove the Docker container.


