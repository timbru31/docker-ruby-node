FROM ruby:2.4-alpine@sha256:f041cf6d3d794562e613fd80baf82737b8d86fc49f47b6db44f2ce7f2d0f7cc9
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
