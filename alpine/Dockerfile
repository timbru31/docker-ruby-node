FROM ruby:2.5-alpine3.7@sha256:32b03df795a62cf117aec7ced5c02ae193d91cec4b9891d250f5b459c662aaf4
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
