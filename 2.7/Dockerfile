FROM ruby:2.7-rc@sha256:e02319ccccedfbae863cb884e93cb44f046274d28ae4e77d4fd8a51a966b853d
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

ENV LANG C.UTF-8
SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
RUN echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
    nodejs \
    yarn \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*
