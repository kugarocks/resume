---
theme: theme.json
author: kugarocks
date: MMMM dd, YYYY
paging: Slide %d / %d
---

# ℹ️  关于我

| 名字 | 生日 | GitHub | 个人网站 |
| ------ | ------ | ------ | ------ |
| 邓焕良 | 1992-02 | [kugarocks](https://github.com/kugarocks) | [kugarocks.com](https://www.kugarocks.com) |

## 📚 教育经历

* 大学：华南农业大学
* 专业：软件工程
* 学历：本科(2010-2014)
* 证书：英语六级

## 👨‍💻 工作经历

* 2014-08 ~ 2015-07 115网盘  研发工程师
* 2015-09 ~ 2017-06 酷狗音乐 后台工程师
* 2017-12 ~ 2021-05 欢聚时代 高级开发工程师
* 2021-07 ~ 2023-11 趣丸科技 高级开发工程师

---

## 🚀 115网盘

主要负责：文件分享、进程管理、短地址服务等。

## 💻 相关技术

PHP、SSDB、Gearman、Supervisor、Elasticsearch。

## 📋 工作内容

* 网盘文件分享，采用 Gearman 异步把文件快照复制到用户目录。
* 使用 Supervisor 管理 Gearman 进程，如重启、重载配置。
* 使用 Elasticsearch 的文档 ID 作为分布式 ID。
* 开发短地址服务，基于 Base58，用于短信发送。

---

## 🚀 酷狗音乐

主要负责：APP 接口开发、支付网关。

## 💻 相关技术

Lua、OpenResty、PHP、Redis。

## 📋 工作内容

* 使用 Lua/OpenResty 开发酷币业务和音乐APP接口。
* 使用 PHP 开发支付网关，对接微信支付、支付宝支付等。
* 使用 Redis 3.0，以支持 Redis 原生集群。

---

## 🚀 欢聚时代

主要负责：Hello语音业务开发、活动模板、运营后台基础库开发。

## 💻 相关技术

PHP、Java、Yii2、Spring Boot、Apollo、Kong。

## 📋 工作内容

* 使用 PHP 开发 Hello 语音业务。
* 从 0-1 开发活动模板，运营可自行配置活动，代码已运行 5 年，上线 400+ 活动。
* 开发运营后台基础库，如 RBAC 权限管理、接入 CAS 统一登录。
* 把 PHP 服务迁移到 Java，并接入 Kong 网关和 Apollo 配置中心。

---

## 🚀 趣丸科技

主要负责：TTChat 海外语音业务开发、测试环境集群维护。

## 💻 相关技术

Golang、Kubernetes、Istio、gRPC-Gateway、Prometheus。

## 📋 工作内容

* 使用 Golang 开发 TTChat 海外语音业务，如用户等级、付费通话等。
* 维护测试环境 Kubernetes 集群，如采用亲和性调度平衡机器负载。
* 使用 gRPC-Gateway 代替 Gin 提供 HTTP 服务。
* 运营后台接入飞书登录和内部权限平台。

---

## 💭 空窗期 (2023-11 ~ 2024-11)

陪家人、旅游、学习新技术、写开源工具。

## 📚 学习书籍

* 《Linux 命令行与 Shell 脚本编程大全》
  * 发现 useradd 命令会修改 /etc/default/useradd 文件的权限。
  * 提交权限问题的 [PR](https://github.com/shadow-maint/shadow/pull/1080)。
  * 修复其它问题的 [PR](https://github.com/shadow-maint/shadow/pull/1086)。

## 💡 个人项目

* 个人网站：记录技术文章，https://www.kugarocks.com。
* 小黄人百科：记录小黄人的百科资料，https://minions.wiki。
* 迷你聊天室：终端风格的 Web 聊天室，https://minichat.kugarocks.com。
* Markdown Finder：命令行工具，快速查找和复制 Markdown 代码块。
