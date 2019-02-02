FROM ruby:2.6-alpine3.8@sha256:c6007b724091bdfb9d13cff040735d08c4574ea6a41ecb28f100ab46349efe07
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
