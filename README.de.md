# libLuna

Ein schlankes GUI-Toolkit in reinem Rust. Die Grundlage des Luna-Desktops – Szenengraph, Text, Eingabe, Themes, i18n und 77 Widgets. Ohne GTK, Qt oder GObject.

> **Sprachen:** [Polski](README.pl.md) · [English](README.en.md) · [Deutsch](README.de.md)

## Teil des Luna-Projekts

Dieses Repository ist Teil der Organisation [LunaDesktop](https://github.com/LunaDesktop) und des **Luna**-Projekts — ein Desktop in Rust, ohne GTK, Qt oder GObject.

## Bauen

```bash
git clone https://github.com/LunaDesktop/libLuna.git
cd libLuna
cargo build --workspace
```

Anforderungen: Linux, Rust 1.80+, Wayland (für Fensteranwendungen).

## Starten

```bash
cargo test --workspace
```

## Dokumentation

- Projektseite: <https://luna.paganlinux.eu/>
- Entwicklerdokumentation: <https://luna.paganlinux.eu/en/docs/>
- Polnische Dokumentation: <https://luna.paganlinux.eu/docs/>
- API-Index: <https://luna.paganlinux.eu/en/docs/api.html>

## Lizenz

Der Code steht unter der Lizenz **GPL-3.0-or-later**. Der vollständige Text liegt in [LICENSE](LICENSE).
