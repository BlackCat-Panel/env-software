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
| `redis-all` | Redis：Windows 移植包 `Redis-x64-*.zip` / Linux 官方源码 `redis-<ver>.tar.gz` |

## 命名约定

- Nginx / OpenResty / Apache / MySQL / MariaDB：见各 Release 文件名
- Redis Win: `Redis-x64-5.0.14.1.zip` 等
- Redis Linux: `redis-<ver>.tar.gz`

仓库公开，仅作备用源；请优先使用官方 CDN。