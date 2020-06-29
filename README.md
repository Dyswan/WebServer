# WebServer
A C++ High Performance WebServer

## Introduction
之所以写这个项目，主要是对linux网络编程做一个总结。
本项目为C++11编写的多线程HTTP网络服务器，目前主要完成的工作有:<br>
1. 基于Reator模式的事件分发器
2. 对epoll进行了封装
3. 实现了一个基本的工作线程池
4. 使用状态机实现http解析
5. 使用智能指针进行资源管理

## Run
$ ./httpServer [port] [io-ThreadNum] [worker-ThreadNum] [second]
