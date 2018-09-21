FROM ruby:2.5-alpine3.7@sha256:c94ad48624fd60c5f7311f5ac377fc9455538fdb113b1d43f3d42b9e0842811f
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
