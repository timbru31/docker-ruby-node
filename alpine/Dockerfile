FROM ruby:2.5-alpine3.7@sha256:895fe4e1e161860a9b1241c9d87e752fd5a84e1d877a96f447a62a963a3050bc
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
