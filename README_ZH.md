 <h1 align="center">PostgreSQL数据库</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[PostgreSQL](https://github.com/memcached/memcached) 是一款‌开源对象-关系型数据库管理系统‌（ORDBMS）。其以可靠性、功能完备性和高度兼容 SQL 标准著称，支持 ACID 事务、复杂查询、外键约束、触发器等核心特性。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的Memcached。

## 核心特性

- **SQL标准兼容性‌：** 
  - 完全支持SQL标准，包括窗口函数、CTE(公共表表达式)等高级特性
  - 支持JSON、XML、数组等非结构化数据类型
- **扩展能力‌：** 
  - 通过插件系统支持时序数据库、地理空间数据处理等扩展功能
  - 支持自定义数据类型和操作符
- **并发控制‌：** 
  - 采用MVCC(多版本并发控制)机制，实现高并发读写
  - 支持细粒度的事务隔离级别

本项目提供的开源镜像商品 [**PostgreSQL数据库**](https://marketplace.huaweicloud.com/hidden/contents/42d1df14-d3e7-435d-9b20-281335a57634#productid=OFFI1164386440709509120) 已预先安装14.18版本的PostgreSQL数据库及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                               | 特性说明 | 备注 |
|--------------------------------------------------------------------------------------------------------------------| --- | --- |
| [PostgreSQL-14.18-kunpeng](https://github.com/HuaweiCloudDeveloper/postgreSQL-image/tree/PostgreSQL-14.18-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/postgreSQL-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md