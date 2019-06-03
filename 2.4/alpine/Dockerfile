FROM ruby:2.4-alpine@sha256:f540b4f3934120f9af7f7d3cb7da6354f9cd60bb76a20ffaebf59784506be246
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
