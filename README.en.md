# libLuna

A lightweight GUI toolkit in pure Rust. The foundation of the Luna desktop — scene graph, text, input, themes, i18n and 77 widgets. No GTK, Qt or GObject.

> **Languages:** [Polski](README.pl.md) · [English](README.en.md) · [Deutsch](README.de.md)

## Part of the Luna project

This repository is part of the [LunaDesktop](https://github.com/LunaDesktop) organisation and the **Luna** project — a desktop written in Rust, without GTK, Qt or GObject.

## Building

```bash
git clone https://github.com/LunaDesktop/libLuna.git
cd libLuna
cargo build --workspace
```

Requirements: Linux, Rust 1.80+, Wayland (for windowed applications).

## Running

```bash
cargo test --workspace
```

## Documentation

- Project page: <https://luna.paganlinux.eu/>
- Developer docs: <https://luna.paganlinux.eu/en/docs/>
- Polish docs: <https://luna.paganlinux.eu/docs/>
- API index: <https://luna.paganlinux.eu/en/docs/api.html>

## License

The code is licensed under **MPL-2.0**. The full text is in [LICENSE](LICENSE).
