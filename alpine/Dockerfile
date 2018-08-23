FROM ruby:2.5-alpine3.7@sha256:626e1f1daabe6bb3965b20479ee093da37757370469f8ebd9672fb9664651734
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
