# 计算机系统学习资源

## 博客

[LoyenWang](https://links.jianshu.com/go?to=https%3A%2F%2Fwww.cnblogs.com%2FLoyenWang%2F) Linux（内核，PCI驱动），Kvm（中断虚拟化，virtio）源码分析讲的很清晰

[stdrc.cc](https://stdrc.cc/) 最佳计算机学习网站

[知乎专栏:术道经纬](https://zhuanlan.zhihu.com/p/93289632) 文章基本与Linux有关

[kernelgo](https://kernelgo.org/) KVM相关的介绍值得一看

[UEFI-BIOS](https://www.zhihu.com/column/UEFIBlog) 介绍UEFI与BIOS的知乎专栏

## 项目

### 操作系统

[RT-Thread](https://github.com/RT-Thread/rt-thread) 实时操作系统

[Minos](https://github.com/minosproject/minos) 微内核实时操作系统，提供虚拟化支持

[swim](https://github.com/swimos/swim) 分布式microkernel

[Redox](https://github.com/redox-os/redox) RUST微内核操作系统

[rCore](https://github.com/rcore-os) RUST 操作系统

[SynestiaOS](https://github.com/SynestiaOS/SynestiaOS) 面向物联网的微内核操作系统，C语言编写，处于开发阶段

[armv8-bare-metal](https://github.com/NienfengYao/armv8-bare-metal) 针对ARMv8写的裸金属操作系统，代码很少，适合学习

[unikernel list](http://unikernel.org/projects/) 提供了所有开源uni kernel项目的**列表**，包括Rumprun，Drawbridge等

[risc os](https://gitlab.riscosopen.org/RiscOS) 针对arm的操作系统

[SimpleKernel](https://github.com/Simple-XX/SimpleKernel) 正在开发中的内核，可以用来练手

[Tisu OS 太素OS](https://github.com/belowthetree/TisuOS) 一个国内大学生用Rust开发的基于RISC-V的操作系统，能够支持最基本的设备与GUI

[BookOS](https://github.com/hzcx998/BookOS) 基于xbook2内核的C语言操作系统

[tetris-os](https://github.com/jdah/tetris-os) 一个专门跑俄罗斯方块的操作系统

### 虚拟机监控器

[cloud-hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) Rust语言编写的虚拟机监控器，提供设备的热插拔功能，支持跑Linux与Windows虚拟机

[firecracker](https://github.com/firecracker-microvm/firecracker) serverless场景中的虚拟机监控器，Rust编写

[ACRN](https://github.com/projectacrn/acrn-hypervisor) 嵌入式领域虚拟机监控器，intel开发，提供实时性，支持跑windows虚拟机，支持设备直通与virtio

[jailhouse](https://github.com/siemens/jailhouse) 支持跑Linux虚拟机，关于ARM硬件虚拟化的代码可以用来参考

[integrity multivisor](https://www.ghs.com/products/rtos/integrity_virtualization.html) 日本green hills公司面向物联网行业制作的虚拟机监控器

[NOVA Microhypervisor](https://hypervisor.org/)针对x86平台的虚拟机监控器， 来自学术界

[khypervisor](https://github.com/kesl/khypervisor)基于ARMv7的虚拟机监控器，已经停止更新

[Xvisor](https://github.com/xvisor/xvisor) 支持ARM系列平台，RISCV

[bao-hypervisor](https://github.com/bao-project/bao-hypervisor) 轻量级分区虚拟机监控器，支持ARMv8-A与RISC-V，正在开发阶段

### 虚拟机

[dockerrpi](https://github.com/lukechilds/dockerpi) 利用docker与qemu模拟rpi硬件

### 驱动

[uspi](https://github.com/rsta2/uspi)

[circle](https://github.com/rsta2/circle) 支持的驱动比较多

### 编译器

[How I wrote a self-hosting C compiler in 40 days](https://www.sigbus.info/how-i-wrote-a-self-hosting-c-compiler-in-40-days)讲述了作者在40天内实现一个C语言编译器的历程

[write-a-C-interpreter](https://github.com/lotabout/write-a-C-interpreter) 一个C语言编译器前端项目，赞的数量比较多

## 课程

[SJTU-SE-ICS](http://ipads.se.sjtu.edu.cn/courses/ics) **国内计算机教学top level课程**: 上海交通大学软件学院计算机系统基础课程

[SJTU-SE-CSE](https://ipads.se.sjtu.edu.cn/courses/cse) 上海交通大学软件学院计算机系统工程课程

[SJTU-SE-COMPILERS](https://ipads.se.sjtu.edu.cn/courses/compilers/) 上海交通大学软件学院编译原理课程

[SJTU-SE-OS](https://ipads.se.sjtu.edu.cn/courses/os/) 上海交通大学软件学院操作系统课程

[得克萨斯大学奥斯汀分校 CS378](https://www.cs.utexas.edu/~vijay/cs378-f17/) 虚拟化教学课程，课程项目是写一个pv vmm

[cs3210](https://github.com/sslab-gatech/cs3210-rustos-public) rust os, 被南大引入为课程lab

[tinykv](https://github.com/tidb-incubator/tinykv) pingcap 出品的分布式课程

[6.824分布式](http://nil.csail.mit.edu/6.824/2018/schedule.html)

[6.s081操作系统](https://pdos.csail.mit.edu/6.S081/2020/index.html)

## 论文

[Lightweight Virtualization on Microkernel-based Systems](https://os.inf.tu-dresden.de/papers_ps/liebergeld-diplom.pdf) 微内核架构中轻量级虚拟化，介绍的很详细，名字是Diplomarbeit， 发表于2010年

[Supporting KVM on the ARM architecture](https://lwn.net/Articles/557132/) 来自lwn社区

[分布式系统领域经典论文翻译列表](http://duanple.com/?p=170)

## 教程

[test-your-sysadmin-skills](https://github.com/trimstray/test-your-sysadmin-skills#simple-questions)

[db-readings](https://github.com/rxin/db-readings) 数据库领域论文列表，由浅入深

[TeachYourselfCS](https://github.com/keithnull/TeachYourselfCS-CN) Github上评价很高的自学教程，有中文翻译

[Writing an OS in Rust](https://os.phil-opp.com/) Rust 写操作系统

#### KVM

[KVM host in a few lines of code](https://zserge.com/posts/kvm/)

[kvm-kernel-example](https://github.com/david942j/kvm-kernel-example) 利用kvm实现虚拟机监控器

[kvm-hello-world](https://github.com/dpw/kvm-hello-world) kvm使用示例

#### SGX

[SGX 101](https://sgx101.gitbook.io/sgx101/) 学习 Intel SGX 的使用

## 工具

[elixir](https://elixir.bootlin.com/linux/latest/source) Linux源码阅读工具

## 文档

[Linux dts阅读说明](https://elixir.bootlin.com/linux/v4.3/source/Documentation/devicetree/bindings/arm/gic.txt)

[Linux启动流程](https://www.kernel.org/doc/Documentation/arm64/booting.txt)

[Linux设备驱动树](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/admin-guide/devices.txt)

[rosettacode](http://rosettacode.org/wiki/Read_entire_file#C.2B.2B)展示基本所有编程语言实现一个操作（比如读文件）所需要的代码，可以用来学习编程语言

## 书籍

[distributed systems for fun and profit](http://book.mixu.net/distsys/intro.html)

[OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/) 操作系统领域经典教材

系统虚拟化-原理与实现      很好的虚拟化教材，对x86平台虚拟化的设计，实现介绍的非常清楚。

[linux-insides](https://github.com/0xAX/linux-insides) 
