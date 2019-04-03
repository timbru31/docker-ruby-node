FROM ruby:2.4-alpine@sha256:7d74b0be9b62f83ffb6f136b8f9ad09e54819490b330e33f4a6fd3f97d333cb5
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
