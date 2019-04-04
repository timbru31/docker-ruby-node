FROM ruby:2.4-alpine@sha256:ccaadab949f329b5b4adda6530ab3d4f07a9056bd272b04118f1298283ed1c9e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
