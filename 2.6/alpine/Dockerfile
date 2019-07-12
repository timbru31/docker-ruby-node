FROM ruby:2.6-alpine@sha256:cbcf3c98e7bd7dfd0a535c91a6c186eed483680cefe0c99ed1ed46d6efbb0e7b
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
