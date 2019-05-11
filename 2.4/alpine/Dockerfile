FROM ruby:2.4-alpine@sha256:1c730ada88be6ea4cff4490e01b55a3a85ab6c9ff1f50ba95530a64575cad1f8
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
