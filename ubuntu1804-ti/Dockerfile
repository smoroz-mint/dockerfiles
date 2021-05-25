
FROM ubuntu:18.04
MAINTAINER smoroz@mint-innovations.com

RUN set -xe \
    && dpkg --add-architecture i386 \
    && apt-get update \
    && apt-get install -y --no-install-recommends \
        software-properties-common \
        apt-utils \
        file \
        curl \
        mtd-utils \
        fontconfig \
        fontconfig-config \
        fonts-dejavu-core \
        openssh-client \
        python3.8 \
        p7zip-full \
        \
        build-essential \
        make \
        gcc \
        g++ \
        git \
        pkg-config \
        \
        libc6:i386 \
        libstdc++6:i386 \
        libncurses5:i386 \
        zlib1g:i386 \
        \
        libc6 \
        libva2 \
        libva-drm2 \
        libva-x11-2 \
        libx11-6 \
        liblzma5 \
        zlib1g \
        \
        libavahi-client3 \
        libavahi-common-data \
        libavahi-common3 \
        libcups2 \
        libdbus-1-3 \
        libdouble-conversion1 \
        libegl1-mesa-dev \
        libevdev2 \
        libfontconfig1 \
        libfreetype6 \
        libgles2-mesa-dev \
        libglib2.0-0 \
        libglu1-mesa \
        libglu1-mesa-dev \
        libgraphite2-3 \
        libgssapi-krb5-2 \
        libgudev-1.0-0 \
        libharfbuzz0b \
        libice6 \
        libicu60 \
        libinput-bin \
        libinput10 \
        libjpeg-turbo8 \
        libjpeg8 \
        libk5crypto3 \
        libkeyutils1 \
        libkrb5-3 \
        libkrb5support0 \
        libmtdev1 \
        libpng16-16 \
        libsm6 \
        libssl1.1 \
        libwacom-common \
        libwacom2 \
        libwayland-bin \
        libwayland-cursor0 \
        libwayland-dev \
        libwayland-egl1 \
        \
        libxcb-icccm4 \
        libxcb-image0 \
        libxcb-keysyms1 \
        libxcb-render-util0 \
        libxcb-shm0 \
        libxcb-util1 \
        libxcb-xinerama0 \
        libxcb-xkb1 \
        libxi6 \
        libxkbcommon-x11-0 \
        libxkbcommon0 \
        libxml2 \
        libxcb-xinerama0-dev \
        ucf \
        x11-common \
        xkb-data \
        \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

