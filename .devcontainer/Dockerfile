# syntax=docker/dockerfile:1
FROM espressif/idf:release-v5.5

USER ubuntu

WORKDIR /workspace
RUN git config --global --replace-all safe.directory /opt/esp-idf && \
    git config --global --add safe.directory "/opt/esp-idf/*"
