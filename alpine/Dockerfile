FROM ruby:2.5-alpine3.8@sha256:1780a51835cad01073b306d78ec55fe095ad29b66105a9efbee48921f5a71800
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
