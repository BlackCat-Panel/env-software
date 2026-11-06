# BlackCat Panel 环境软件备用下载

面板安装软件时，官方/国内镜像失败后会回退到本仓库 GitHub Releases（并经 ghfast.top 加速）。

## Releases

| Tag | 说明 |
|-----|------|
| 
ginx-all | Nginx |
| openresty-all | OpenResty |
| pache-all | Apache |
| mysql-all | MySQL |
| mariadb-all | MariaDB |
| 
edis-all | Redis |
| pgsql-all | PostgreSQL |
| mongodb-all | MongoDB（Windows zip / Linux ubuntu/debian/rhel tgz） |
| jdk-all | OpenJDK Temurin 8/11/17/21（Win zip / Linux tar.gz） |
| 	omcat-all | Apache Tomcat 10/9/8/7（zip + tar.gz） |
| php-all | PHP 8.5~5.3（Win zip + 源码 tar.gz） |
| composer-all | Composer（latest-stable + 面板列表版本 phar） |

## 命名约定

- MongoDB Win: mongodb-windows-x86_64-<ver>.zip
- MongoDB Linux: mongodb-linux-x86_64-<plat>-<ver>.tgz
- JDK Win: jdk-<ver>-windows-x64.zip
- JDK Linux: jdk-<ver>-linux-x64.tar.gz
- Tomcat: pache-tomcat-<ver>.zip / pache-tomcat-<ver>.tar.gz
- PHP Win: php-<ver>-Win32-<crt>-x64.zip（5.3/5.4 为 x86）
- PHP Linux: php-<ver>.tar.gz
- Composer: composer-latest-stable.phar / composer-<ver>.phar

仓库公开仅作开源软件镜像备用，请优先使用官方 CDN。
