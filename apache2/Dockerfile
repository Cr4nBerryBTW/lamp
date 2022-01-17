FROM ubuntu/apache2
RUN apt update -y && apt upgrade -y
RUN a2enmod rewrite
RUN a2enmod proxy
RUN a2enmod proxy_fcgi
COPY 000-default.conf /etc/apache2/sites-available/000-default.conf
