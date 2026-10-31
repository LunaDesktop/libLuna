# libLuna

Lekki toolkit GUI w czystym Rust. Fundament środowiska Luna — graf sceny, tekst, wejście, motywy, i18n i 77 widgetów. Bez GTK, Qt i GObject.

> **Języki:** [Polski](README.pl.md) · [English](README.en.md) · [Deutsch](README.de.md)

## Część projektu Luna

Repozytorium jest częścią organizacji [LunaDesktop](https://github.com/LunaDesktop) i projektu **Luna** — pulpitu pisanego w Rust, bez GTK, Qt i GObject.

## Budowanie

```bash
git clone https://github.com/LunaDesktop/libLuna.git
cd libLuna
cargo build --workspace
```

Wymagania: Linux, Rust 1.80+, Wayland (dla aplikacji okienkowych).

## Uruchomienie

```bash
cargo test --workspace
```

## Dokumentacja

- Strona projektu: <https://luna.paganlinux.eu/>
- Dokumentacja deweloperska: <https://luna.paganlinux.eu/docs/>
- Wersja angielska: <https://luna.paganlinux.eu/en/docs/>
- Indeks API: <https://luna.paganlinux.eu/en/docs/api.html>

## Licencja

Kod jest dostępny na licencji **MPL-2.0**. Pełny tekst znajduje się w pliku [LICENSE](LICENSE).
