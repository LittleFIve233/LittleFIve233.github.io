---
layout: post
title: "解除阻止系统更新"
date: 2023-02-02 07:40:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 解除阻止系统更新
---

# 解除阻止系统更新

## 开始

如果你需要进行系统更新，则需要按以下步骤移除屏蔽更新

<hr />

## 移除屏蔽更新

1.开机（如果没有自启动则打开安全使用须知）按住+键进入AutobootModule选择界面

2.在AutobootModule同时按住+键和-键直到显示Update Unblock!

3.[移除自启动PayloadLoader](https://wiiu.1919810.com/wiiu/2023/02/01/uninstall-PayloadLoader.html)

## 如果是旧的破解无法使用AutobootModule的方法

> 这个阻止更新的办法比使用DNS屏蔽更加高级，需要使用一个自制程序来修改系统文件。且eShop的功能不会受到限制。

1.下载 [UDFiine](https://wiiubru.com/appstore/zips/UFDiine.zip) 并解压到你的储存卡根目录，如果提示覆盖文件，请选择覆盖文件

2.将储存卡插回Wii U并开机。

3.打开HBL并找到UDFiine

4.按下A恢复更新文件夹并确认它的提示。
- 你现在不再阻止系统更新了。Update folder exists

## 解除DNS屏蔽

进入Wii U的系统设置，依次打开：Internet（网络）> Connect to the Internet（连接至网络）> Connection List（接入点列表）>Your WiFi connection（你的WiFi接入点）> Change Settings（更改设定）> DNSAuto-obtain（自动获取）
