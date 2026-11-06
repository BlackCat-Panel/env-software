# BlackCat Panel 环境软件备用下载

面板安装软件时，官方/国内镜像失败后会回退到本仓库 GitHub Releases（并经 `ghfast.top` 加速）。

## Releases

| Tag | 说明 |
|-----|------|
| `nginx-all` | Nginx：Windows `.zip` / Linux `.tar.gz` |
| `openresty-all` | OpenResty：Windows `.zip` / Linux `.tar.gz` |
| `apache-all` | Apache：Windows `.zip` / Linux `.tar.gz` |
| `mysql-all` | MySQL：Windows `.zip` / Linux `.tar.xz` 或 `.tar.gz` |
| `mariadb-all` | MariaDB：Windows `.zip` / Linux `.tar.gz` |
| `redis-all` | Redis：Windows 移植包 / Linux 官方源码 `.tar.gz` |
| `pgsql-all` | PostgreSQL：Windows EDB 二进制 zip / Linux 官方源码 `.tar.gz` |

## 命名约定

- PostgreSQL Win: `postgresql-<ver>-windows-x64-binaries.zip`（如 `16.6-1`）
- PostgreSQL Linux: `postgresql-<ver>.tar.gz`（如 `16.6`）

仓库公开，仅作备用源；请优先使用官方 CDN。