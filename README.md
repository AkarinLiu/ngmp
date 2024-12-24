# NGMP (Nginx MariaDB PHP)

## 这个项目是什么？

这个项目是将复杂的手动配置流程自动化安装和配置一个 Nginx + MariaDB + PHP 环境。

## 这个项目的存在意义是什么？
近期， LNMP 一键安装包被曝光植入后门，因此，本项目旨在提供一个安全、稳定、高效的 Nginx + MariaDB + PHP 环境。

## 要求

| 要求 | 详细信息 |
|-----|-----|
|操作系统 | Debian 11 以上（推荐）、Rockly Linux 8 以上、AlmaLinux 8 以上 |
| 内存 | 2GB 以上 |
| 硬盘 | 20GB 以上 |

## 安装

*注意：请使用Root身份运行这个脚本！！*

```bash
wget --no-clobber https://raw.githubusercontent.com/AkarinLiu/NGMP/master/ngmp && bash ngmp
```

位于中国大陆地区的服务器可以使用以下脚本：

```bash
wget --no-clobber https://mirror.ghproxy.com/https://raw.githubusercontent.com/AkarinLiu/ngmp/master/ngmp && bash ngmp
```
## 已知问题

以下是已知问题列表，欢迎提交 [Pull Request](https://github.com/AkarinLiu/ngmp/pulls) 来修复这些问题。

- [ ] 在 Debian 11 以下的版本，无法正常安装。

## 鸣谢
- [CodeGeeX](https://codegeex.com)
- [智谱轻言](https://chatglm.cn)