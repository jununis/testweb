FROM php:7.4-fpm

RUN apt-get update && apt-get install -y \
    git \
    unzip

COPY php.ini /usr/local/etc/php/

WORKDIR /var/www/html

EXPOSE 9000

CMD ["php-fpm"]
