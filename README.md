# BlackCat Panel 环境软件备用下载

面板安装软件时，官方/国内镜像失败后会回退到本仓库 GitHub Releases（并经 `ghfast.top` 加速）。

## Releases

| Tag | 说明 |
|-----|------|
| `nginx-all` | Nginx：Windows `.zip` / Linux `.tar.gz` |
| `openresty-all` | OpenResty：Windows `.zip` / Linux `.tar.gz` |
| `apache-all` | Apache：Windows `.zip` / Linux `.tar.gz` |
| `mysql-all` | MySQL：Windows `.zip` / Linux `.tar.xz` 或 `.tar.gz`（8.4 / 8.0 / 5.7 / 5.6 / 5.5） |

## 命名约定

- Nginx: `nginx-<ver>.zip` / `nginx-<ver>.tar.gz`
- OpenResty: `openresty-<ver>-win64.zip` / `openresty-<ver>.tar.gz`
- Apache Win / Linux: `httpd-<ver>-...` / `httpd-<ver>.tar.gz`
- MySQL Win: `mysql-<ver>-winx64.zip`
- MySQL Linux: `mysql-<ver>-linux-glibc2.28-x86_64.tar.xz` 或 `glibc2.12` 的 `.tar.xz` / `.tar.gz`

仓库公开，仅作备用源；请优先使用官方 CDN。