---
title: Vscode配置Python运行环境
date: 2021-07-16 09:31:13
updated: 2021-07-17 09:04:39
tags: 
    - 技术 
    - 安装
description: 使用Vscode而非Pycharm运行使用python
author: 元华啊
email: 744503584@qq.com
readmore: true #显示更多
comments: true
categories: 
    - python
#hide:index #只在首页隐藏，归档中显示
reward: false #是否开启打赏
---

# 前言
VScode是一个相当优秀的IDE，具备开源、跨平台、模块化、插件丰富、启动时间快、颜值高、可高度定制等等优秀的特质，不愧是微软爸爸的私生子。
Vscode虽然是一个文本编辑器，但是在安装不同的插件后，就可以有相当多的工程。
所以用VScode来编写Python，也是相当的好用的。
所以，今天我们就来讲讲，怎么在VScode上配置Python开发环境。

# 软件准备
首先，我们必须先下载好Python的安装包和VScode的安装包。
下载地址如下：
[Python下载](https://www.python.org/downloads/)
[VScode下载](https://code.visualstudio.com/)
大家选择适合自己的版本下载即可。

本文中所用的系统是win11预览版，选择版本为python3.9.6.

# 软件安装

## 安装python
在安装过程中切记勾选添加环境变量

### 安装第三方的包
    python #检查python版本
    import this #欣赏python之禅
    exit() #退出
    pip list #检查第三方的包
    pip install --user flake8 #下载安装flake8
    pip install --user yapf #下载安装yapf

![检查配置的Python](https://cdn.jsdelivr.net/gh/yuanhuaa/images@master/images-cage/检查配置的Python.70att70nipg0.png)

## 安装Vscode
从官网上下载好安装包后，一路NEXT就好了。
（所以我本章到底要讲啥呢，水了这么几个步骤，主要还是下面最关键咯）

# 配置Vscode

## 安装python插件
- 1.打开Vscode，按快捷键`Ctrl+Shift+X`，进入插件管理页面。
- 2.在搜索栏中输入python
- 3.选择插件，点击安装。
  
![Vscode安装插件python](https://cdn.jsdelivr.net/gh/yuanhuaa/images@master/images-cage/Vscode安装插件python.5y6xg4nirv40.png)

# 总结
基本上Vscode安装Python步骤到此就结束了，下一更开始将会开始Python语言的基础学习。

什么？你说我这篇博客啥都没写？的确啊，我就是在水，略略略🤷‍♂️