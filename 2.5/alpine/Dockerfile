FROM ruby:2.5-alpine@sha256:2e2e5fc72ae875c90007a5c12f50c2a768e9ba10794a65dbdc1162386b92129d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
