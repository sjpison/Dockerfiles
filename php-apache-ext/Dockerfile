FROM php:7.1.12-apache
RUN apt-get update && apt-get install -y --no-install-recommends \
    libpng12-dev \
    libjpeg-dev \
    libpq-dev
RUN docker-php-ext-configure gd --with-png-dir=/usr --with-jpeg-dir=/usr
RUN docker-php-ext-install \
    gd \
    mbstring \
    pdo \
    pdo_mysql \
    mysqli \
    zip
RUN a2enmod rewrite
