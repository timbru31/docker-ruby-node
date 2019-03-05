FROM ruby:2.6-alpine3.9@sha256:6957d50ac5322fce3c131cee1aeb089afbf17a806ef813bbd98179f0ec28ff65
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
