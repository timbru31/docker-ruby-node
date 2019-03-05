FROM ruby:2.6-alpine3.9@sha256:105b713f53ce2da93bc7b3727b7a779b3d19249f557346aba8b466a25785b66a
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
