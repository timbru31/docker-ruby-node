FROM ruby:2.5-alpine3.7@sha256:830080e883e3a307e830010b09756627ba49a2cb0cb69bd20e396afd6b092eaa
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
