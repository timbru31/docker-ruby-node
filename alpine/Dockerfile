FROM ruby:2.5-alpine3.7@sha256:2e4f0345a9089f47bbb35aea656fb0be85757833b4e7a529dd57d482ed80357f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
