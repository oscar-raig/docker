# Docker

This project contains a set of Dockerfiles nodejs, C++ container with some tools.



For building from Dockerfile

1. Download Dockerfile

2. Build docker 
3. 
docker build --rm -t your-name/c7-systemd .

## For running an interactive shell:

docker run  -ti --entrypoint /bin/bash    your-name/c7-systemd


## For running an interactive shell with volume:

docker run   -ti --entrypoint=/bin/bash  -v /Users/oscarraig/git-public/Calculate_Regression/:/home/  oscarraig/c7-boost-gtest

## Enter a running docker container

docker exec -it [container-id] bash

## Copying a file from docker to host

docker cp CONTAINER_ID:/etc/nginx/conf.d/default.conf .
