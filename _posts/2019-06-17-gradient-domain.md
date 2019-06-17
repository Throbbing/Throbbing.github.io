---
layout: post
title: "基于梯度域渲染方法的分析 (表面) "
subtitle: "Gradient Domain based rendering"
author: "ls"
header-img: "img/post-gradient-cover.jpg"
header-mask: 0.2
tags:
  - Web
  - Flash
---

[toc]

#梯度域方法概述
梯度域方法是一种“降噪”方法，其主要目的是加快基于MonteCarlo采样的收敛效率，基于梯度域的方法主要通过以下流程实现：
1. 计算初始图像
2. 计算梯度图像
3. 对初始图像和梯度图像进行图像重构
4. 得到最终结果
其具体例子可见图1


![图1](2019-06-17-gradient-domain/1.png)

#关于基于梯度域方法的三大要素
##初始渲染算法
初始渲染算法决定了路径的生成和初始图像的计算
##Shift函数
Shift函数决定如何根据Base Path来生成Offset Path
##雅可比行列式
雅可比行列式用来矫正在Offset Path相对于Base Path的路径密度改变

#Shift函数

#不同算法中Shift函数的应用以及具体调整

#雅可比行列式

#Shift函数的开销和对比


#GD- 算法分析


#可研究点