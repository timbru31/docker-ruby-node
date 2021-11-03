# Ruby 2.6, 2.7 or 3.0 with Node.js 12 or 14 LTS Dockerfile

[![Docker Automated build](https://img.shields.io/docker/automated/timbru31/ruby-node.svg)](https://hub.docker.com/r/timbru31/ruby-node/)
[![buildx Status](https://github.com/timbru31/docker-ruby-node/workflows/buildx/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3Abuildx)
[![Lint Dockerfiles](https://github.com/timbru31/docker-ruby-node/workflows/Lint%20Dockerfiles/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3A%22Lint+Dockerfiles%22)

A minimal Dockerfile based on Ruby (2.6, 2.7 or 3.0) Dockerfile (regular, slim or alpine) with Node.js 12 LTS (Erbium) or Node.js 14 LTS (Fermium) installed. Please note, that the Node.js 12 LTS (Erbium) builds for alpine might be outdated due to Alpine's update policy.

## What's included

- Ruby 2.6, 2.7 or 3.0
- Node.js 12 (Erbium) LTS or 14 LTS (Fermium)
- npm 6 (latest for Node.js LTS v14 on alpine, see [why](https://gitlab.alpinelinux.org/alpine/aports/-/commit/25b10bd1a93e12a7e49fee38b0a229281ae49fb7))
- yarn

### Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:

- linux/amd64
- linux/arm64
- linux/arm/v7
- linux/arm/v6 (not for regular or slim)
- linux/386 (not for regular or slim)
- linux/ppc64le (not for regular or slim)
- linux/s390x (not for regular or slim)

---

Built by (c) Tim Brust and contributors. Released under the MIT license.
