FROM ruby:2.5-alpine3.7@sha256:f5392e6c30b91031f02545536574ffa76115fe0fda1f66d4c23057f21ad02b43
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
