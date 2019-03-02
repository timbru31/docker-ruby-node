FROM ruby:2.6-alpine3.8@sha256:f2296ab1f123d8ba49810a06e6005d35ec0d79b1abc8eefc552cede6ad22d7f0
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
