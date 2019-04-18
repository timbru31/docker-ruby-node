FROM ruby:2.6-alpine@sha256:fe746a766d2614144c9d97d3b6f9d1efe87e56c80109c837d1510289189ab687
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
