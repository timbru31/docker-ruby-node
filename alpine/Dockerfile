FROM ruby:2.5-alpine3.7@sha256:20503940e1eda342f059c1bbdf55e87a2a2338a4b2b6cd0a7b183e712615e65f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
