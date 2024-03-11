# NGMP (Nginx MariaDB PHP)

## 这个项目是什么？

这个项目是将复杂的手动配置流程自动化安装和配置一个 Nginx + MariaDB + PHP 环境。

## 这个项目的存在意义是什么？
近期， LNMP 一键安装包被曝光植入后门，因此，本项目旨在提供一个安全、稳定、高效的 Nginx + MariaDB + PHP 环境。

## 要求

| 要求 | 详细信息 |
|-----|-----|
|操作系统 | Debian 11 以上（推荐）、Rockly Linux 8 以上、AlmaLinux 8 以上 |
| 内存 | 1GB 以上 |
| 硬盘 | 20GB 以上 |

## 安装
```bash
wget https://raw.githubusercontent.com/AkarinLiu/NGMP/main/ngmp && bash ngmp