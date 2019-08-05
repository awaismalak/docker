FROM php:7.2-apache
RUN apt-get update && apt-get -y install mariadb-client
RUN  docker-php-ext-install mysqli && docker-php-ext-enable mysqli   