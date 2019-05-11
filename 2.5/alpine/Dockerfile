FROM ruby:2.5-alpine@sha256:d1489f4da360edef170efdc24d76d295e42d74c6dbbca0e66a520c9f9190cc0d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
