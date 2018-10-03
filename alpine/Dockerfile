FROM ruby:2.5-alpine3.7@sha256:1ccadf8e7789d8b70b12b024ecb9de69eb8a5505b5f7c56652cd5f9511b6a289
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
