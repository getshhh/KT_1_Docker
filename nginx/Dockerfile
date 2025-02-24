FROM ubuntu:latest

RUN apt update && \
    apt install -y wget curl nginx

COPY ./site /var/www/html


EXPOSE 80
EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]
