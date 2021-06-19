##### 参考文档

```
1.https://www.cnblogs.com/xiaoxi/category/961351.html	入门

2.https://draveness.me/whys-the-design-redis-single-thread/	单线程模型 Why the Design ?

```



##### 备注

```
Redis核心对象
	redisObject{
		数据类型(type)	String, Hash, List, Set, Zset
		编码方式(encoding)
		数据指针(ptr)
		虚拟内存(vm)
		其他信息  
	}
	
Redis单线程模型
Redis Hash实现
双向链表
栈/队列
跳跃表
lru机制
持久化(RDB方式和AOF方式)
FLUSHALL
```

