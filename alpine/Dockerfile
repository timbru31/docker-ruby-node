FROM ruby:2.5-alpine3.7@sha256:a8f16d1cac06388a85e2f9af9fcc1a23797f17211b8befbed108c8c13b727349
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
