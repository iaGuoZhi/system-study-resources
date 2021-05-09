# 计算机系统学习资源

## 博客

[LoyenWang](https://links.jianshu.com/go?to=https%3A%2F%2Fwww.cnblogs.com%2FLoyenWang%2F) Linux（内核，PCI驱动），Kvm（中断虚拟化，virtio）源码分析讲的很清晰

[stdrc.cc](https://stdrc.cc/) 最佳计算机学习网站

## 项目

### 操作系统

[RT-Thread](https://github.com/RT-Thread/rt-thread) 实时操作系统

[Minos](https://github.com/minosproject/minos) 微内核实时操作系统，提供虚拟化支持

[swim](https://github.com/swimos/swim) 分布式microkernel

[rCore](https://github.com/rcore-os) RUST 操作系统

[SynestiaOS](https://github.com/SynestiaOS/SynestiaOS) 面向物联网的微内核操作系统，C语言编写，处于开发阶段

[armv8-bare-metal](https://github.com/NienfengYao/armv8-bare-metal) 针对ARMv8写的裸金属操作系统，代码很少，适合学习

### 虚拟机监控器

[ACRN](https://github.com/projectacrn/acrn-hypervisor) 嵌入式领域虚拟机监控器，intel开发，提供实时性，支持跑windows虚拟机，支持设备直通与virtio

[jailhouse](https://github.com/siemens/jailhouse) 支持跑Linux虚拟机，关于ARM硬件虚拟化的代码可以用来参考

[integrity multivisor](https://www.ghs.com/products/rtos/integrity_virtualization.html) 日本green hills公司面向物联网行业制作的虚拟机监控器

[NOVA Microhypervisor](https://hypervisor.org/)针对x86平台的虚拟机监控器， 来自学术界

[khypervisor](https://github.com/kesl/khypervisor)基于ARMv7的虚拟机监控器，已经停止更新

[Xvisor](https://github.com/xvisor/xvisor) 支持ARM系列平台，RISCV

[bao-hypervisor](https://github.com/bao-project/bao-hypervisor) 轻量级分区虚拟机监控器，支持ARMv8-A与RISC-V，正在开发阶段

### 驱动

[uspi](https://github.com/rsta2/uspi)

[circle](https://github.com/rsta2/circle) 支持的驱动比较多

## 课程

[SJTU-SE-ICS](http://ipads.se.sjtu.edu.cn/courses/ics) **国内计算机教学top level课程**: 上海交通大学软件学院计算机系统基础课程

[SJTU-SE-CSE](https://ipads.se.sjtu.edu.cn/courses/cse) 上海交通大学软件学院计算机系统工程课程

[SJTU-SE-COMPILERS](https://ipads.se.sjtu.edu.cn/courses/compilers/) 上海交通大学软件学院编译原理课程

[SJTU-SE-OS](https://ipads.se.sjtu.edu.cn/courses/os/) 上海交通大学软件学院操作系统课程

[得克萨斯大学奥斯汀分校 CS378](https://www.cs.utexas.edu/~vijay/cs378-f17/) 虚拟化教学课程，课程项目是写一个pv vmm

[cs3210](https://github.com/sslab-gatech/cs3210-rustos-public) rust os, 被南大引入为课程lab
## 论文

[Lightweight Virtualization on Microkernel-based Systems](https://os.inf.tu-dresden.de/papers_ps/liebergeld-diplom.pdf) 微内核架构中轻量级虚拟化，介绍的很详细，名字是Diplomarbeit， 发表于2010年

[Supporting KVM on the ARM architecture](https://lwn.net/Articles/557132/) 来自lwn社区

## 教程

### KVM

[KVM host in a few lines of code](https://zserge.com/posts/kvm/)

## 工具

[elixir](https://elixir.bootlin.com/linux/latest/source) Linux源码阅读工具

## 文档

[Linux dts阅读说明](https://elixir.bootlin.com/linux/v4.3/source/Documentation/devicetree/bindings/arm/gic.txt)

[Linux启动流程](https://www.kernel.org/doc/Documentation/arm64/booting.txt)

[Linux设备驱动树](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/admin-guide/devices.txt)