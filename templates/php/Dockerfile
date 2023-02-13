FROM php:fpm

RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql

RUN apt-get -y update
RUN apt-get install -y libicu-dev
RUN docker-php-ext-configure intl 
RUN docker-php-ext-install intl
