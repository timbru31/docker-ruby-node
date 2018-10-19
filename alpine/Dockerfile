FROM ruby:2.5-alpine3.7@sha256:ef16b55e5bbebf270943d6bfd315b926d4054cbe7c760ebb0215099e3b12e86c
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
