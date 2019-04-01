FROM ruby:2.5-alpine@sha256:b19794d10847886ab515ca930c79b693ba026b1cec5e5e8dfe264820d7b80fc3
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
