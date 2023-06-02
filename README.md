# ei-node-build

ei-node-build provides [Custom Build Definitions](https://github.com/nodenv/node-build#custom-build-definitions) for Node.js 18+ binaries built on Amazon Linux2.

The Node.js 18+ pre-built binaries provided at nodejs.org are built on Red Hat Enterprise Linux (RHEL) 8 and are compatible with Linux distributions based on glibc 2.28 or later.
So those binaries cannot be run on glibc 2.26 such as Amazon Linux2.
This repository provides binaries for Node.js 18 or higher built on Amazon Linux2.

## Installation

```sh
$ mkdir -p "$(nodenv root)"/plugins
$ git clone https://github.com/elastic-infra/ei-node-build.git "$(nodenv root)"/plugins/ei-node-build
```

### Upgrading

```sh
$ git -C "$(nodenv root)"/plugins/ei-node-build pull
```

## Usage

### Basic Usage

```sh
$ nodenv install 18.0.0 # installs Node 18.0.0 to ~/.nodenv/versions
```
