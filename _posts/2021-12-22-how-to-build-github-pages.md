---
layout: post
title: 如何在GitHub上搭建个人网站（github.io）
categories: 编程
description: 使用 GitHub Pages 搭建个人网站
keywords: GitHub Pages、github.io、个人网站
---

目前，想要搭建自己的博客、个人主页、在线简历、项目演示，大部分同学选择购买云服务器+域名，我也在阿里云购买了云服务器+域名，不过也有同学想要免费的服务，就可以使用 GitHub 提供的免费 Pages服务：`github.io`。

# 步骤

## 第一步：新建仓库

创建一个新的仓库，仓库名设置为如下格式：`账户名.github.io`
![](https://img.nanvon.cn/2022-0208-14:16:15:602.png)

## 第二步：添加文件

创建后，提示你导入项目，或者创建文件，这里为了简化操作，直接选择创建文件：
![](https://img.nanvon.cn/2022-0208-14:16:33:003.png)
输入文件名：`index.md`，并在里面写一点 Markdown 格式的文字：
![](https://img.nanvon.cn/2022-0208-14:15:00:246.png)
拉到下面直接提交即可：
![](https://img.nanvon.cn/2022-0208-14:14:55:950.png)

## 第三步：修改主题

打开 Settings 页面：
![](https://img.nanvon.cn/2022-0208-14:14:40:073.png)
点击 Pages，点击 Change Theme，选择自己喜欢的主题
![](https://img.nanvon.cn/2022-0208-14:14:23:481.png)
![](https://img.nanvon.cn/2022-0208-14:14:09:363.png)

## 第四步：等待

等待 1 到 5 分钟，在浏览器输入 `账户名.github.io`，比如我的网址就是`https://nanvon.github.io/`，应该就可以显示了。
![](https://img.nanvon.cn/2022-0208-14:13:56:084.png)

## 第五步：添加项目演示

将这个 git 仓库克隆到本地，将项目生成的 dist 目录下所有文件拷贝到该仓库，提交并推送，等待 1 到 5 分钟，刷新你的网站即可。

## 结尾

这个教程比较简单，喜欢折腾的同学可以自己探索怎么用其他的博客，比如 hexo，操作原理和上面讲的步骤五类似：将生成的网页文件提交到 GitHub 仓库就行。
喜欢 Markdown 的同学，使用 Markdown 即可，喜欢 HTML 的同学也可以使用 HTML。
单文件的话，把文件名改成index就行，GitHub 会自动识别的。如果想要添加多个文件，在仓库内添加文件夹并推送到远程仓库就行，访问的时候在域名后加上：`/文件名`，比如我的在线简历域名为：`https://nanvon.github.io/jianli/`。
