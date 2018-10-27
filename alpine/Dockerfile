FROM ruby:2.5-alpine3.7@sha256:3247e0e311b7d0d3f3fab9c29b50a962d4d981bc19e8654b256e8351e83c95db
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
