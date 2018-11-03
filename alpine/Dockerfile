FROM ruby:2.5-alpine3.7@sha256:60cf938aca2fca11442516bd2a597c3df944333bdb5b78a9a0ac70d2e79c5f62
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
