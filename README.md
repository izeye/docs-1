[![Build Status](https://travis-ci.org/buildpacks/docs.svg?branch=master)](https://travis-ci.org/buildpacks/docs/branches)

# docs
Website for [Cloud Native Buildpacks](https://buildpacks.io)

## Development

##### Prerequisites

* [jq](https://stedolan.github.io/jq/)
    * macOS: `brew install jq`
    * Windows: `choco install jq`
* Make
    * macOS: `xcode-select --install`
    * Windows: `choco install make`

#### Serve

Serve docs at http://localhost:1313

```bash
make serve
```

#### Build

```bash
make build
```
