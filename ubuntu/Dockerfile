FROM ubuntu:18.04

RUN apt-get update && apt-get install -y curl vim sudo

WORKDIR /var/www/httpd

RUN touch index.html

RUN echo "Hello World from falcon!!!" > index.html

