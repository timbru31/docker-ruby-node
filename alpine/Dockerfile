FROM ruby:2.6-alpine3.8@sha256:0f309d96a24fdd76b32d80de98d56f8457e61462d97a131708dab4f8e1edc664
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
