FROM ruby:2.5-alpine3.7@sha256:67f8af234be9213a5edf82d2bf8d420e2ab2f7c6167e7e68d88054da87612fcb
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
