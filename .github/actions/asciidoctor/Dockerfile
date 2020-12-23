FROM ubuntu:21.04

RUN apt update; \
    apt install ruby-full -y; \
    gem install asciidoctor-pdf

COPY ./entrypoint.sh /entrypoint.sh

ENTRYPOINT ["bash","/entrypoint.sh"]