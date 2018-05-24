FROM ruby:2.5-alpine3.7@sha256:83b450faffac8446818dc9e3f3da9cafb25becbdf732b77fc958e84859c2935d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  nodejs-npm \
  yarn
