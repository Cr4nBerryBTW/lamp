FROM bitnami/php-fpm

RUN apt-get update && apt-get install -y \
                              curl \
                              php-pdo \
                              php-pdo-mysql \
                              php-mysqli

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer




