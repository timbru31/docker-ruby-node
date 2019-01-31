FROM ruby:2.6-alpine3.8@sha256:3e3e25d53934c6e9fc2401738d1ddd3b1edbdb13d5509bbbd061b2b1f3c30f76
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
