FROM ruby:2.5-alpine3.7@sha256:c5e2ec42210996faed772ef6acdfda768d6d2fccb45309ffe665ffacef50bf99
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
