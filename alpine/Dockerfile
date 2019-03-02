FROM ruby:2.6-alpine3.8@sha256:7eaa6cfcd13694ff2ea31f6dd3dcb8fae5bc22c185ce2559591b627874bb99ca
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
