# Ruby 2.5, 2.6, 2.7 or 3.0 (RC) with Node.js 14 LTS Dockerfile

[![Docker Automated build](https://img.shields.io/docker/automated/timbru31/ruby-node.svg)](https://hub.docker.com/r/timbru31/ruby-node/)
[![buildx Status](https://github.com/timbru31/docker-ruby-node/workflows/buildx/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3Abuildx)
[![Lint Dockerfiles](https://github.com/timbru31/docker-ruby-node/workflows/Lint%20Dockerfiles/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3A%22Lint+Dockerfiles%22)

A minimal Dockerfile based on Ruby (2.5, 2.6, 2.7 or 3.0 (RC)) Dockerfile (regular, slim or alpine) with Node.js 14 LTS (Fermium) installed.

## What's included

- Ruby 2.5, 2.6, 2.7 or 3.0 (RC)
- Node.js 14
- npm 6
- yarn

### Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:

- linux/amd64
- linux/arm64
- linux/arm/v7 (not for 2.7-alpine)
- linux/arm/v6 (not for regular or slim, not for 2.7-alpine)
- linux/386 (not for regular or slim)
- linux/ppc64le (not for regular or slim)
- linux/s390x (not for regular or slim, not for >=2.7-alpine)

---

Built by (c) Tim Brust and contributors. Released under the MIT license.
