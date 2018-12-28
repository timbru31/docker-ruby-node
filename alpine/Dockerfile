FROM ruby:2.6-alpine3.8@sha256:c7b58e0d7fc40f28d020a4914861a7a71f1b296aa0cfdefff644a89167c929ab
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
