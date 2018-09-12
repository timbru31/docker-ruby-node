FROM ruby:2.5-alpine3.7@sha256:f45aad41c67d05af7b08456664e1eea46e135229df1cd2bdfe9006e87a68f9ce
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
