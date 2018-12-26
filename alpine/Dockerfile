FROM ruby:2.5-alpine3.8@sha256:80f85b2af09bf5986b222ed066746a57f804d86561bb18f41ced8f5ac64db663
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
