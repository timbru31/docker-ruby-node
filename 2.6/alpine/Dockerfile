FROM ruby:2.6-alpine@sha256:2564f9e429347326297055ba27092e8e575f9ee4fb409c960388a4b04ca9ebe4
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
