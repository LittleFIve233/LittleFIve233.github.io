---
layout: post
title: "卸载indexiine"
date: 2023-02-02 02:40:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 卸载indexiine
---

## 卸载indexiine

indexiine，都被大多数玩家~~和奸商~~称为网页固化，是替换了Wii U浏览器默认的加载网页来让它加载浏览器完毕后直接启动网页漏洞，现在我们有了Tiramisu，那么就可以抛弃它了

<hr />

### 准备

[请准备TiramisuCFW（必须Tiramisu）](https://wiiu.1919810.com/wiiu/2023/02/05/prepare.html)

[下载indexiine installer](https://github.com/GaryOderNichts/indexiine-installer/releases)

<hr />

### 开始

0.将下载的indexiine-installer.zip解压并将wiiu文件夹放入根目录，需要替换则选择替换

1.进入Tiramisu选择Mii工作室（6个Mii图标的软件）

2.选择indexiine-installer后点Load

3.按下B卸载安装的indexiine（切记一定不要重新安装！）

- 如果失败表示没有Backup-index.html，请使用下方链接中的文本创建backup-index.html文件

  - [backup-index.html](https://github.com/LittleFIve233/LittleFIve233.github.io/blob/master/Backup-index.html) 将所有内容全选后复制，然后创建一个新文本文档命名为backup-index.html，并放到SD/wiiu/apps/indexiine-installer/文件夹中

4.退出HBL并检查打开浏览器是否还会自动执行漏洞或者卡死

> 如需恢复系统更新，[请点击这里继续](https://wiiu.1919810.com/wiiu/2023/02/01/uninstall-UDFiine.html)
