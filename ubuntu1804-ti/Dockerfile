
FROM ubuntu:18.04
MAINTAINER smoroz@mint-innovations.com

RUN set -xe \
    && dpkg --add-architecture i386 \
    && apt-get update \
    && apt-get install -y --no-install-recommends \
        build-essential \
        make \
        gcc \
        libc6:i386 \
        libstdc++6:i386 \
        libncurses5:i386 \
        zlib1g:i386 \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

