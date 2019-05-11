FROM ruby:2.5-alpine@sha256:7d1c019b9de8ed534f01460232a9eee14d93ac5a46288ebd05bc2a6bbae40b76
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
