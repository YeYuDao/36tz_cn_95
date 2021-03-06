# 36tz_cn_95
理论+实战 构建完整JVM知识体系
理论+实战 构建完整JVM知识体系
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fce10ce09e9829905400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 课程导学与准备工作 

#### 本章主要介绍为何要带大家从零开始学习一门JVM基础与实战相结合的系统课程，之后会为大家介绍本课程内容具体安排，最后给出如何学好这门课程的一些学习建议。希望大家都能通过这门课程，学有所成，学有所归。
1-1 课前必读（不看会错过一个亿）

1-2 课程介绍及学习指导 (12:18)


### 第2章 认识JVM规范 

#### 本章首先从三种认知角度带你了解JVM以及JVM的组成，帮你建立JVM知识体系，再通过阅读JVM规范来带大家掌握Class文件的格式，实现Class文件字节码的阅读，之后带大家进入ASM的开发，学会动态创建Java类。
2-1 从三种认知角度重识JVM (12:19)

2-2 JVM规范作用及其核心 (13:43)

2-3 理解JVM规范中的虚拟机结构 (14:19)

2-4 如何学习JVM规范中的指令集 (11:22)

2-5 Class字节码解析：理解ClassFile结构 (13:16)

2-6 阅读Class字节码：常量池 (17:43)

2-7 阅读Class字节码：类定义和属性 (15:53)

2-8 阅读Class字节码：方法和方法调用 (13:08)

2-9 ASM开发：编程模型和核心API (14:22)

2-10 ASM开发：ClassVisitor开发 (16:36)

2-11 ASM开发：MethodVisitor开发 (12:58)

2-12 ASM开发：实现模拟AOP功能 (15:24)


### 第3章 类加载、连接和初始化

#### 本章将带大家从类加载到JVM再到类卸载，剖析完整过程中的每个步骤的细节功能和核心技能，结合实战，重点需要大家理解类加载、类加载器，双亲委派模型，理解并掌握各种主动使用类的初始化时机等。
3-1 类加载和类加载器 (13:21)

3-2 案例：类加载器使用 (16:09)

3-3 双亲委派模型 (10:14)

3-4 案例：自定义ClassLoader (13:53)

3-5 双亲委派模型说明和代码示例 (14:42)

3-6 类连接和初始化 (17:49)

3-7 案例：类的主动初始化 (10:10)

3-8 案例：类的初始化机制和顺序 (15:59)


### 第4章 内存分配

#### 本章先带大家系统学习Java的内存分配模型，堆内存核心内容，内存分配相关的各种参数的配置和使用，然后带大家掌握各种内存溢出，学习如何使用MAT工具进行内存溢出的分析和问题查找。
4-1 JVM的简化架构和运行时数据区 (19:09)

4-2 Java堆内存模型和分配 (14:38)

4-3 案例：Trace跟踪和Java堆的参数配置 (16:52)

4-4 案例：新生代配置和GC日志格式 (22:52)

4-5 案例：使用MAT进行内存分析 (17:39)

4-6 案例：堆、栈、元空间的参数配置 (23:34)


### 第5章 字节码执行引擎

#### 本章先带大家深入Java栈，理解栈帧、运行期操作数和局部变量表之间的交互关系，再带大家剖析方法调用，掌握静态分派和动态分派，最后通过实战带大家理解如何执行方法中的字节码指令。
5-1 栈帧和局部变量表 (14:48)

5-2 案例：slot是复用的 (12:41)

5-3 案例：操作数栈 (14:53)

5-4 静态分派和动态分派 (14:47)


### 第6章 垃圾回收

#### 本章先来掌握垃圾回收的不可达算法、垃圾判断步骤、GC类型、引用类型等基础内容，再带大家深入垃圾回收的算法，包括标记清除法、复制算法、标记整理等，最后带大家掌握各种垃圾收集器，包括串行收集器、并行收集器、新生代Parallel Scavenge收集器、CMS、G1等。...
6-1 垃圾回收基础和根搜索算法 (13:08)

6-2 引用分类 (13:22)

6-3 案例：各种引用的实现 (14:58)

6-4 垃圾回收基础【跨代引用、记忆集、写屏障、判断垃圾的步骤、STW】 (21:44)

6-5 垃圾回收算法 (15:05)

6-6 垃圾收集器基础和串行收集器 (12:53)

6-7 并行收集器和Parallel Scavenge收集器 (12:58)

6-8 CMS收集器 (11:04)

6-9 G1收集器 (22:23)

6-10 ZGC收集器、GC性能指标和JVM内存配置原则 (14:44)


### 第7章 高效并发

#### 本章先来分析Java内存模型，内存间的交互操作，然后学习多线程的可见性、有序性和指令重排、线程安全的处理方法，最后带大家学习自旋锁、锁消除、锁粗化、轻量级锁、偏向锁等锁优化。
7-1 Java内存模型和内存间的交互操作 (13:22)

7-2 内存间的交互操作的规则 (10:29)

7-3 volatile特性 (12:56)

7-4 指令重排原理和规则 (15:30)

7-5 代码示例：指令重排的各种情况分析 (16:33)

7-6 线程安全处理 (10:31)

7-7 锁优化 (18:45)


### 第8章 性能监控与故障处理工具

#### 本章带你掌握实际工作中的高频技能，包括jps、jinfo、jstack、jmap、jstat、jstatd、jcmd等命令行工具和jconsole、 jmc、visualvm等图形化工具，最后结合实际操作带你理解两种远程连接方式：JMX、jstatd。
8-1 命令行工具 (14:28)

8-2 jconsole (07:37)

8-3 jmc1 (18:27)

8-4 jmc2 (10:34)

8-5 visualVM (16:54)

8-6 远程连接 (12:59)

8-7 监控实战1 (19:35)

8-8 监控实战2 (14:08)


### 第9章 【实战】JVM调优

#### 本章将从调什么、如何调、调的目标是什么三个方面带你掌握如何进行JVM调优，接着传授你JVM调优策略、调优冷思考、调优经验、如何分析和处理内存溢出，最后我们将综合应用这些知识，在给定的应用上，实战JVM调优。
9-1 JVM调优：调什么、如何调 (17:06)

9-2 调优的目标、调优的策略和调优冷思考 (12:34)

9-3 JVM调优经验、内存泄漏分析 (15:29)

9-4 实战JVM调优：认识待调优的应用 (18:34)

9-5 实战JVM调优：录制JFR并分析结果 (13:06)

9-6 实战JVM调优：按照分析结果调整JVM运行时内存参数 (16:49)

9-7 实战JVM调优：查找内存泄漏点、分析并处理内存泄漏 (23:14)


### 第10章 面试加油站

#### 本章以面试官视角带你剖析JVM面试问题，掌握回答技巧，轻松搞定面试中涉及到JVM相关问题，为大家的面试助力。
10-1 字节码部分【面试精讲】 (15:58)

10-2 内存分配【面试精讲】 (20:20)

10-3 监控工具和实战【面试精讲】 (17:13)


### 第11章 课程总结

#### 本章将带大家回顾总结课程重点难点，在课程问答区CC老师等着与你进一步交流，有问题欢迎大家到课程问答区提问。
11-1 课程总结 (08:54)


[下载地址](http://www.36tz.cn "下载地址")
