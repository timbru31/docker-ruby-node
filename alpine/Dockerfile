FROM ruby:2.5-alpine3.7@sha256:c061912669b5ad11b09cece9eeaa847f9208ea8cdf6621ff6bd4b68fec32168d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
