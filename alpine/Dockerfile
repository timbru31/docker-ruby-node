FROM ruby:2.6-alpine3.9@sha256:3b838db52e67d04c87ebd212b3b508cbe83382177dd6829c2b2d3ec41da3a24a
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
