<h1 align="center">  Demo Krown </h1> <br>

<p align="center">
  This microservice is responsible for...
</p>

## Table of Contents

- [Domain](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Quick Start](#quick-start)

## Domain




## Features :heavy_check_mark:



## Requirements
The application can be run locally or in a docker container, the requirements for each setup are listed below.

### Docker
* [Docker](https://www.docker.com/get-docker)

## Quick Start 
### Run Docker

First, build the image:
```bash
$ docker build . -t newsletter-service:{version}
```

When ready, run it:
```bash
$ docker run -p {port:port} newsletter-service:{version}
```

The application will run by default on port `80`

### Microservice Dependencies
Open CMD, move to the projects directory, and run the following command to install the default docker-compose file:
```
$ docker-compose up -d
```

In case you want to install a different docker-compose file, run the following command:
```
$ docker-compose -f {docker-compose-file-name}.yml up -d
