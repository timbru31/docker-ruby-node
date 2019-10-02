FROM ruby:2.5-alpine@sha256:1af6542ab5903182705337ecd2fc0961d27bd3a5a5634ce3bdb0d1c34e9fc6ba
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
