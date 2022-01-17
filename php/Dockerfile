FROM phpdockerio/php7-cli

RUN apk update
RUN apk upgrade

RUN apk add curl

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin/ --filename=composer


