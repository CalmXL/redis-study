### Redis 数据类型

#### 1. 字符串类型(string)

- 最大可存储 512MB
- key - value
- set mobile 13800000001
- get mobile

#### 2. 哈希类型(Hash)

- key - value
- key: { name: mike, age: 18}
- hset user name mike
- hset user age 18
- hset user score 98

- hget user name
- hgetall user
- hmset user2 name joe age 18

#### 3. 列表(List)

- rpush database mysql
- rpush database mongodb
- lpush database oracle
- lrange database 0(start) 10(end)
- lpop database
- rpop database

#### 4. 无序集合(Unsorted Set)

1. 集合元素无序
2. 集合元素唯一

- sadd students mike
- scard students 返回数量
- smembers students 列出元素
- sdiff students students2 列出差集
- sdiffstore students3 students students2 保存到 students3
- sinter students students2 交集
- sinterstore students4 students students2
- smove students students2 rose 将 students 中的 rose 移动到 students2
- spop students2
- srandmemeber students2 2
- srem students joe
- sunion students students2 返回并集
- sunionstore students6 students students2
- sscan students6 0 match j\*
