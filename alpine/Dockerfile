FROM ruby:2.5-alpine3.7@sha256:637559ee73feadf715873a3102494f7e1a180549728b6db154a85f6a51ca2aea
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
