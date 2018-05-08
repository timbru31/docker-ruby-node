FROM ruby:2.5-alpine3.7@sha256:e46f839001cb722b426f264361ba8743556960bc7088735dd6eb5173ab9e1056
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  nodejs-npm \
  yarn
