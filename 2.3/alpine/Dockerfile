FROM ruby:2.3-alpine@sha256:60c44723f12848e72d9b87efbb00cff4e5d34fec9520e0692e26e181f54302be
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
