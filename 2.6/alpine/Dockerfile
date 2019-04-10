FROM ruby:2.6-alpine@sha256:7af6a75ccc7ad96730cb500a2b0144c6226e4c9d9e64254a5e0066516da77413
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
