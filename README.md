# study
学习资料总结

================================================================================
以下的所有学习资料均来自网友的总结

JVM：
  1. JVM内存区域    https://github.com/969251639/study/wiki/JVM%E5%86%85%E5%AD%98%E5%8C%BA%E5%9F%9F
  2. JVM运行时内存   https://github.com/969251639/study/wiki/JVM%E8%BF%90%E8%A1%8C%E6%97%B6%E5%86%85%E5%AD%98
  3. 垃圾回收与算法    https://github.com/969251639/study/wiki/%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E4%B8%8E%E7%AE%97%E6%B3%95
  4. GC垃圾收集器    https://github.com/969251639/study/wiki/GC%E5%9E%83%E5%9C%BE%E6%94%B6%E9%9B%86%E5%99%A8
  5. JVM类加载机制   https://github.com/969251639/study/wiki/JVM-%E7%B1%BB%E5%8A%A0%E8%BD%BD%E6%9C%BA%E5%88%B6
  6. 类加载器   https://github.com/969251639/study/wiki/%E7%B1%BB%E5%8A%A0%E8%BD%BD%E5%99%A8
  
JAVA并发包：
  1. 前言
  2. JAVA  线程实现和创建
  3. jdk 4种线程池
  4. 线程基本用法
  5. 线程池
  6. 阻塞队列
  7. java并发包工具类
  8. volatile
  9. ThreadLocal
  10. 锁
  10. ConcurrentHashMap
  11. CAS
  12. AQS （ 抽象的队列同步器 ）
  
JAVA集合类：

kafka：
  1. kafka存储
  2. kafka生产者
  3. kafka消费者
  
mybatis:
  1. mybatis缓存
  
mysql：
  1. 存储引擎
  2. 索引
  3. Percona-toolkit 功能列表
  4. show profile
  5. Mysql threads connect
  6. Pt-table-sync同步主从不一致
  7. binlog主从同步使用
  8. Mysql常见索引
  9. pt-query-digest分析慢查询
  10. MySql慢日志
  
netty:
  1. netty原理
  2. netty RPC实现

rabbitmq:
  1. rabbitmq架构
  
redis:
  1. 字符串
  2. 链表
  3. 字典
  4. 跳跃表
  5. 整数
  6. 压缩列表
  7. 对象
  8. 数据库
  9. RDB
  10. AOF
  11. 事件
  12. 客户端
  13. 服务端
  14. 主从复制
  15. 哨兵
  16. 集群
  16. 注意事项

spring:
  1. 前言
  2. IOC
  3. AOP
  4. Spring Bean
  5. Spring MVC
  
zookeeper：
  1. 前言
  2. ZAB
  
分布式缓存：
  1. 缓存雪崩
  2. 缓存穿透
  3. 缓存预热
  4. 缓存更新
  5. 缓存降级
  
日志：
  1. java日志组件
  
数据结构：
  1. 栈
  2. 队列
  3. 链表
  4. 散列表
  5. 排序二叉树
  6. 红黑树
  7. B树
  
网络：
  1. 7层架构
  2. TCP/IP
  3. HTTP
  4. CDN
  
一致性算法：
  1. Paxos
  2. Zab
  3. Raft
  4. Gossip
  5. 一致性哈希
  
线上问题排查技巧：

================================================================================
以下的源码浅析均来自个人的研究，中间肯定有很多待需纠正之处，仅供个人学习使用

java基础类：
  1. Object
  2. String
  3. ArrayList
  4. HashMap
  5. HashSet

线程：
  1. ThreadPoolExecutor
  2. ThreadLocal
  3. Actomic

并发包：
  1. AbstractQueueSysnchorized

Tomcat：
  
Mybatis：

Spring：

Spring MVC：

Spring Boot

Eurka

Sharding-jdbc

kafka

================================================================================
设计方案：
  1. 参数校验
  2. 分布式ID
  3. 分布式任务
  4. 分布式事务
  5. 分布式锁
  6. 缓存设计
  7. 开发平台设计
  8. 配置文件设计
  9. 批量任务存储设计
  10. 规则设计
  11. 事件监听设计
  12. 统计设计
  13. 自动化测试
  14. 消息可靠传输
  15. 事件轮
  
