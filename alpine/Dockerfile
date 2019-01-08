FROM ruby:2.6-alpine3.8@sha256:58bb64194026bff3c83c980dccd266e0ddcf50001e231d0f69f08758365e1f39
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
