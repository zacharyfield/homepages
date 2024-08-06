---
date: 2022-09-06T22:42:23+08:00
title: Clash 简介
navWeight: 1000 # Upper weight gets higher precedence, optional.
linkTitleIcon: <i class="fas fa-fw fa-book"></i> # The icon of the link title, optional.
series:
  - Guide
---

Clash 是一个使用 Go 语言编写，基于规则的跨平台代理软件核心程序 [已删库]

## 特点

这是对Clash特性的概述.  

- Inbound: HTTP、HTTPS、SOCKS5服务器、TUN设备
- Outbound: Shadowsocks(R)， VMess, Trojan, Snell, SOCKS5, HTTP(S)， Wireguard
- 基于规则的路由: 动态脚本、域、IP地址、进程名等
- Fake-IP DNS: 减少对DNS污染的影响，提高网络性能
- 透明代理: 重定向TCP和TProxy TCP/UDP协议，支持自动管理路由表/规则
- 代理组: 自动回退、负载均衡、延迟测试
- Remote: 动态加载远程代理列表
- RESTful API: 通过全面的API原地更新配置

## Clash.Meta 

另外一种Clash内核程序

[点此看源码](https://github.com/clash-next/clash-meta/).

## Clash Meta for Android

Clash.Meta 的安卓客户端程序 (适用除苹果外的其他品牌智能手机)

[点此看源码](https://github.com/MetaCubeX/ClashMetaForAndroid/).

### 系统要求

- 安卓 5.0+ (最低)
- 安卓 7.0+ (推荐)
- `armeabi-v7a` , `arm64-v8a`, `x86` or `x86_64` 架构CPU

