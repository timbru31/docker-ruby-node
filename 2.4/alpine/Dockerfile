FROM ruby:2.4-alpine@sha256:c393a72a9571ae25db44f0ddbd0617713c54ff43c0ce0946479ce09cb09b3441
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
