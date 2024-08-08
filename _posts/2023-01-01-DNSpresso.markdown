---
layout: post
title: "通过DNSpresso安装破解"
date: 2023-02-05 10:38:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 通过DNSpresso安装破解
---

## 注意：如果你在中国大陆，可能部分情况受到运营商影响，所以建议不要首选使用此方法！

## 准备文件

请准备Aroma或者Tiramisu的文件

*若无法下载请挂梯*

- **以下CFW文件可以二选一不用全部下载**

- [aroma.foryour.cafe](aroma.foryour.cafe)

  - 将四个警示都打钩后，选择主要内容下载：请下载Base的所有内容、Aroma、以及除了USB Serial logging模块其他模块都要下载

  - 把压缩包中的wiiu文件夹依次放入WiiU SD卡中的根目录

- [aroma.foryour.cafe](aroma.foryour.cafe)

  - 请点击Download Tiramisu，并将下载好的压缩包中的wiiu文件夹放入根目录

请下载[PayloadFromRPX](https://github.com/wiiu-env/PayloadFromRPX/releases)

- 将root.rpx重命名为launch.rpx放入WiiU存储卡根目录

## 破解

**请确保你的主机可以连接至互联网，再进行以下步骤**

[怎么给我的Wii U主机联网](https://en-americas-support.nintendo.com/app/answers/detail/a_id/1126)

**有线网络也可以使用此方法**

1.打开主机设置-网络-连接到网络

- 我推荐设置两个接入点，首个用于连接网络，后者用于破解

- 如果您已保存接入点，请新建一个接入点后，按X打开接入点列表

2.选择第二个接入点，继续选择变更设置

3.在DNS选择不自动获取，并在主DNS输入

- **85.215.57.182**

4.按B保存

- 如果问是否设定为默认接入点，请选择否

- 如果问是否进行连接测试，请选择否

5.在变更设置，删除设置，连接测试的列表中选择连接测试

6.你的主机在连接到互联网时会卡住，别担心，这是正常的，卡死过后会出现黑色界面，紧接着就进入了Payloadloader

## [接下来请按照此方法继续](https://wiiu.1919810.com/wiiu/2023/02/05/Payloadloader.html#%E5%AE%89%E8%A3%85payloadloader)