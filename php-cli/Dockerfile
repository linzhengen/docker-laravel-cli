FROM php:7.4-cli

COPY --from=composer:2.0 /usr/bin/composer /usr/bin/composer
COPY ./php.ini /usr/local/etc/php/php.ini

WORKDIR /app
