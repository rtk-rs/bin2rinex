BIN2RINEX
=========

[![Rust](https://github.com/rtk-rs/bin2rinex/actions/workflows/rust.yml/badge.svg)](https://github.com/rtk-rs/rnx2crx/actions/workflows/rust.yml)
[![Rust](https://github.com/rtk-rs/bin2rinex/actions/workflows/daily.yml/badge.svg)](https://github.com/rtk-rs/rnx2crx/actions/workflows/daily.yml)
[![crates.io](https://img.shields.io/crates/v/bin2rinex.svg)](https://crates.io/crates/bin2rinex)

[![License](https://img.shields.io/badge/license-MPL_2.0-orange?style=for-the-badge&logo=mozilla)](https://github.com/rtk-rs/bin2rinex/blob/main/LICENSE)

`bin2rinex` is a small command line utility to deserialize a BINEX stream.
This is more than a deserialization tool, it is a true RINEX (readable BINEX) collection,
capable of gathering each BINEX frame into standardized RINEX.

BINEX is the only open-source protocol to describe GNSS navigation frames from a GNSS receiver.
It is the binary ""equivalent"" of the RINEX format. Read the following pages for more information about:

- [the BINEX streaming format](https://github.com/georust/rinex/tree/main/binex)
- [the RINEX format](https://github.com/georust/rinex/tree/main/binex)

:warning: this tool is work in progress

## Licensing

This application is part of the [RTK-rs framework](https://github.com/rtk-rs) which
is delivered under the [Mozilla V2 Public](https://www.mozilla.org/en-US/MPL/2.0) license.
