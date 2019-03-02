FROM ruby:2.6-alpine3.8@sha256:36a040c3e37c2381073c93c7fa311bdd75ec9db6b459771cc8864cd7a2019149
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
