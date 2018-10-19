FROM ruby:2.5-alpine3.7@sha256:5f669f51f127d16dde219b6831232677b3bd98408243f512928945d653a6d9ed
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
