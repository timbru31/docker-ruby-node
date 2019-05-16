FROM ruby:2.4-alpine@sha256:d36e72bcb936ccc72f9b097cb26e15a52540bb6a9d28c1dd8bd01fe37403dea7
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
