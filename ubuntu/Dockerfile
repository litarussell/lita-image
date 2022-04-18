FROM ubuntu:latest

WORKDIR /root

RUN set -x; buildDeps='gcc g++ make gdb flex bison' \
    && apt-get update \
    && apt-get -y upgrade \
    && apt-get install -y $buildDeps \
    && apt-get autoremove

RUN mkdir -p /root/mini_c
