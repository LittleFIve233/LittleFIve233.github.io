---
layout: post
title: "安装PayloadLoader"
date: 2023-02-05 10:39:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 安装PayloadLoader
---

## 介绍

PayloadLoader为加载Aroma/Tiramisu的重要前置，则无法继续做后面的教程

- 安装PayloadLoader将可以运行安全使用须知软件来访问Tiramisu。

**_请注意：初始化主机不会卸载注入的PayloadLoader。如果需要卸载，请按照[卸载PayloadLoader](https://wiiu.1919810.com/wiiu/2023/02/01/uninstall-PayloadLoader.html)删除PayloadLoader。_**

## 浏览器漏洞

>**请确保你的主机可以连接至互联网，再进行以下步骤**
>[怎么给我的Wii U主机联网](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1126)

1.把SD卡从电脑中弹出并插入Wii U主机。

2.打开Wii U的网络浏览器，然后访问 [u.wiidb.de](https://u.wiidb.de) 网站。

>备用网站：
>[littlefive233.github.io/LoveU/](https://littlefive233.github.io/LoveU/)

3.点击 **HAXX**

- 如果你的Wii U卡住或者白屏了，请稍等。如果什么都没有出现，请长按**主机**电源键4秒或更长直至红灯来强制关机，重启后到浏览器设置里[重置浏览器保存的数据](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1507/~/how-to-delete-the-internet-browser-history)，然后再试一次。

>如果你以前安装过indexiine然后格式化存储卡导致进入浏览器就死机可以[尝试DNSpresso](https://wiiu.1919810.com/wiiu/2023/02/05/DNSpresso.html)

## 安装PayloadLoader

1.进入蓝色页面的Payloadloader后，
> 如果一起做了Tiramisu，则会在Payloadloader中看见installer，此时也可以使用这个installer安装payloadloader
>（如果使用此installer则直接跳到第4步）

2.请选择进入aroma，稍后将进入WiiU Menu
- 如果进入了AutobootModule则选择WiiU Menu

3.找到payloadloader_installer并打开它

4.按选择check按A键检查你是否可以安装PayloadLoader
- 它应该会告知你PayloadLoader能够安装到安全使用须知软件

3.使用 十字键 选择Install并按A键进行安装

4.在安装完成后，继续按A键关闭主机

## 设置自启动PayloadLoader

**如果你不想自启动破解，请跳过本大步并直接进行下一步**

1.启动WiiU，等待返回桌面

2.按住X键并点击安全使用须知，你将进入EnvironmentLoader

3.使用十字键将光标移动到installer并按A进入。

4.选择Check并按下A键，它将会再次检查

5.选择Boot options，它将会问你是否切换默认启动项，选择Switch to PayloadLoader即可。

6.当进程结束后，按下A键关闭主机

## [以上步骤全部完成后点我继续至安装CFW](https://wiiu.1919810.com/wiiu/2023/02/05/Hack.html)
