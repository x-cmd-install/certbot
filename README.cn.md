# certbot

[English version](./README.md)

Certbot is EFF's tool to obtain certs from Let's Encrypt and (optionally) auto-enable HTTPS on your server.  It can also act as a client for any other CA that uses the ACME protocol.

![certbot](https://repo.x-cmd.io/certbot.svg?lang=zh)

## 安装

```sh
x install certbot
```

## 源代码

- **上游仓库**: <https://github.com/certbot/certbot>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v5.8.0` (2026-09-01)
- **最近提交**: 2026-09-09
- **Release 含资产**: 19 个

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [acme-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/acme-5.8.0.tar.gz) | 89.0 KiB | `native/unknown` |
| [certbot-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot-5.8.0.tar.gz) | 691.9 KiB | `native/unknown` |
| [certbot_apache-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_apache-5.8.0.tar.gz) | 5.9 KiB | `native/unknown` |
| [certbot_dns_cloudflare-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_cloudflare-5.8.0.tar.gz) | 17.6 KiB | `native/unknown` |
| [certbot_dns_digitalocean-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_digitalocean-5.8.0.tar.gz) | 14.2 KiB | `native/unknown` |
| [certbot_dns_dnsimple-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_dnsimple-5.8.0.tar.gz) | 12.0 KiB | `native/unknown` |
| [certbot_dns_dnsmadeeasy-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_dnsmadeeasy-5.8.0.tar.gz) | 12.2 KiB | `native/unknown` |
| [certbot_dns_gehirn-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_gehirn-5.8.0.tar.gz) | 12.1 KiB | `native/unknown` |
| [certbot_dns_google-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_google-5.8.0.tar.gz) | 24.6 KiB | `native/unknown` |
| [certbot_dns_linode-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_linode-5.8.0.tar.gz) | 12.3 KiB | `native/unknown` |
| [certbot_dns_luadns-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_luadns-5.8.0.tar.gz) | 12.0 KiB | `native/unknown` |
| [certbot_dns_nsone-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_nsone-5.8.0.tar.gz) | 12.1 KiB | `native/unknown` |
| [certbot_dns_ovh-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_ovh-5.8.0.tar.gz) | 12.5 KiB | `native/unknown` |
| [certbot_dns_rfc2136-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_rfc2136-5.8.0.tar.gz) | 16.5 KiB | `native/unknown` |
| [certbot_dns_route53-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_route53-5.8.0.tar.gz) | 15.4 KiB | `native/unknown` |
| [certbot_dns_sakuracloud-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_dns_sakuracloud-5.8.0.tar.gz) | 12.1 KiB | `native/unknown` |
| [certbot_nginx-5.8.0.tar.gz](https://github.com/certbot/certbot/releases/download/v5.8.0/certbot_nginx-5.8.0.tar.gz) | 6.4 KiB | `native/unknown` |
| [SHA256SUMS](https://github.com/certbot/certbot/releases/download/v5.8.0/SHA256SUMS) | 1.6 KiB | `other` |
| [SHA256SUMS.asc](https://github.com/certbot/certbot/releases/download/v5.8.0/SHA256SUMS.asc) | 659 B | `other` |

## 流行度

- **Star**: 33,232 · **Fork**: 3,510 · **开放 issue**: 5,574 · **贡献者**: 490

## 累计统计

- **发布数**: 73 · **已合并 PR**: 4134 · **开放 PR**: 63 · **已关闭 issue**: 5452 · **开放 issue**: 122 · **提交数**: 11436

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 4 | 2 | 3 | 1 | 9 |
| 90d | 2026-06-12 | 2 | 18 | 8 | 15 | 8 | 31 |
| 360d | 2025-09-15 | 10 | 118 | 24 | 63 | 42 | 184 |

## 代码规模

合计: **73,351** 行代码（覆盖前 5 种语言、共 **725** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Python | 57,786 | 5,348 | 11,791 | 366 |
| Bitbake | 6,296 | 3,415 | 1,706 | 237 |
| ReStructuredText | 2,660 | 0 | 928 | 97 |
| Sh | 2,066 | 520 | 346 | 20 |
| Json | 1,446 | 0 | 0 | 5 |

## OpenSSF Scorecard 评分

总评分: **6.9 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 改进这些数据

certbot 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `certbot` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/certbot.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T16:35:20Z._
