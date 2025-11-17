# syntax=docker/dockerfile:1
FROM espressif/idf:release-v5.5

USER ubuntu

# create bind mount point
RUN mkdir -p /home/ubuntu/libs/arduino-libs

WORKDIR /workspace
RUN git config --global --replace-all safe.directory /opt/esp-idf && \
    git config --global --add safe.directory "/opt/esp-idf/*"
