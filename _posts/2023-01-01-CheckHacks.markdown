---
layout: post
title: "检查Wii U破解"
date: 2023-02-04 16:00:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 检查破解
---

## 前言

该教程将检查你主机所安装的CFW，它们无疑就只有三种，检查它们的方法也非常简单

**请注意：如果以下三种都没有检查出来那就是未破解状态**

<hr />

## Aroma＆Tiramisu

### 简介

Aroma无疑是现在最好的CFW了，它拥有插件加载器，它还是tiramisu的升级版，继承了一切来自tiramisu的好处，例如无需花钱无需担心初始化系统砖机，它们的前置叫payloadloader，以下方法用于检查payloadloader的安装状态

#### 检查payloadloader

如果没有自启动payloadloader则是通过安全与健康程序运行CFW的，所以如果你的安全使用须知软件（黄色感叹号）打开后会自动返回Wii U菜单或者打开一些界面而不是安全健康介绍，代表着你没有做自启动payloadloader，而payloadloader则已被安装到安全使用须知

自启动payloadloader在开机时就已经启动了，打开安全与健康会显示*DO NOT RUN EXPLOIT TWICE……*，其他的办法可以在开机时按住Start(+)或者是X键就能进入payloadloader选择界面或autobootmodule选择界面

<hr />

## Haxchi&CBHC（脑锻炼破解固化）

### 简介

Haxchi可能是大部分折腾玩家或是一劳永逸的玩家的首选，因为Haxchi可以更为CBHC，在开机时进行冷启动以省去不少时间打开CFW

#### 检查Haxchi&CBHC

检查CBHC很简单，在开机时会有Autobooting的黑屏画面，这就是CBHC，还可以通过看数据管理主机储存里有没有一个叫Don't touch me的软件。**！当你不知道干什么时，千万不要删除这个软件！**

检查Haxchi可以去看桌面，一般的Haxchi就是一个写着Haxchi的软件，不过，商家一般会把它的启动图标和启动画面改了，一般叫“一键破解”，这个就是haxchi

<hr />

## Mocha&Indexiine（浏览器破解固化）

### 简介

Mocha是大部分不想去购买DSVC的玩家的普遍选择，通常这些玩家~~以及商家~~会去做Indexiine来节省打开CFW的时间

#### 检查Mocha&Indexiine

检查Mocha比上面说的CBHC更简单了，你可以打开在启动网页破解的时候打开你自己安装的游戏，可能会跳出199-9999的错误，这就是还没启用Mocha CFW

检查Indexiine同样很简单，在打开浏览器后（需要在首页而不是其他页面）等上几秒，看下是不是自动跳转到HBL或是其他的自制程序里或者自动卡死浏览器，是就代表你安装了Indexiine
