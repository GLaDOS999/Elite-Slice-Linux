# Elite Slice Linux

Open-source Linux support for the HP Elite Slice G2 collaboration hardware.

## Overview

This project aims to bring full Linux support to the proprietary HP Elite Slice G2 collaboration hardware, including:

- 🎤 Collaboration Cover
- 🔊 Speaker Module (CX20926)
- 📹 Video Ingest Modules
- 💡 LEDs and button controls

## Current Progress

- ✅ Device discovery
- ✅ Raw HID communication with the Collaboration Cover
- 🔄 Reverse engineering the HID protocol
- ⏳ Video Ingest initialization

## Goals

- Support Linux Mint
- Support Ubuntu
- Support Debian
- Expand to other Linux distributions

## Building

```bash
cargo build
```

## Running

```bash
cargo run
```

## License

MIT (planned)

---

**Project status:** 🚧 Early development


## Why?

The HP Elite Slice G2 includes several collaboration devices that only function fully under Windows with proprietary HP software.

The goal of this project is to provide an open-source implementation that restores that functionality on Linux, beginning with Linux Mint and expanding to other distributions.
