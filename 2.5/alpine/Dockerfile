FROM ruby:2.5-alpine@sha256:816bac98abfda8ce0f3fe92a18ab6a1bf2ce2e3cc91e6bb287a24a0b1a0026d7
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
