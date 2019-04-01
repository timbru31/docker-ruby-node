FROM ruby:2.4-alpine@sha256:3bf2528db799c75ac15919ec34e6e7931ee0c20eaf3e7afb5b21d0f43e7bae1a
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
