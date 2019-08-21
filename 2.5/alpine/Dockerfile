FROM ruby:2.5-alpine@sha256:325c5d5346ccf0211524d279c9a5b034370aa7b6ce74cb3e9b5a9033f8f7cb91
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
