FROM ruby:2.6-alpine3.8@sha256:76c74ae59ba14d55e540ae5ca51646dd350b17270d328d80a9c026d53d62138d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
