FROM ruby:2.6-alpine3.8@sha256:2b46391477fd416db5b6a685b1a80586c450ae7191c25f744083c0d37eb6700e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
