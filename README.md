# Package Name API

The [Project API](https://apibr.com) client wrapper written in Rust.

[![Maintainability](https://api.codeclimate.com/v1/badges/96c5f836e1ece8027022/maintainability)](https://codeclimate.com/github/guibranco/calendarific-sdk-rs/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/96c5f836e1ece8027022/test_coverage)](https://codeclimate.com/github/guibranco/calendarific-sdk-rs/test_coverage)

| Service      | Status |
| -------      | :----: |
| AppveyorCI   | [![Build status](https://ci.appveyor.com/api/projects/status/AppVeyorId?svg=true)](https://ci.appveyor.com/project/guibranco/apiclient-boilerplate-rust/branch/master) |
| crates.io    | [![crates.io](https://img.shields.io/crates/v/package-name-rs.svg)](https://crates.io/crates/package-name-rs) |

Pure Rust bindings to the [Project API](https://apibr.com).

## Dependencies and support

**package-name-rs** is intended to work on all tier 1 supported Rust systems:

- MacOSX
- Linux
- Windows

## Minimum Compiler Version

Due to the use of certain features package-name-rs requires `rustc` version 1.18 or
higher.

## Getting Started

Add the following to your `Cargo.toml`

```toml
[dependencies]
package_name_rs = "0.0.1"
serde_json = "1.0"
```

Then in your `lib.rs` or `main.rs` file add:
```rust
extern crate package_name;

let client = PackageNameAPIClient::new();

```

## License

Licensed under

- MIT license ([LICENSE](https://github.com/guibranco/apiclient-boilerplate-rust/blob/master/LICENSE) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))
