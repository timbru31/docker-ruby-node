FROM ruby:2.6-alpine3.9@sha256:64fc3e29cf8e32d34721aa1e35795d1702ade98f4b827400ff4f20c52b401d43
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
