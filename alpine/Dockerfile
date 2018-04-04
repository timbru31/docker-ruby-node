FROM ruby:2.5-alpine3.7@sha256:256e2b58c4e4e12850021c45af2b28d0dd319bdfa3ea48b07d6584b34d64bc09
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  nodejs-npm \
  yarn
