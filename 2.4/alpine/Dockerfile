FROM ruby:2.4-alpine@sha256:31e295d987a7091011f4c1219e8487d0bad3fad96de047385a35a1ff566ff8f0
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
