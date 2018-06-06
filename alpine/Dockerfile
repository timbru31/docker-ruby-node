FROM ruby:2.5-alpine3.7@sha256:15e425d2b978927772ec0657050cd3052e2b5d444dc599794e145ad0b9b01cda
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  nodejs-npm \
  yarn
