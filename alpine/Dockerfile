FROM ruby:2.5-alpine3.7@sha256:9821849f0c9c9c782a2e2c77fb5142a0eff713977ab57e26d17e5a34a2c12239
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
