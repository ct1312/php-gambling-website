FROM php:7.2-fpm

RUN docker-php-ext-install opcache

RUN docker-php-ext-install pdo_mysql

# Must have for enqueue/amqp-lib
RUN docker-php-ext-install bcmath
