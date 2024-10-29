FROM php:8.3-fpm

# Install PDO MySQL extension
RUN docker-php-ext-install pdo pdo_mysql

# Copy custom PHP configuration
COPY ./docker/php/local.ini /usr/local/etc/php/conf.d/
