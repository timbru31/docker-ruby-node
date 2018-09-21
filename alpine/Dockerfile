FROM ruby:2.5-alpine3.7@sha256:5edfc2436e62512793a64394260f5a1310f1fc8bbfc51a2feafa9d7c62011a5d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
