# 特别说明

本项目用来保存自己编译的 x86_64 软路由固件。

## 项目简介

每个自然月更新一次固件，固件文件类型为 imge。

## 插件列表

该项目基于个人喜好，删除了大部分不需要使用的插件，编译过程中主要添加了以下插件（部分必要插件不做说明）。

- OpenClash
- Docker
- Docker-CE
- Turbo ACC
- ServerChan
- 动态 DNS
- KMS 服务器
- UPnP

~~- 阿里云盘 FUSE~~

~~- 阿里云盘 WebDAV~~


## 使用方法

- 下载相关版本固件 [Release](https://github.com/brick713/OpenWRT_X86_64/releases)
- 在软路由 Web 端直接上传固件升级，或使用命令行`sysupgrade -v xxxx.img`


## 提醒

第一次刷写 efi 固件会重置软路由密码，将会重置为 Lean 大固件默认的密码。
