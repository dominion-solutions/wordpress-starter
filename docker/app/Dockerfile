FROM php:7-fpm-alpine
RUN docker-php-source extract &&\
	docker-php-ext-install mysqli pdo pdo_mysql &&\
	docker-php-source delete