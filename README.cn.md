# rage

[English version](./README.md)

A simple, secure and modern file encryption tool (and Rust library) with small explicit keys, no config options, and UNIX-style composability.

![rage](https://repo.x-cmd.io/rage.svg?lang=zh)

## 安装

```sh
x install rage
```

## 代码洞察

合计: **17,143** 行代码（覆盖前 5 种语言、共 **139** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Rust | 12,768 | 582 | 1,720 | 58 |
| FreeMarker | 2,338 | 0 | 947 | 14 |
| Toml | 2,024 | 95 | 394 | 65 |
| Pan | 10 | 3 | 7 | 1 |
| Json | 3 | 0 | 0 | 1 |

## OpenSSF Scorecard 评分

总评分: **4.7 / 10**

评分最低的几项:

- **Code-Review** (1/10) — Found 1/8 approved changesets -- score normalized to 1
- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## 源代码

- **上游仓库**: <https://github.com/str4d/rage>
- **官网**: <https://age-encryption.org/v1>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.12.1` (2026-07-14)
- **最近提交**: 2026-07-14
- **Release 含资产**: 12 个

## 流行度

- **Star**: 3,653 · **Fork**: 160 · **开放 issue**: 228 · **贡献者**: 37

## 累计统计

- **发布数**: 26 · **已合并 PR**: 328 · **开放 PR**: 19 · **已关闭 issue**: 180 · **开放 issue**: 48 · **提交数**: 1533

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 0 | 1 | 0 | 2 | 0 |
| last60d | 2026-07-14 | 2 | 0 | 4 | 0 | 4 | 0 |
| 90d | 2026-06-14 | 4 | 7 | 5 | 2 | 5 | 19 |
| last180d | 2026-03-16 | 5 | 13 | 6 | 8 | 7 | 40 |
| 360d | 2025-09-17 | 5 | 22 | 8 | 10 | 12 | 74 |
| last720d | 2024-09-22 | 9 | 30 | 14 | 23 | 24 | 147 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 改进这些数据

rage 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `rage` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/rage.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T04:39:21Z._
