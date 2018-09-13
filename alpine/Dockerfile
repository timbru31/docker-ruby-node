FROM ruby:2.5-alpine3.7@sha256:c8e826aba2503c987b57a17cf5382c7f01ab51e29f9924afadda02755bbf1b07
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
