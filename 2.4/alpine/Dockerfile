FROM ruby:2.4-alpine@sha256:64d26cf4712e5a761f80a962facdfa408138308f7d5ddbcdfe07b2aa1fad4ffb
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
