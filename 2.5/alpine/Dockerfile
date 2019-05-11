FROM ruby:2.5-alpine@sha256:4644107eb33cf1d8bd3524ae560de28a0b1eb51a35376d1e47c376d617754612
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
