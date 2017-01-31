## Nordic NRF5 SDK Dockerfile
This repository contains the Dockerfile used for building an image including Nordic's SDK.

### Base Docker Image

* [ubuntu:16.04](https://registry.hub.docker.com/u/library/ubuntu/)

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/barracksiot/nrf5_sdk_docker/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull barracksiot/nrf5_sdk_docker`

   (alternatively, you can build an image from Dockerfile: `docker build -t="barracksiot/nrf5_sdk_docker" github.com/barracksiot/nrf5_sdk_docker`)


### Usage

    docker run -it --rm barracksiot/nrf5_sdk_docker
