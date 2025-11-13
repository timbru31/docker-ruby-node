# Ruby 3.2, 3.3, 3.4, 3.5 (RC) with Node.js 20 LTS, Node.js 22 LTS or Node.js 24 LTS Dockerfile

[![Docker Automated build](https://img.shields.io/docker/automated/timbru31/ruby-node.svg)](https://hub.docker.com/r/timbru31/ruby-node/)
[![buildx Status](https://github.com/timbru31/docker-ruby-node/workflows/buildx/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3Abuildx)
[![Lint Dockerfiles](https://github.com/timbru31/docker-ruby-node/workflows/Lint%20Dockerfiles/badge.svg)](https://github.com/timbru31/docker-ruby-node/actions?query=workflow%3A%22Lint+Dockerfiles%22)

A minimal Dockerfile based on Ruby (3.2, 3.3, 3.4 or 3.5 (RC)) Dockerfile (regular, slim or alpine) with Node.js 20 LTS (Iron), Node.js 22 LTS (Jod) or Node.js 24 LTS (Krypton) installed.

## What's included

- Ruby 3.2, 3.3, 3.4, 3.5 (RC)
- Node.js 20 LTS (Iron), Node.js 22 LTS (Jod) or Node.js 24 LTS (Krypton)
- bundled npm that comes with the respective Node.js version (latest for Node.js LTS on alpine, see [why](https://gitlab.alpinelinux.org/alpine/aports/-/commit/25b10bd1a93e12a7e49fee38b0a229281ae49fb7))
- yarn

### Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:

- linux/amd64
- linux/arm64
- linux/arm/v7 (not for Node.js >= 24)
- linux/arm/v6 (not for regular or slim)
- linux/386 (not for regular or slim)
- linux/ppc64le (not for regular or slim)
- linux/s390x (not for regular or slim)

---

Built by (c) Tim Brust and contributors. Released under the MIT license.
