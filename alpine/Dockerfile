FROM ruby:2.5-alpine3.7@sha256:13a1262f1bf9ca663cb230ada8c7323d98e14edaeb63874c05f85e3316831ad7
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
