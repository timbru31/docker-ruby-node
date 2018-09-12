FROM ruby:2.5-alpine3.7@sha256:cf33d4ea18d13ca736bd1d29fb72aa448fb411b4b8860872f97a4c8cf2302d87
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
