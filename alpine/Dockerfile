FROM ruby:2.5-alpine3.7@sha256:8855b2269faeb03167ec993042b5e0bafef415d7581aae97321637c1b368a51f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
