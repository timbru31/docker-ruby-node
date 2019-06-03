FROM ruby:2.5-alpine@sha256:d491e6760e8fc6dd9cc94d00f9f46df2b0e18f6f988276b996de298b0ffaba20
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
