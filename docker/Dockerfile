FROM php:8.5.0RC5-cli

RUN apt-get update && apt-get install -y \
        unzip \
    && docker-php-source extract \
    && docker-php-ext-install pdo_mysql \
    && docker-php-source delete