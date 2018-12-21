FROM ruby:2.5-alpine3.8@sha256:c6158d193e224e16bf5aaf2bbb6802120e48d1d86df04b9d34f65aded988c0ff
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
