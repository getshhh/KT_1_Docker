FROM postgres:latest

ENV POSTGRES_USER=postgres
ENV POSTGRES_NAME=postgres
ENV POSTGRES_PASS=root


COPY init.sql /docker-entrypoint-initdb.d/
