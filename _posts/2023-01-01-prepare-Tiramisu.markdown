---
layout: post
title: "Tiramisu——准备破解"
date: 2023-02-05 12:40:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s1.ax1x.com/2022/11/26/zN87dO.jpg
describe: Tiramisu——准备破解
---

## 准备破解

<hr />

## 卸载过时的破解

**请在安装Tiramisu前卸载之前安装的旧破解**

[卸载CBHC](https://wiiu.1919810.com/wiiu/2023/02/01/uninstall-CBHC.html)

[卸载Indexiine](https://wiiu.1919810.com/wiiu/2023/02/01/uninstall-indexiine.html)

卸载Haxchi只需要打开主机设置，选择数据管理进行删除就好了

- **但是请不要这样卸载CBHC**，如果你~~脑抽~~这样删除了CBHC，你的机器只能通过之前的备份恢复（需要焊接技能），或者使用USB漏洞（需要支持设备）。

- 如果你想保留Haxchi，请看[Haxchi与Tiramisu共存](https://wiiu.1919810.com/wiiu/2022/10/28/Save-Haxchi.html)

如果你一直使用网页破解，也就是在线漏洞（**不是打开浏览器自动破解的indexiine！**），那可以继续此教程

## 准备SD卡

将储存卡格式化为FAT32（如果你之前拥有别的破解，请不要格式化！）

- [64G储存卡可能需要其他工具进行格式化为FAT32](https://zhidao.baidu.com/question/313838908478081124/answer/4207170040.html)

#### 从这里下载你需要的文件：

- 外网直链：[tiramisu.foryour.cafe](https://tiramisu.foryour.cafe/)
  - 点击**Download Tiramisu**
- [最新的**01_sigpatches.rpx**](https://github.com/marco-calautti/SigpatchesModuleWiiU/releases/tag/1.2)
  - （请下载 01_sigpatches.rpx并放在SD://wiiu/environments/tiramisu/modules/setup）

- 若无法下载请挂梯

**解压文件并放到储存卡根目录，如果需要替换文件请选择替换**

如果一切步骤正常，那么应该只有wiiu文件夹被更新了！

![SD卡文件](https://s1.ax1x.com/2022/03/28/qDj62V.png)

## 浏览器漏洞

**请确保你的主机可以连接至互联网，再进行以下步骤**

[怎么给我的Wii U主机联网](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1126)

1.把SD卡从电脑中弹出并插入Wii U主机。

2.打开Wii U的网络浏览器，然后访问 [wiiuexploit.xyz](https://wiiuexploit.xyz) 网站。
- 备用网站：

  - [littlefive233.github.io/LoveU/](https://littlefive233.github.io/LoveU/)

  - [u.wiidb.de](u.wiidb.de)

3.点击 **_5.5.X Exploit!_** ，等待新的页面打开后点击 **_Run Exploit!_** 并按住**B键**，直到见到菜单才可以松开。
- 如果你的Wii U卡住或者白屏了，请稍等。如果什么都没有出现，请长按**主机**电源键4秒或更长直至红灯来强制关机，重启后到浏览器设置里[重置浏览器保存的数据](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1507/~/how-to-delete-the-internet-browser-history)，然后再试一次。

## [以上步骤全部完成后点我继续（制作NAND备份）](https://wiiu.1919810.com/wiiu/2022/02/04/Dump-NAND.html)
