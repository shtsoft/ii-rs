# iiservice

[![crates.io][crates-badge]][crates-url]
[![GPL licensed][license-badge]][license-url]

[crates-badge]: https://img.shields.io/crates/v/iiservice.svg
[crates-url]: https://crates.io/crates/iiservice
[license-badge]: https://img.shields.io/badge/license-GPL-blue.svg
[license-url]: ./Cargo.toml

A **simple** IRC client as a service powered by [iilib](https://github.com/shtsoft/ii-rs/iilib), effectively constituting a reimplementation of [ii](https://tools.suckless.org/ii) as a service in **Rust**.

- simplicity:
  * ...
- Rust:
  * safety:
    + thoroughly testet
    + memory-safety: no `unsafe`-code

### Installation

You can install iiservice with `cargo` by running:

```console
user@host:~$ cargo install iiservice
```

### Usage

To get a usage description just run the app without arguments:

```console
user@host:~$ iiservice
```

## Contributing

If you want to contribute: [CONTRIBUTING](../CONTRIBUTING.md).

### Security

For security-related issues see: [SECURITY](../SECURITY.md).
