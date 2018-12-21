FROM ruby:2.5-alpine3.8@sha256:ebf481f4244f9bf2e32f09d3010563fb087a1505e40627acf0eb0e60713bacdc
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
  nodejs \
  nodejs-npm \
  yarn
