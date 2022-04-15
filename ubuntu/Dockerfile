FROM ubuntu:latest

WORKDIR /root

RUN set -x; buildDeps='gcc make' \
    && apt-get update \
    && apt-get -y upgrade \
    && apt-get install -y $buildDeps \
    && apt-get autoremove

RUN mkdir -p /root/mini_c
