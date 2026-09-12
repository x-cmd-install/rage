# rage

[中文版本](./README.cn.md)

A simple, secure and modern file encryption tool (and Rust library) with small explicit keys, no config options, and UNIX-style composability.

![rage](https://repo.x-cmd.io/rage.svg)

## Install

```sh
x install rage
```

## Code insight

Total: **17,143** lines of code across **139** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Rust | 12,768 | 582 | 1,720 | 58 |
| FreeMarker | 2,338 | 0 | 947 | 14 |
| Toml | 2,024 | 95 | 394 | 65 |
| Pan | 10 | 3 | 7 | 1 |
| Json | 3 | 0 | 0 | 1 |

## OpenSSF Scorecard

Overall score: **4.7 / 10**

Lowest-scoring checks:

- **Code-Review** (1/10) — Found 1/8 approved changesets -- score normalized to 1
- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## Source

- **Upstream**: <https://github.com/str4d/rage>
- **Homepage**: <https://age-encryption.org/v1>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.12.1` (2026-07-14)
- **Last commit**: 2026-07-14
- **Assets in release**: 12

## Popularity

- **Stars**: 3,653 · **Forks**: 160 · **Open issues**: 228 · **Contributors**: 37

## Totals (cumulative)

- **Releases**: 26 · **Merged PRs**: 328 · **Open PRs**: 19 · **Closed issues**: 180 · **Open issues**: 48 · **Commits**: 1533

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 0 | 1 | 0 | 2 | 0 |
| last60d | 2026-07-14 | 2 | 0 | 4 | 0 | 4 | 0 |
| 90d | 2026-06-14 | 4 | 7 | 5 | 2 | 5 | 19 |
| last180d | 2026-03-16 | 5 | 13 | 6 | 8 | 7 | 40 |
| 360d | 2025-09-17 | 5 | 22 | 8 | 10 | 12 | 74 |
| last720d | 2024-09-22 | 9 | 30 | 14 | 23 | 24 | 147 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [rage-musl_0.12.1-1_amd64.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage-musl_0.12.1-1_amd64.deb) | 1.4 MiB | `runtime/deb/amd64` |
| [rage-musl_0.12.1-1_arm64.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage-musl_0.12.1-1_arm64.deb) | 1.2 MiB | `runtime/deb/arm64` |
| [rage-musl_0.12.1-1_armhf.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage-musl_0.12.1-1_armhf.deb) | 1.2 MiB | `runtime/deb/armhf` |
| [rage-v0.12.1-arm64-darwin.tar.gz](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-arm64-darwin.tar.gz) | 2.7 MiB | `native/darwin/arm64` |
| [rage-v0.12.1-arm64-linux.tar.gz](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-arm64-linux.tar.gz) | 2.9 MiB | `native/linux/arm64` |
| [rage-v0.12.1-armv7-linux.tar.gz](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-armv7-linux.tar.gz) | 2.8 MiB | `native/linux/arm` |
| [rage-v0.12.1-x86_64-darwin.tar.gz](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-x86_64-darwin.tar.gz) | 2.8 MiB | `native/darwin/x64` |
| [rage-v0.12.1-x86_64-linux.tar.gz](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-x86_64-linux.tar.gz) | 4.9 MiB | `native/linux/x64` |
| [rage-v0.12.1-x86_64-windows.zip](https://github.com/str4d/rage/releases/download/v0.12.1/rage-v0.12.1-x86_64-windows.zip) | 2.4 MiB | `native/win/x64` |
| [rage_0.12.1-1_amd64.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage_0.12.1-1_amd64.deb) | 1.8 MiB | `runtime/deb/amd64` |
| [rage_0.12.1-1_arm64.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage_0.12.1-1_arm64.deb) | 1.2 MiB | `runtime/deb/arm64` |
| [rage_0.12.1-1_armhf.deb](https://github.com/str4d/rage/releases/download/v0.12.1/rage_0.12.1-1_armhf.deb) | 1.2 MiB | `runtime/deb/armhf` |

## Improve this data

Install metadata for rage lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `rage` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/rage.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T04:39:20Z._
