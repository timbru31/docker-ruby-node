FROM ruby:2.6-slim@sha256:9f83f32c8b98a6e607703f540ef5c16d3d08dcfc07a588d357cf480417f92c79
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

# hadolint ignore=DL3009
RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
    curl \
    gnupg2

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
RUN echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
    nodejs \
    yarn \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*
