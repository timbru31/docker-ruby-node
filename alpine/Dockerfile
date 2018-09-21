FROM ruby:2.5-alpine3.7@sha256:17363a4d33e26725afcd96599da8b37931542fecc7ddc1074f685414e7f7e0b2
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
