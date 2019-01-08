FROM ruby:2.6-alpine3.8@sha256:3dadc14b9a41f5908a138dbf8a3bec788ec08e94fd084b7b7766c76ad2a50178
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
