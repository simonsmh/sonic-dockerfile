FROM nginx:mainline

RUN apt-get -qqy update && \
    apt-get -qqy --no-install-recommends install \
    wget \
    gnupg

RUN apt-get -qqy update && \
    apt-get -qqy --no-install-recommends install chromium chromium-driver && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
