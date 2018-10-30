FROM ruby:2.5-alpine3.7@sha256:288888be7b814a107c8ac257a40d7600f8772bced00f7e1fda98460f0271de05
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
