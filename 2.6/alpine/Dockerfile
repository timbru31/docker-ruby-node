FROM ruby:2.6-alpine@sha256:8683463fbfd706a1b30e0f97ba1693d57aad32d27ccaec36d204cec1feccc784
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
