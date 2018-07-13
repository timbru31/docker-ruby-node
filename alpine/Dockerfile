FROM ruby:2.5-alpine3.7@sha256:f30c176a86634baac74a17189dc671b7212b5b47df006042a6a982c9f476cb53
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
