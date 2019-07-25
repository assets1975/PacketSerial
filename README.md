# PacketSerial

> An Arduino Library that facilitates packet-based serial communication using COBS or SLIP encoding.

- **CI**: [![Build Status](https://travis-ci.org/bakercp/PacketSerial.svg?branch=master)](https://travis-ci.org/bakercp/PacketSerial)

- **Documentation**: [https://bakercp.github.com/PacketSerial](https://bakercp.github.com/PacketSerial)
- **Repository**: [https://github.com/bakercp/PacketSerial](https://github.com/bakercp/PacketSerial)  
- **License**: [MIT](LICENSE.md)

- **Code of Conduct**: [Code of Conduct](docs/CODE_OF_CONDUCT.md).
- **Changelog**: [Changelog](docs/CHANGELOG.md).
- **Examples**: [Examples](examples).

## Features

_PacketSerial_ is an small, efficient, library that allows [Arduinos](http://www.arduino.cc/) to send and receive serial data packets (with COBS, SLIP or a user-defined encoding) that include bytes of any value (0 - 255). A _packet_ is simply an array of bytes.

## Why do I need this?

Read the [background introduction](docs/BACKGROUND.md) page.

## How can I contribute?

Read the [contributing](docs/CONTRIBUTING.md) page.

## Compatibility

### Other Software

- openFrameworks (C/C++ on macOS, Windows, Linux, Android, etc).
  - [ofxSerial](https://github.com/bakercp/ofxSerial) addon.
    - See the `ofx::IO::PacketSerial` object which is directly compatible with this library.

- Python
  - [PySerial](https://pythonhosted.org/pyserial/index.html)
    - [COBS](https://pythonhosted.org/cobs/) (see [this discussion](https://github.com/bakercp/PacketSerial/issues/10) for more).
    - [SLIP](https://pypi.python.org/pypi/sliplib/0.0.1)

_Any library that correctly implements a COBS or SLIP encoding scheme should be compatible._

### Hardware

The code is tested with a number of Arduino Platforms.


