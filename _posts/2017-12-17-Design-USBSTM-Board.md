---
layout: post
title:  "USBSTM板的设计"
date:   2017-12-18 11:29:00
categories: boardDesign
tags: [STM32,USB,Hardware]
---
软件:Altium Designer 18  
主要芯片:STM32F407,USB3300  
![usbstm](https://user-images.githubusercontent.com/2595085/34708921-f56d7706-f54f-11e7-8b79-1fcfb7c51910.png)

<!-- more -->

基于STM32和USB3300设计了一款小的测试版,以后在别的地方(智能家居)可能会用到,故参照[STM32F4xx+USB3300实现高速USB数据传输，单片机程序及PC驱动程序源码分享](http://www.embed-net.com/thread-171-1-1.html) 帖子的思路,用AD布了一块板.经过测试,读取数据的速度可以达到32MB/s.

焊接完成后,用STM32CubeMX产生普通的CDC_USB Device 模板,根据[USB枚举过程分析](https://maxscut.github.io/coding4fun/USB-enumeration-process.html)修改模板,上位机用Qt基于libusb库来进行通讯.
