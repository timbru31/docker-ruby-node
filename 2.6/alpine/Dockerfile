FROM ruby:2.6-alpine@sha256:164ad2564d946833890177b9fdc440701e18bd5bf1e32f27fcc9c04131dd1a9c
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
