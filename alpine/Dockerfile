FROM ruby:2.5-alpine3.8@sha256:3d684eea757a9c2e21bf7fd69b5f7e29c46f721f6c074df31b8bd76ac92fb46b
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
