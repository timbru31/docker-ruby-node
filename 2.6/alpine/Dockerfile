FROM ruby:2.6-alpine@sha256:868d2367ecd0c98c63e4abe84a6aa122b643b87f7f0fdfb2157776f9e13baa48
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
