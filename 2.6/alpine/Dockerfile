FROM ruby:2.6-alpine@sha256:dfa9ec3eac436e243b371c0f2e5cc6dba4b65a72b130d1a12e6e216661eb2bc3
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
