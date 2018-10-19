FROM ruby:2.5-alpine3.7@sha256:55efabaf06ae83aeb1ae6d4e99b9b3677197da8122031467631e9f3d703c8815
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
