FROM ruby:3.2-alpine
LABEL maintainer="Tim Prüssing <github@timbrust.de>"

ARG REFRESHED_AT
ENV REFRESHED_AT=$REFRESHED_AT

RUN echo @3.24 https://dl-cdn.alpinelinux.org/alpine/v3.24/community >> /etc/apk/repositories \
  && echo @3.24 https://dl-cdn.alpinelinux.org/alpine/v3.24/main >> /etc/apk/repositories \
  && apk -U upgrade \
  && apk add --no-cache \
   nodejs-current@3.24 \
    npm@3.24 \
    yarn@3.24
