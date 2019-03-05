FROM ruby:2.6-alpine3.8@sha256:aa41a77a43c019ee700dc8895f48465420f9a0636510956ccaca0216adc05dd0
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
