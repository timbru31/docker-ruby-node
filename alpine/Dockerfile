FROM ruby:2.6-alpine3.9@sha256:50458b6f1f162861a070a6b9c175a94c4148bae015d5c6eb56648daa12d8f702
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
