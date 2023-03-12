---
layout: post
title: "OPPOWatch3删除更新"
date: 2023-02-04 21:43:00 +0800
categories: ow3
tags: adb ow3
img: https://s1.ax1x.com/2023/03/13/ppMox9s.jpg
describe: OPPOWatch3删除更新
---

## 前言

**这不是wiiu教程，这也不是降级教程，仅为学习记录**

你说的对，但《OPPO Watch 3 Pro》是由OPPO自主创立的一款全新智能手表。在这里，被lubia选中的人将被授予「表皇」，导引安卓表皇之力。你将扮演一位名为「Color OS For Watch」的神秘角色，在自由的互盆中学会怎么看性格各异、能力独特的穿戴用户们，寻求志同道合的同伴－手表温度过高，将自动关闭移动数据，和他们一起科技生活，找回失散的亲人——「读取应用列表」。同时，逐步发掘「闪屏」的真相。

ow3禁用了读取软件列表，所以无法用常用的方法去清除数据

### adb安装

请前往百度、必应等搜索引擎百度一下“adb如何安装”

### 开启USB调试

打开设置-关于手机-版本号，连点五次版本号就行了，返回设置

### 获取包名

打开手表更新界面，输入以下命令：
*adb shell dumpsys window w |findstr \/ |findstr name=*

重点查看后三行：
msurface＝surface(name＝com.heytap.wearable.ota...)

获取到包名后输入adb shell pm clear com.heytap.wearable.ota

上面这串命令是清除数据，把系统更新软件的数据清除后，下载的系统更新会一并删除