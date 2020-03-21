---
title: "如何用hugo搭建个人博客"
date: 2020-03-21T21:48:18+08:00
draft: false
---

# 首先先安装hugo
[官网有教程](https://gohugo.io/getting-started/installing)
## mac安装
* brew install hugo
* hugo version
## win安装
* 去[这个页面](https://github.com/gohugoio/hugo/releases)下载hugo_xxx_Windows-64bit.zip
* 解压，把hugo.exe放到一个目录
* 把该目录加到PATH
* 重启终端，运行hugo version查看版本
# 如何快速搭建博客
## 看文档高出网站
1. 进入[Hugo](https://gohugo.io/)官网，点击Quick Start凯苏开始
2. 从Step 2开始抄代码，直到Step 7
3. 得到一个public目录，这就是我们的博客站点
4. hugo server -D可以预览草稿
5. hugo server 可以预览非草稿
## 预览网站
1. 双击打开public/index.html发现不能预览
2. 因为public/index.html不能使用文件协议预览
3. 请使用hugo server预览