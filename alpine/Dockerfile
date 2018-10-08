FROM ruby:2.5-alpine3.7@sha256:5c2c66e70bfbb3f08d67e1335f555ccf69f6e3bcbf418a7b2fe3abf31d330ff2
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
