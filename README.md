# ProxyIpPool,运行测试:com.myapp.timer.Timer   mian函数

[![Build Status](https://travis-ci.org/letcheng/ProxyPool.svg?branch=master)](https://travis-ci.org/letcheng/ProxyPool)

### 3个定时器线程,第一个负责收集代理ip,第二个个负责运行维护代理ip,第三个负责存储到redis,(redis并做持久化服务),并于每天提供服务后重新放入池子第二天再进行维护。

#### 系统原理图

![cmd-markdown-logo](http://o9beglkd1.bkt.clouddn.com/proxyippool.png)
Test2

