### 关系型数据库

1. 英文: RDB -> Relational Database
2. 组织数据的核心特点: 以行和列组成的数据表 (table)

- #### students

- ID NAME
- 1 Mike
- 2 Joe

3. 数据表之间通过主键和外键进行关联并形成数据集合

- #### students

- ID NAME CLASS_NO
- 1 Mike 2
- 2 Joe 1

- #### class

- ID NAME TEACHER
- 1 class1 Mendy
- 2 class2 Crystal

4. 对数据进行类型, 结构和序列化的强约束

### 非关系型数据库

1. 英文: NoSQL
2. 无关系模型
3. 不定义数据结构
4. 主要以 key-value 结构进行数据的描述

### Redis 简介

1. 英文: REmote DIctionary Server
2. 中文: 远程字典数据存储服务

- remote: 远程

3. key-value 数据存储服务系统

### Redis 特点

1. 跨平台
2. 非关系型数据存储
3. 开源 [地址](https://github.com/redis/redis)
4. 支持分布式, 持久性数据存储
5. 支持各种语言的 API
6. 性能高 (10 万次/秒)
7. 多种数据类型支持

### Redis 下载与安装

- [官网](https://redis.io/)
- [windows 客户端下载](https://github.com/tporadowski/redis/releases/tag/v5.0.14.1)

- Mac 的下载安装

  1. 安装 homebrew
  2. 安装 redis

  - brew install redis

### Redis 启动

1. 打开命令行工具
2. redis-server 启动服务
3. redis-cli 进行 redis 的操作环境

- 默认主机: 120.0.0.1
- 默认端口: 6379

4. 执行 set mobile 13800000001

- set 设置
- mobile key
- 13800000001 value

5. get mobile

### Redis 的配置

1. config get \* 获取所有配置
