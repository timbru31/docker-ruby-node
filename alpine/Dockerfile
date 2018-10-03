FROM ruby:2.5-alpine3.7@sha256:06ae122eb1e2b65cf253d4a0e9037a6eb1236ce476dbebc898dc1e81a8227d0c
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
