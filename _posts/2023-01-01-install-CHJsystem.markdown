---
layout: post
title: "安装中文系统"
date: 2023-02-04 22:49:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 安装中文系统
---

## 前言

当走完Tiramisu教程后，现在你的主机已经安装了PayloadLoader、Environment Loader 和 Tiramisu。

现在将为Wii U安装日文字库里面的汉字所组成的中文系统了

此中文系统在我的掌握下非常安全，不会砖机；如果你还是不想，可以现在关闭此页面

<hr />

## 准备

- 从中文系统发布链接中下载对应区域的中文系统
> [https://wwi.lanzouo.com/b00pdmi2b](https://wwi.lanzouo.com/b00pdmi2b) 密码:ae8a

<hr />

## 开始

1.将你下载的中文系统的压缩包解压，并把**SDcafiine**和**wiiu**文件夹放入SD卡根目录

2.打开HBL，并找到SDcafiine这个软件，点击选中，然后点Load，请等待自动返回Wii U菜单

3.汉化完成，试试效果

<hr />

## Aroma开机自动挂载（建议！）

将SDcafiine放入wiiu文件夹后并启用Aroma SDcafiine的自动挂载功能即可

## 开机自动挂载（非常不建议使用！）

> **此功能与Mii工作室冲突！会出现一打开Mii工作室就返回桌面的情况！并且会占用HBL，请再下载一个WUP版的HBL并安装完后再做这个！**

请注意：你不需要做[疑难解答中的选择保留HomeBrewlauncher](https://wiiu.1919810.com/wiiu/2023/02/05/QA.html#tiramisu%E5%B8%B8%E8%A7%81%E9%94%99%E8%AF%AF)

1.将sd:/wiiu/apps/sdcafiine/sdcafiine.elf重命名为Homebrew_launcher.elf

2.把此文件放在sd:/wiiu/apps/Homebrew_launcher文件夹内并替换文件

3.在Wii U启动时按住 + (Start)，使用十字键选择Homebrew Launcher按Y选为自动启动，并按A启动到Wii U菜单。

- 需要使用Mii工作室的时候（例如创建账号绑定Mii，更改机主Mii的模样），需要将储存卡拔出主机

> **请注意，请不要把中文系统注入NAND！这可能会出现很多麻烦，甚至砖机！为了你主机的安全，我建议你使用完全外挂，因为这样不会伤害到你的主机！**
