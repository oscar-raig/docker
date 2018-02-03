FROM node:6.9.4
MAINTAINER Oscar Raig <oscar.raig@gmail.com>


RUN \
  apt-get update && \
  apt-get install -y python python-dev python-pip  && \
  rm -rf /var/lib/apt/lists/*
RUN pip install boto3==1.3.0 
RUN npm install webpack -g
