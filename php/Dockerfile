FROM php:7.1.24-fpm-alpine

RUN docker-php-ext-install -j5 pdo pdo_mysql mbstring

CMD ["php-fpm"]