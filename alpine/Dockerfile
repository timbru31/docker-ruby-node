FROM ruby:2.5-alpine3.7@sha256:99ec405f57a949be5683e00d799c8d4170756d3ffead9a6c6e59f4706dcb46a3
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
