FROM ruby:2.5-alpine3.7@sha256:cbc198ea48974b60118d8cab634f87bf509a95ae9735db9973cdb645020ea7c6
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
