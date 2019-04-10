FROM ruby:2.4-alpine@sha256:d28b0eb85440f554a93ded51b23f3c5c136ac892eae56089ae89a541ea24bc22
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
