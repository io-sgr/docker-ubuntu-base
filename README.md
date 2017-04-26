## Base and latest Ubuntu OS image

This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/sgrio/ubuntu-base/) published to the public [Docker Hub](https://hub.docker.com/).

### Docker Tags

`sgrio/ubuntu-base` provides only one single tagged image:

* `latest` (default): based on `ubuntu:latest`

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/sgrio/ubuntu-base/) from public [Docker Hub](https://hub.docker.com/): `docker pull sgrio/ubuntu-base`

   (alternatively, you can build an image from Dockerfile: `docker build -t="sgrio/base-ubuntu" https://raw.githubusercontent.com/sgr-io/docker-ubuntu/base/master/Dockerfile`)

### Usage

    docker run -it sgrio/ubuntu-base /bin/bash
