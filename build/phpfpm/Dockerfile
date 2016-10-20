FROM php:7.0-fpm

MAINTAINER Thomas Bisignani <contact@thomasbisignani.com>

RUN docker-php-ext-install mysqli \
    && docker-php-ext-install pdo \
    && docker-php-ext-install pdo_mysql

# Set up the PHP configuration file
ADD conf/php.ini /usr/local/etc/php/
