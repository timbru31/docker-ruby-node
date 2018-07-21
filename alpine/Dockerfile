FROM ruby:2.5-alpine3.7@sha256:8cb2b724f120e452875556e483e6995feb468f86a8b6158014116fbc8b09e7f6
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
