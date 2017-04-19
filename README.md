# QEMU 模拟 Cortex-A9 运行 U-boot 和 Linux

Made with ❤️ by APRICITY

【尚在施工中…会尽快完成】

【现在可以点击左侧导航来进入相应章节】


## 环境说明

本文使用的发行版是 XUbuntu 16.04.2 LTS，虚拟化软件是 VirtualBox。
如果你使用的是原版 Ubuntu，也没有关系，它们只是桌面环境长得不一样而已。


## 在开始之前…

我对于工作目录（也就是文件夹）的安排见这里：[工作目录安排](appendix/workspace-structure.md)

如果你对 Unix 命令行还不是很熟悉，可以看这里：[熟悉命令行](appendix/intro-commandline.md)


## 修订历史（最新的在最前）

* **【2017-04-19】** 更换内核版本为长期支持版（4.10.5 stable -> 4.9.23 LTS）。
* **【2017-04-19】** 将下载地址换为国内（我在 Coding.net 上的一个仓库）。
* **【2017-04-19】** 增加使用 `apt` 安装虚拟机附加程序的说明。