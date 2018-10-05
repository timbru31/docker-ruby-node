FROM ruby:2.5-alpine3.7@sha256:c88ee0877e44f95dcf7cfaace673e1174c9e9e1e2fb32b1ce0f97979568a6fd7
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
