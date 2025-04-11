FROM mysql:8.0

ENV MYSQL_DATABASE=socialmediause
ENV MYSQL_ROOT_PASSWORD=root

COPY ./socialmediause-db_2025-02-08.sql /docker-entrypoint-initdb.d/
