FROM ruby:2.4-alpine@sha256:413b178de0af37f4282f126ca408c064923359f91a3a10a2bc905d511cea2b53
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
