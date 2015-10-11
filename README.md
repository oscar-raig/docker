# docker

For building from Dockerfile

1. Download Dockerfile

2. Build docker 
3. 
docker build --rm -t your-name/c7-systemd .

##For running an interactive shell:

docker run  -ti --entrypoint /bin/bash    your-name/c7-systemd


##For running an interactive shell with volume:

docker run   -ti --entrypoint=/bin/bash  -v /Users/oscarraig/git-public/Calculate_Regression/:/home/  oscarraig/c7-boost-gtest

##Eneter a running docker container

docker exec -it [container-id] bash
