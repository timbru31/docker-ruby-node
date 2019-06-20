FROM ruby:2.4-alpine@sha256:3fc65da4e2ba2cc888f72629902f3923854c7e64ae2d2941829eba6741f35956
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
