---
layout: post
title: "安装中文系统"
date: 2023-02-04 22:49:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 安装中文系统
---

## 注意事项

**此中文系统在我的掌握下非常安全，不会砖机。**

**如果你对此持怀疑态度或喜欢自己乱搞，那大可现在关闭此页面**

**我非常不喜欢有人搞NAND注入！我对因此情况造成的砖机概不负责！我对因此情况造成的砖机概不负责！**

<hr />

## 准备

- 确保Aroma和Tiramisu正常运行 

- 从中文系统发布链接中下载对应区域的中文系统：
  - [https://wwi.lanzouo.com/b00pdmi2b](https://wwi.lanzouo.com/b00pdmi2b) 密码:ae8a

<hr />

## 开始

### Aroma（开机自动挂载）

1.将你下载的中文系统的压缩包解压，并把**SDcafiine**和**wiiu**文件夹放入SD卡根目录，然后将**SDcafiine**复制到**wiiu**文件夹中

2.启动主机，此时会询问你加载modpack，**请对CHJSystem~~或CHSSystem~~按下A键**

3.进入主菜单后同时按下 **L+十字键下+SELECT(-)** 后在菜单中找到**SDCafiine Plugin**

4.在**settings**与**Advanced settings**中将所有选项均改为**true**

<hr />

### Tiramisu（HBL）

> **需注意此方法进行挂载在进入主机设置和Mii工作室以及重启主机以后会自动失效，部分软件也会受限！**

1.将你下载的中文系统的压缩包解压，并把**SDcafiine**和**wiiu**文件夹放入SD卡根目录

2.打开HBL，并找到SDcafiine这个软件，点击选中，然后点Load，请等待自动返回Wii U菜单


#### Tiramisu开机自动挂载（非常不建议使用！）

> **此功能与Mii工作室冲突！会出现一打开Mii工作室就返回桌面的情况！并且会占用HBL，请再下载一个WUP版的HBL并安装完后再做这个！**

请注意：你不需要做[疑难解答中的选择保留HomeBrewlauncher](https://wiiu.1919810.com/wiiu/2023/02/05/QA.html#tiramisu%E5%B8%B8%E8%A7%81%E9%94%99%E8%AF%AF)

1.将sd:/wiiu/apps/sdcafiine/sdcafiine.elf重命名为Homebrew_launcher.elf

2.把此文件放在sd:/wiiu/apps/Homebrew_launcher文件夹内并替换文件

3.在Wii U启动时按住 + (Start)，使用十字键选择Homebrew Launcher按Y选为自动启动，并按A启动到Wii U菜单。

> 需要使用Mii工作室的时候（例如创建账号绑定Mii，更改机主Mii的模样），需要将储存卡拔出主机
