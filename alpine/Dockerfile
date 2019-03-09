FROM ruby:2.6-alpine3.9@sha256:7fdd3e9ab2f9797c280deeb1a97d8158b28bd33eb98531b928cb006270712d2e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
