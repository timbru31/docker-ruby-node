FROM ruby:2.6-alpine@sha256:2ed0fef592d2cc544dc4b14b6c17106907a58be1399568dcf0f4de668ba14afc
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
