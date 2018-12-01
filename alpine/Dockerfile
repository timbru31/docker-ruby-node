FROM ruby:2.5-alpine3.8@sha256:f0d03c0e907929b8d7172ebe2bfa7e544db7ac61a3d837097246e8d8925bdb65
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
