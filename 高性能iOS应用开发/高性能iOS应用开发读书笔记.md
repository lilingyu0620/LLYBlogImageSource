---
title: 高性能iOS应用开发读书笔记
date: 2017-07-07 10:02:22
tags:
---

![](http://ofy1hyquv.bkt.clouddn.com/%E9%AB%98%E6%80%A7%E8%83%BDiOS%E5%BA%94%E7%94%A8%E5%BC%80%E5%8F%91.png)

### 第一章 移动应用的性能

* 应用首次工作出错以后，79%的用户只会再重试一两次
* 当应用载入时间超过3秒时，25%的用户会放弃使用该应用。
* 31%的用户会将糟糕的体验转告他人。

#### 定义性能

高性能有着多重的含义和丰富的解释方式。

#### 性能指标

* 内存
* 电池消耗
* 程序初始化时间
* 执行速度
* 响应速度
* 本地存储
* 互操作性
* 网络环境
* 带宽
* 数据刷新
* 多用户支持
* 单点登录
* 安全
* 崩溃

#### 应用性能分析

* 采样
* 埋点

#### 测量

过早优化是编程领域的万恶之源--高德纳？？？

[测试代码地址](https://github.com/gvaish/hpios)

### 第二章 内存管理

90%的应用崩溃与内存管理有关，其中最主要的原因是错误的内存访问和保留环所引起的内存泄露 -- Apple Dev






