# 事件总线

事件总线是将消息从发送方传输到接收方的中介. 它在对象,服务和应用程序之间提供了一种松散耦合的通信方式.

## 事件总线类型

ABP框架提供了两种事件总线类型;

* **[本地事件总线](Local-Event-Bus.md)** 适合进程内消息传递.
* **[分布式事件总线](Distributed-Event-Bus.md)** 适合进程间消息传递,如微服务发布和订阅分布式事件.