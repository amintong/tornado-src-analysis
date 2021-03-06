# tornado源码解析

## 简介
   此项目主要是针对python web框架——tornado源码相关模块进行解析，加深对web开发的理解。在详解某一模块时会引入相关基础知识概念。包括以下几个知识点：

* [tornado.ioloop](./tornado_ioloop.md)
    * [socket（TCP三次握手、四次挥手）](./socket.md)
    * [IO多路复用（select、epoll、kqueue）](./io_multiplexing.md)
    * [tornado中对posix接口的实现](./tornado_platform_posix.md)
    * [tornado定时器](./tornado_ioloop_PeriodicCallback.md)
    * [tornado配置类Configurable](./tornado_util_configurable.md)
* [tornado.httpserver](./tornado_httpserver.md)
* [tornado.iostream](./tornado_iostream.md)
* [tornado.http1connection](./tornado_http1connection.md)
* [tornado.concurrent](./tornado_concurrent.md)
* [tornado.gen](./tornado_gen.md)
* [tornado.application](./tornado_application.md)

## 环境
* python 2.7
* tornado 4.5.1
* Ubuntu 16.04
