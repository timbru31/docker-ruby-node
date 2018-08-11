FROM ruby:2.5-alpine3.7@sha256:bb31e1350f0098b9b715beb32caa594d88f879fc042233e52819358b061e2abc
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
