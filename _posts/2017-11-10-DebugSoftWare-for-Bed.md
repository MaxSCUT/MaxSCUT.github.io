---
layout: post
title:  "床垫调试器程序的设计"
date:   2017-11-10 11:29:00
categories: coding4fun
tags: [Qt,Sketch,Software]
---
软件:QT5.9,Sketch  
通讯方式:UDP  
下位机:STM32控制器(UCOS)  
<!-- more -->

看了很久的dribble大神的作品,终于有机会自己从UI设计开始一款软件了.这个软件的作用就是和下位机通讯,然后控制层叠起来的床垫机,取出和放入床垫.主要用在商场等场合.  
软件登陆界面:  
![login](https://user-images.githubusercontent.com/2595085/34712703-b5cffd9e-f55e-11e7-86b3-cbfad310bda2.jpg)
电子开关控制界面:  
![switch](https://user-images.githubusercontent.com/2595085/34712701-b59f3dee-f55e-11e7-9964-938bc2448ba7.png)
电机控制界面:  
![motor](https://user-images.githubusercontent.com/2595085/34712704-b60007dc-f55e-11e7-8457-47e5adbd83ed.png)
层高设置界面:  
![layerheight](https://user-images.githubusercontent.com/2595085/34712705-b6326baa-f55e-11e7-895a-6bb25d1507be.png)
门挡高度设置界面:  
![doorheight](https://user-images.githubusercontent.com/2595085/34712706-b662eb22-f55e-11e7-9314-3f738869b9f5.png)
出入库控制界面:  
![store](https://user-images.githubusercontent.com/2595085/34712709-b697a57e-f55e-11e7-927c-5896366a7e3e.png)


参考资料:  
[1][Dribbble](https://dribbble.com/)  
    ->没有特定哪个,算是这里拿一点,那里取一点,再加点自己的想法做出来的UI界面.  
[2][Sketch中文网](http://www.sketchcn.com/)  
    ->入门Sketch的好去处  
[3][Qt Documentation](http://doc.qt.io/)  
    ->用别人的库还是看别人的help文档吧
