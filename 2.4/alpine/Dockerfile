FROM ruby:2.4-alpine@sha256:2db399142fa2c8be2740d6076d9c2802ca809deb0d3e2a3d278f11a718f4d632
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
