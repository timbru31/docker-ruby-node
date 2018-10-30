FROM ruby:2.5-alpine3.7@sha256:7ec4a10fe94adbe32246a8ff30b9c75469031c466ce0d2882c926d662681242c
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
