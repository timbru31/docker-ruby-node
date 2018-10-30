FROM ruby:2.5-alpine3.7@sha256:9b9226851c7d4a92750ae3170cc911d98e17c9ccf4aad957c92fd8d20cd0bf92
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
