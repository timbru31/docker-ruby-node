FROM ruby:2.7-slim
LABEL maintainer "Tim Brust <github@timbrust.de>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

# hadolint ignore=DL3009
RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
    curl \
    gnupg2

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
    nodejs \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

RUN npm install -g yarn@1.22.4
