# Ruby 2.5, 2.6 or 2.7 with Node.js 12 LTS Dockerfile

[![Docker Automated build](https://img.shields.io/docker/automated/timbru31/ruby-node.svg)](https://hub.docker.com/r/timbru31/ruby-node/)
[![Docker Build Status](https://img.shields.io/docker/build/timbru31/ruby-node.svg)](https://hub.docker.com/r/timbru31/ruby-node/)
[![Build Status](https://travis-ci.org/timbru31/docker-ruby-node.svg?branch=master)](https://travis-ci.org/timbru31/docker-ruby-node)

A minimal Dockerfile based on Ruby (2.5, 2.6 or 2.7) Dockerfile (regular, slim or alpine) with Node.js 12 LTS (Erbium) installed.

## What's included

- Ruby 2.5, 2.6 or 2.7
- Node.js 12
- npm 6
- yarn

## Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:
- linux/amd64
- linux/arm64
- linux/arm/v7 (not for 2.7-alpine)
- linux/arm/v6 (not for 2.7-alpine)
- linux/386 (not for regular or slim)
- linux/ppc64le (not for regular or slim)
- linux/s390x (not for regular or slim, not for 2.7-alpine)

---

Built by (c) Tim Brust and contributors. Released under the MIT license.
