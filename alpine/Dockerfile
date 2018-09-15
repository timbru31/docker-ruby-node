FROM ruby:2.5-alpine3.7@sha256:f0e78baf2379e4ab63c097c666cd0a2b2e4b539bd1e9cf44689cc3cc37bf0324
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
