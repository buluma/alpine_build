# Alpine Test Build

[![Docker Test](https://github.com/buluma/alpine_build/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/buluma/alpine_build/actions/workflows/docker-publish.yml) [![Docker Image CI](https://github.com/buluma/alpine_build/actions/workflows/docker-image.yml/badge.svg)](https://github.com/buluma/alpine_build/actions/workflows/docker-image.yml) ![Docker Pulls](https://img.shields.io/docker/pulls/buluma/alpine_build)

An Alpine base image for patching.

### Building
```sh
$ git clone https://github.com/buluma/alpine_build.git
$ cd alpine_build
$ docker build -f Dockerfile -t buluma/alpine_build:latest .
```

