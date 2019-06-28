FROM ruby:2.5-alpine@sha256:d1eb9eebc6de1887c865893993a0cf52bfa384449b722da9ea5b3b095a27d17d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
