# Ubuntu 20.10の通常サポート期限: 2021年7月
FROM ubuntu:20.10

RUN  apt-get update -qq &&\
     DEBCONF_NOWARNINGS=yes apt-get install -y -q --no-install-recommends \
       curl ca-certificates &&\
     apt-get clean &&\
     rm -rf /var/lib/apt/lists/*
