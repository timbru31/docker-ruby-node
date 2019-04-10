FROM ruby:2.6-alpine@sha256:704b3369eb921a8b42239fbfb6c3ea443a72ed5e483be0eb8b97324cca6e4e2b
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
