# @pyke/opus [![Build](https://github.com/pykeio/opus/workflows/Build/badge.svg)](https://github.com/pykeio/opus/actions?query=workflow%3ABuild) [![Prebuild](https://github.com/pykeio/opus/workflows/Prebuild/badge.svg)](https://github.com/pykeio/opus/actions?query=workflow%3APrebuild)

> Native bindings to libopus v1.4

Forked from [`discordjs/opus`](https://github.com/discordjs/opus)

## Usage

```js
const { OpusEncoder } = require('@pyke/opus');

// Create the encoder.
// Specify 48kHz sampling rate and 2 channel size.
const encoder = new OpusEncoder(48000, 2);

// Encode and decode.
const encoded = encoder.encode(buffer);
const decoded = encoder.decode(encoded);
```

## Platform support

⚠ Node.js 14.12.0 or newer is required.

- Linux x64 & ia32
- Linux arm (RPi 1 & 2)
- Linux arm64 (RPi 3)
- macOS x64
- macOS arm64
- Windows x64
