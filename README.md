# ofxAddon

## Description

An addon template for openFrameworks.

## Features

-   An important feature.

## Getting Started

### Bootstrap

Every effort is made to keep the repository small. Thus sometimes third-party libraries need to be compiled and example data needs to be downloaded. The bootstrap script takes care of this.

-   From the `scripts/` directory ...
    -   `./bootstrap.sh`

### Generate Project Files

1.   Generate the example project files using the openFrameworks [Project Generator](http://openframeworks.cc/learning/01_basics/how_to_add_addon_to_project/).
2.   Open the Project Files in your Integrated Development Environment (IDE), or run `make && make run` from the example directory.

For more, see [docs/GETTING_STARTED.md](docs/GETTING_STARTED.md).

## Support

See [docs/SUPPORT.md](docs/SUPPORT.md).

## Documentation

API documentation can be found here.

## Requirements

-   A list of any requirements, additional addons, etc.

## Compatibility

### Supported Platforms

| Platform          | Build Status | Notes  |
|-------------------|--------------|--------|
| **osx**           |      ❓      | _None_ |
| **linux**         |      ❓      | _None_ |
| **Linux64**       |      ❓      | _None_ |
| **linuxarmv6l**   |      ❓      | _None_ |
| **msys2**         |      ❓      | _None_ |
| **vs**            |      ❓      | _None_ |
| **ios**           |      ❓      | _None_ |
| **tvos**          |      ❓      | _None_ |
| **emscripten**    |      ❓      | _None_ |
| **android**       |      ❓      | _None_ |

|      Status      | Symbol |
|------------------|--------|
| **Tested**       |   ✅   | 
| **Untested**     |   ⚠️   |
| **Incompatible** |   ❌   |
| **Unknown**      |   ❓   |


### Build Status

Linux, macOS [![Build Status](https://travis-ci.org/bakercp/ofxIO.svg?branch=master)](https://travis-ci.org/bakercp/ofxIO)

Visual Studio, MSYS2 [![Build status](https://ci.appveyor.com/api/projects/status/krr0ck8ffida8nsj/branch/master?svg=true)](https://ci.appveyor.com/project/bakercp/ofxio/branch/master)

### Branches

The `stable` branch of this repository is meant to be compatible with the openFrameworks [stable branch](https://github.com/openframeworks/openFrameworks/tree/stable), which corresponds to the latest official openFrameworks release.

The `master` branch of this repository is meant to be compatible with the openFrameworks [master branch](https://github.com/openframeworks/openFrameworks/tree/master). This is often the same as the `stable` branch.

The `develop` branch of this repository is used by developers to test new features. It is usually compatible with the openFrameworks [master branch](https://github.com/openframeworks/openFrameworks/tree/master), but is compatibility is not guaranteed. The `develop` branch should not be used for production.

Some past openFrameworks releases are supported via tagged versions and [releases](releases/), but only `stable` and `master` branches are actively supported.

## Versioning

This project uses [Semantic Versioning](http://semver.org/spec/v2.0.0.html), although strict adherence will only come into effect at version 1.0.0.

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)


## Licensing

See [LICENSE.md](LICENSE.md)
