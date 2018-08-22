FROM ruby:2.5-alpine3.7@sha256:c572b9ab6d2458a83544964829d0f13c181a14a10cf23d9f0db5881b52ee4275
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
