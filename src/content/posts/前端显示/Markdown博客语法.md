---
title: Markdown博客语法               #标题
description: Markdown语法和博客独特语法 #描述
draft: false                         #草稿未发布
published: 2025-12-04                #发布时间
updated: 2025-12-05                  #更新时间
pinned: false                        #置顶
tags: [Blog, Markdown, Grammar, Syntax]    #标签
category: "前端显示"                  #类别（使用文件夹名称）
slug: Markdown博客语法                #自定义链接（使用标题名称）

# sourceLink: ""                    #原链接
author: Alan_xxk                    #作者
licenseName: "CC BY-NC-SA 4.0"      #许可证名称
image: "api"                        #随机封面 “image: ./cover.jpg”
# date: 2025-12-04                  #创建时间(无显示)
---

# 0.目录
- [0.目录](#0目录)
- [1.Markdown语法](#1markdown语法)
  - [1.1.原理](#11原理)
  - [1.2.语法](#12语法)
    - [1.2.1.正文](#121正文)
    - [1.2.2.跳转](#122跳转)
    - [1.2.3.列表](#123列表)
    - [1.2.4.结构](#124结构)
    - [1.2.5.图片](#125图片)
    - [1.2.6.表格](#126表格)
    - [1.2.7.特殊](#127特殊)
- [2.Firefly框架语法](#2firefly框架语法)
  - [2.1.隐藏文本](#21隐藏文本)
  - [2.2.提醒框](#22提醒框)
  - [2.3.代码块美化](#23代码块美化)
  - [2.4.其他文章链接](#24其他文章链接)
  - [2.5.Github仓库卡片](#25github仓库卡片)
  - [2.6.在线视频](#26在线视频)

# 1.Markdown语法
- 菜鸟教程：https://www.runoob.com/markdown/md-tutorial.html
## 1.1.原理
- Markdown是HTML的简化版本，本质上是Markdown源码通过解析器转换成HTML，浏览器从而能渲染出画面
## 1.2.语法
### 1.2.1.正文
- 换行：双空格+换行
- 缩进：Tab
- 段落：空行
- 上标：^
- 下标：~
- 斜体：*
- 粗体：**
- 粗斜：***
- 标记：`
- 高亮：==
- 删除线：~~
- 下划线：\<u>\</u>
### 1.2.2.跳转
- 字链：[]( "") 或 [][]+[]: ""
- 址链：<>
- 脚注：[\^]+[\^]:
- 跳转：\[]\(#) —— [1.2.语法](#12语法)
### 1.2.3.列表
- 勾选：- [x]
- 圆点：-
- 数字：1.
- 嵌套：双空格
### 1.2.4.结构
- 标题：#
- 引用：>
- 分割线：---
- 代码：```
- 代码下划线：+
- 代码删除线：-
### 1.2.5.图片
- 图片：\!\[]( "") 或 \<img src="" alt="" width="%">
- 图廊：\<div style="display: flex; justify-content: space-around; flex-wrap: wrap;">\</div>
- 图链：\[!\[]( "")]()
### 1.2.6.表格
- 单元格：|
- 分隔：---
- 对齐：:--- 或 :---: 或 ---:
### 1.2.7.特殊
- 转义：\
- 按键：\<kbd>\</kbd>
- 公式：\$ 或 \$\$ 或 \$\$ \\\
- 流图：\```mermaid```
- 徽章：\[\!\[]\(https://img.shields.io/badge/--?logo=)]() —— [![](https://img.shields.io/badge/Icon-图标库-blue?logo=simpleicons)](https://simpleicons.org/)
---
# 2.Firefly框架语法
## 2.1.隐藏文本
```markdown
:spoiler[]
```
## 2.2.提醒框
```markdown
:::note/tip/important/warning/caution[]
:::
```
```markdown
> [!NOTE/TIP/IMPORTANT/WARNING/CAUTION]
```
## 2.3.代码块美化
```markdown
\```ansi/bash/powershell/sh/ps  #独特外框
\```ansi frame="none"           #取消外框
\```cpp title=""                #添加标题
\```cpp del={2} ins={3-4} {6}   #码行高亮
\```diff  lang="cpp"            #码行高亮
\```cpp {"1":5} del={"2":7-8} ins={"3":10-12}   #标签数字
\```cpp {"1. Provide the value prop here:":5-6} #标签文本
\```cpp "" 或 ins="" 或 del=""  #文本高亮（还有正则表达式和转义正斜杠）
\```cpp wrap=true               #换行显示
\```cpp wrap=true preserveIndent=true           #缩进显示
\```cpp collapse={1-5, 12-14, 21-24}            #折叠显示
\```cpp showLineNumbers=true    #行号显示
\```cpp showLineNumbers=true startLineNumber=5  #起始行号
```
## 2.4.其他文章链接
```html
<a href="/posts/my-first-post/">我的第一篇文章</a>
```
```html
<ul>
    <li><a href="/posts/my-first-post/">我的第一篇文章</a></li>
    <li><a href="/posts/my-second-post/">我的第二篇文章</a></li>
    <li><a href="/posts/my-third-post/">我的第三篇文章</a></li>
</ul>
```
## 2.5.Github仓库卡片
```markdown
::github{repo="Alanxxk/Astro-Source-Website"}
```
## 2.6.在线视频
```markdown
<iframe width="100%" height="468" src="//player.bilibili.com/player.html?isOutside=true&aid=&bvid=&cid=&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" &autoplay=0></iframe>
```
```markdown
<iframe width="100%" height="468" src="" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```
