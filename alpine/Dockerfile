FROM ruby:2.5-alpine3.7@sha256:75f6c465aad5567085564e7dad66a3b6beaf8bda275f13b131c05940c17ec5bd
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN sed -i -e 's/v3\.7/edge/g' /etc/apk/repositories
RUN apk add --no-cache \
  nodejs \
  npm \
  yarn
