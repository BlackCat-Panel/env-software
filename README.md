# BlackCat Panel 环境软件备用下载

面板安装软件时，官方/国内镜像失败后会回退到本仓库 GitHub Releases（并经 `ghfast.top` 加速）。

## Releases

| Tag | 说明 |
|-----|------|
| `nginx-all` | Nginx |
| `openresty-all` | OpenResty |
| `apache-all` | Apache |
| `mysql-all` | MySQL |
| `mariadb-all` | MariaDB |
| `redis-all` | Redis |
| `pgsql-all` | PostgreSQL |
| `mongodb-all` | MongoDB（Windows zip / Linux `ubuntu/debian/rhel` tgz） |
| `jdk-all` | OpenJDK Temurin 8/11/17/21（Win zip / Linux tar.gz） |
| `tomcat-all` | Apache Tomcat 10/9/8/7（zip + tar.gz） |
| `php-all` | PHP 8.5~5.3（Win zip + 源码 tar.gz） |
| `composer-all` | Composer（latest-stable + 面板列表版本 phar） |
| `nodejs-all` | Node.js（Win zip + Linux tar.xz） |
| `pm2-all` | PM2（npm tarball） |
| `deno-all` | Deno（Win/Linux x64 zip，`deno-v{ver}-…`） |
| `python-all` | Python（Win embed zip + Linux astral standalone） |
| `go-all` | Go SDK（Win/Linux amd64+arm64） |
| `frp-all` | frp（官方包含 frps+frpc；Win/Linux amd64+arm64） |
| `roundcube-all` | Roundcube WebMail（complete tar.gz） |

## 命名约定

- MongoDB Win: `mongodb-windows-x86_64-<ver>.zip`
- MongoDB Linux: `mongodb-linux-x86_64-<plat>-<ver>.tgz`
- JDK Win: `jdk-<ver>-windows-x64.zip`
- JDK Linux: `jdk-<ver>-linux-x64.tar.gz`
- Tomcat: `apache-tomcat-<ver>.zip` / `apache-tomcat-<ver>.tar.gz`
- PHP Win: `php-<ver>-Win32-<crt>-x64.zip`（5.3/5.4 为 x86）
- PHP Linux: `php-<ver>.tar.gz`
- Composer: `composer-latest-stable.phar` / `composer-<ver>.phar`
- Node.js Win: `node-v<ver>-win-x64.zip`
- Node.js Linux: `node-v<ver>-linux-x64.tar.xz`
- PM2: `pm2-latest.tgz` / `pm2-<ver>.tgz`
- Deno: `deno-v<ver>-x86_64-pc-windows-msvc.zip` / `deno-v<ver>-x86_64-unknown-linux-gnu.zip`
- Python Win: `python-<ver>-embed-amd64.zip`
- Python Linux: `cpython-<ver>+<tag>-x86_64-unknown-linux-gnu-install_only.tar.gz`
- Go: `go<ver>.windows-amd64.zip` / `go<ver>.windows-arm64.zip` / `go<ver>.linux-amd64.tar.gz` / `go<ver>.linux-arm64.tar.gz`
- frp: `frp_<ver>_windows_amd64.zip` / `frp_<ver>_windows_arm64.zip` / `frp_<ver>_linux_amd64.tar.gz` / `frp_<ver>_linux_arm64.tar.gz`
- Roundcube: `roundcubemail-<ver>-complete.tar.gz`

仓库公开仅作开源软件镜像备用，请优先使用官方 CDN。
