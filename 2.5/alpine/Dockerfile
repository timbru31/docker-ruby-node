FROM ruby:2.5-alpine@sha256:a047524108d6d8fa03a8099b972d96e9a9e32103a23f335874c87d68808ed890
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
RUN echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
  echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/main >> /etc/apk/repositories && \
  apk add --no-cache \
  libstdc++@edge \
  libuv@edge \
  nodejs@edge \
  nodejs-npm@edge \
  yarn@edge
