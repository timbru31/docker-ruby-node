FROM ruby:2.5-alpine3.8@sha256:2e150b08ffac4d24787261dbb199a5d04ea62fc0501ae1d9b8421ce1d8e7cb68
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
