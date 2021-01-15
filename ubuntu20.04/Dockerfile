FROM ubuntu:20.04

RUN  apt-get update -qq &&\
     DEBCONF_NOWARNINGS=yes apt-get install -y -q --no-install-recommends \
       curl ca-certificates &&\
     apt-get clean &&\
     rm -rf /var/lib/apt/lists/*
