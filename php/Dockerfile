FROM php:7.4-apache
COPY ./php.ini /usr/local/etc/php/
RUN apt-get update && apt-get install -y \
  libfreetype6-dev \
  libjpeg62-turbo-dev \
  libpng-dev \
  libonig-dev \
  zip \
  unzip \
  git \
  && docker-php-ext-install \
  pdo_mysql \
  mysqli \
  gd \
  iconv \