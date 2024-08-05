﻿# C+核心编程-面向对象

## 内存分区模型（4个区域）
意义：不同区域存放不同的数据，赋予不同的生命周期
### 代码区
存放函数体的二进制代码，由操作系统进行管理
### 全局区
存放全局变量和静态变量以及常量
### 栈区
存放函数的参数值，局部变量等
### 堆区

## 程序运行前（exe）
代码区：存放CPU执行的及其指令；共享的；只读的；
全局区：存放全局变量和静态变量；还包含常量区，字符串常量和其它常量也存放在此；

