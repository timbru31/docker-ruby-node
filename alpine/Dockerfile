FROM ruby:2.6-alpine3.8@sha256:19dd5a7bf2bb3896cd510b0b2fdedd71ccfa77147aaf9070b0a000ecb669c6c6
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
