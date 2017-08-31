FROM ubuntu:xenial

COPY .apt.sources.list /etc/apt/sources.list

RUN apt-get update \
 && apt-get install -y --no-install-recommends arping \
  && apt-get clean

