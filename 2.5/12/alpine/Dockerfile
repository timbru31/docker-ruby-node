FROM ruby:2.5-alpine
LABEL maintainer "Tim Brust <github@timbrust.de>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository https://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  "nodejs<14" \
  "nodejs-npm<14" \
  yarn
