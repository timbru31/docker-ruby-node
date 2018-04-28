FROM ruby:2.5-slim@sha256:0098669eea13ecece4b1ff6104abb76ab5228912219cc95715ef6f9f838ebd94
LABEL maintainer "Tim Brust <tim.brust@sinnerschrader.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apt-get update -qqy && apt-get -qqyy install \
    curl \
    gnupg2

RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -
RUN curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
RUN echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
RUN apt-get update -qqy && apt-get -qqyy install \
    nodejs \
    yarn \
  && rm -rf /var/lib/apt/lists/*
