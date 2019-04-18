FROM ruby:2.6-alpine@sha256:114903cc15cb8b2bdcd0491506146d546800ee1a790c6ac093cc0aca3a45dbb6
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
