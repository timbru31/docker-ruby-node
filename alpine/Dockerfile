FROM ruby:2.5-alpine3.7@sha256:7c8a3d6cb7bbbc360acce07f16f579eb4832adc2fda1da6d81f2abe7254a0f5e
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
