FROM ruby:2.6-alpine@sha256:2749716577d81ef71bc487dfd35962bb067ca11a1b9d6d6d81f8ff7cc3e03f60
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
