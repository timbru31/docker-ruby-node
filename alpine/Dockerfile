FROM ruby:2.5-alpine3.7@sha256:6147d4eec99f1b4734371003f0d1e4e1cca01531572acb7a807bad6cf44d09f4
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
