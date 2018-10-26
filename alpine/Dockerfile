FROM ruby:2.5-alpine3.7@sha256:514c54ed11d43c7eec6d54a6b9dfd1e2f2ab544c2ddc79dc45c982dc77c28fb1
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
