# syntax=docker/dockerfile:1
ARG PHP_VERSION=8.2-apache
FROM php:$PHP_VERSION
ARG APP_VERSION=desarrollo
ENV VERSION=$APP_VERSION
COPY app /var/www/html/
EXPOSE 80
