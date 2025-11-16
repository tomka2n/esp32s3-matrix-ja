# syntax=docker/dockerfile:1
FROM espressif/idf:release-v5.5

RUN apt-get update && apt-get install -y && \
    locales && locale-gen en_US.UTF-8 && \
    update-locale LANG=en_US.UTF-8

USER ubuntu

WORKDIR /workspace
RUN git config --global --replace-all safe.directory /opt/esp-idf && \
    git config --global --add safe.directory "/opt/esp-idf/*"
