FROM php:7.2-fpm

# install git zip unzip vim
RUN apt-get update \
&& apt-get install -y \
git \
zip \
unzip \
vim

# install DB
RUN apt-get update \
    && apt-get install -y libpq-dev \
    && docker-php-ext-install pdo_mysql pdo_pgsql

# install gnupg
RUN apt-get install -y gnupg

WORKDIR /laravel
