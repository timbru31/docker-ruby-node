FROM ruby:2.4-alpine@sha256:50df9575abe386afac9a0d0c7c1546fe66fe8fbcbca2c95cb1c35fca3c5cdeeb
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
