FROM ruby:2.5-alpine3.7@sha256:1be6204f647a89f5498729bc08b438c800f6cbbda310bc0b9d807193248e418b
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
