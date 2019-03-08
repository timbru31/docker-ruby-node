FROM ruby:2.6-alpine3.9@sha256:7268521a1e3808e502f81b8307e32979ed8f80504bf6e37dce10e793c2373a1f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
