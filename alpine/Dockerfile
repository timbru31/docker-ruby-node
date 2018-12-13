FROM ruby:2.5-alpine3.8@sha256:80a8c9bcfe208ee3b2001aaa51700c9513e14bca408b18e0012008f05fe5ed5f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
