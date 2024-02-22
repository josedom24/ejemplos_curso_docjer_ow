# syntax=docker/dockerfile:1
FROM debian:stable-slim
RUN apt-get update  && apt-get install -y  apache2 
WORKDIR /var/www/html
COPY index.html .
CMD apache2ctl -D FOREGROUND
