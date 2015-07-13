# docker.datastore
Small set of docker images for datastore (a platform to manage IoT data).

## Setup

This project use docker with docker-compose tool to manage all containers.

Setup docker-compose :

    pip install -U docker-compose

Populate subfolders with images files:

    git clone https://github.com/sourceperl/docker.mosquitto.git
    git clone https://github.com/sourceperl/docker.sigserver.git
    git clone https://github.com/sourceperl/docker.mqttwarn.git

Copy/edit configuration(s) file(s) :

    vim docker.mqttwarn/mqttwarn.ini

## Start all

Start all containers (config in docker-compose.yml)

    docker-compose up -d

*This build images and start all containers.*

