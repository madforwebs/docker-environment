FROM mysql:8.0.20
ARG TIMEZONE

RUN apt-get update && apt-get install -y nano

COPY docker/mysql/my.cnf /etc/mysql/conf.d/
#RUN echo "upstream php-upstream { server php:9000; }" > /etc/mysql/conf.d/upstream.conf
