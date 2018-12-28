FROM ruby:2.6-alpine3.8@sha256:2b4d28f53aa285e5566963c5592a365bfbdd7b38a8f53550ca1ef5fe00b10fd4
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
