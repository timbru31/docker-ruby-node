FROM ruby:2.6-alpine@sha256:346727c6b2ecc3f41eaeb7dc74b3bc4fb97c8589ca44111642ef48f13f86d9ba
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
