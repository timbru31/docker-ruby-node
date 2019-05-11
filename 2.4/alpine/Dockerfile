FROM ruby:2.4-alpine@sha256:62ee30ba72a95c98a1c864c0b8e8703c5d3b86a208204095432d61fb48f17622
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
