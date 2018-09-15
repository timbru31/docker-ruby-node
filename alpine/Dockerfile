FROM ruby:2.5-alpine3.7@sha256:567e836ff8f0a4cd46a1502790bc0ec48847774df208d82b87071d70bd90f8df
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
