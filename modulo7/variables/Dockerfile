# syntax=docker/dockerfile:1
ARG PHP_VERSION=8.0
ARG APP_VERSION=desarrollo
FROM php:${PHP_VERSION}
COPY app /var/www/html/
ENV VERSION=${APP_VERSION}
EXPOSE 80
