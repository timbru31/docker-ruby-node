FROM ruby:2.5-alpine3.7@sha256:5c2c66e70bfbb3f08d67e1335f555ccf69f6e3bcbf418a7b2fe3abf31d330ff2
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
