FROM ruby:2.6-alpine3.8@sha256:1d28e4931cfa5776e67e674ec93a586855c01d29c78e36a03305a559c80ef43e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
