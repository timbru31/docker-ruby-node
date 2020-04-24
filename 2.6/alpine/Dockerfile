FROM ruby:2.6-alpine@sha256:50b9fb16b7ea921d62a9d42b064196e07439c9e91c5a47ff5954eebdac929cd2
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
  echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/main >> /etc/apk/repositories && \
  apk add --no-cache \
  libstdc++@edge \
  libuv@edge \
  nodejs@edge \
  nodejs-npm@edge \
  yarn@edge
