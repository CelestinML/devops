FROM debian:latest

RUN apt update

RUN apt -y install certbot

RUN apt -y install python3-certbot-dns-ovh

RUN apt -y install python3-certbot-nginx

CMD [ "/bin/sh", "-c", "while true; do sleep 1; done;" ]
