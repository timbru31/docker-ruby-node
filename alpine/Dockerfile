FROM ruby:2.6-alpine3.9@sha256:9fee6680610546f3f50e3d00e63ca73b53f6bc04a2b0ed4cd70b126956358e4e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
