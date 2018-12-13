FROM ruby:2.5-alpine3.8@sha256:d4bf19a8b82cbfb3fab59404f9e55a57a716e37526fafde9ff175d873a54bb4f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
