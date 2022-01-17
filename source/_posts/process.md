---
title: process
date: 2021-08-17 15:47:36
tags:
 - 
categories:
 - Go
cover: https://cdn.jsdelivr.net/gh/ThinkBIM/CDN@V1.0/comic/pic_1.jpg
---

# 进程 Process



## 孤儿进程

父进程不在了，子进程还在运行



## 僵尸进程

一个进程使用fork创建子进程，如果子进程退出，而父进程并没有调用wait或waitpid获取子进程的状态信息，那么子进程的进程描述符仍然保存在系统中。这种进程称之为僵尸进程



## 守护进程

后台服务进程  &

{% post_link /page/go/sort 你好 %}
