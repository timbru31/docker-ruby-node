FROM ruby:2.6-alpine@sha256:60a0f16c15af8e5dad39617e5819fdd4978bec6a1d3da2202f96d530cbd90946
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
