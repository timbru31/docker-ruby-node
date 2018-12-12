FROM ruby:2.5-alpine3.8@sha256:aed0225e84b0c480bc1290cbcce22f590dd15ce86bfd921cfd2fdea0bafd9200
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
