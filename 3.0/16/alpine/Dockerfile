FROM ruby:3.0-alpine
LABEL maintainer "Tim Brust <github@timbrust.de>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk -U upgrade \
  && apk add --repository https://dl-cdn.alpinelinux.org/alpine/v3.16/main/ \
    nodejs \
  && apk add --no-cache \
    npm \
    yarn
