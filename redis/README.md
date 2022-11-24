# README

Redis Middleware


# Read Redis Source

[redis](https://github.com/redis/redis)


[annotated Redis 3.0 source code](https://github.com/huangz1990/redis-3.0-annotated)

[如何阅读 Redis 源码](https://blog.huangz.me/diary/2014/how-to-read-redis-source-code.html)

[Sphinx 和 readthedocs](https://blog.huangz.me/diary/2013/tools-for-writing-redisbook.html)



# Commands 

[redis commands](https://redis.com.cn/commands.html)


# Redis Internal

Data Structure

Network I/O Module

AOF

RDB

PUB/SUB

Replication

Sentinel

Cluster


# DevOps


## Info Command

[info Command](https://redis.io/commands/info/)

```
INFO [section [section ...]]
```

section
- server: General information about the Redis server
- clients: Client connections section
- memory: Memory consumption related information
- persistence: RDB and AOF related information
- stats: General statistics
- replication: Master/replica replication information
- cpu: CPU consumption statistics
- commandstats: Redis command statistics
- latencystats: Redis command latency percentile distribution statistics
- cluster: Redis Cluster section
- modules: Modules section
- keyspace: Database related statistics
- modules: Module related sections
- errorstats: Redis error statistics



## Prometheus Monitor

[Prometheus Exporter for Redis Metrics](https://github.com/oliver006/redis_exporter)



## Migration

[redis-shake](https://github.com/alibaba/RedisShake) is a tool for Redis data migration and data filtering.


[redis-full-check](https://github.com/alibaba/RedisFullCheck) is used to compare whether two redis have the same data.


## Cluster Management


[CacheCloud](https://github.com/sohutv/cachecloud) is a Redis cloud management platform. 
It supports Standalone, Sentinel, and Cluster architectures for Redis, 
effectively reducing large-scale Redis operation and maintenance costs, and improving re…







