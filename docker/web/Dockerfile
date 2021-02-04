FROM php:7.4-apache

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN apt-get update && apt-get upgrade -y && apt-get install -y git
RUN git config --global user.email "mahmoud.dahab99@gmail.com" && git config --global user.name "Mahmoud Ragab Dahab"


# install imagick
RUN apt-get update && apt-get install -y libmagickwand-dev --no-install-recommends && rm -rf /var/lib/apt/lists/*
RUN printf "\n" | pecl install imagick
RUN docker-php-ext-enable imagick

RUN docker-php-ext-install gd
RUN docker-php-ext-install mysqli pdo pdo_mysql


