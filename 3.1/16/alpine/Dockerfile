FROM ruby:3.1-alpine
LABEL maintainer "Tim Brust <github@timbrust.de>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk del gmp-dev libstdc++ \
  && apk -U upgrade \
  && apk add --repository https://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache \
    gmp-dev \
    libstdc++ \
    nodejs \
    npm \
    yarn
