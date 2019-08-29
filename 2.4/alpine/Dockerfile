FROM ruby:2.4-alpine@sha256:0ce6fa9a8fbcedf492fc26e6ea43ffe5b1768cf3d53ad795f50d4c618359d0c1
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
