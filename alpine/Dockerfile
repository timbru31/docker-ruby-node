FROM ruby:2.6-alpine3.8@sha256:76a486e8fdb16d3fa6516300a062a12c33a4038fd3935e49adb1ba869c72f346
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
