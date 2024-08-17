## 常见问题--面经总结

**待补充ing...**

* 其他rpc框架比较，如dubbo,gprc等
* 简单实现
  * JDK动态代理(CGLIB动态代理)--动态代理
  * 反射
* Socket
  * 网络IO
  * 五种IO模型
  * IO多路复用--select,poll,epoll区别
  * Java里面的IO--BIO,NIO,AIO
* Netty
  * 与Socket区别--阻塞非阻塞，事件驱动架构(并发)
  * Netty线程模型--三种Reactor模型
  * 零拷贝
  * 时间轮
* 解决粘包问题
  * 自定义协议
  * TCP粘包问题
  * 自定义编解码器怎么做的
* 序列化
  * 序列化原理
  * 四种序列化方式区别--JSON,Kryo,Hessian,Protobuf
  * Kryo的安全问题，为什么体积小
  * JSON序列化类型问题
  * 其他序列化--thrift,JDK
* Nacos服务注册
  * 服务从注册到下线(调用，响应)的整个流程
  * 与其他注册中心区别--Zookeeper,Eureka等
  * zk方向的问题--结构，分布式锁
  * 负载均衡策略--轮询，随机
  * 一致性哈希方向的问题
  * 钩子函数--注销服务
  * 同步/异步响应
* Netty心跳机制
  * 链路恢复 检测
  * Nacos心跳机制
* 注解扫描自动注册
