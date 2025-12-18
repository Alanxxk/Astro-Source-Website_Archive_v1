---
title: Github主页美化                #标题
description: Github个人主页添加图片信息美化显示 #描述
draft: false                        #草稿未发布
published: 2025-12-15               #发布时间
updated: 2025-12-15                 #更新时间
pinned: false                       #置顶
tags: [Github, Profile, Graph, Chart]   #标签
category: "前端显示"                 #类别（使用文件夹名称）
slug: Github主页美化                 #自定义链接（使用标题名称）

sourceLink: "https://github.com/Alanxxk"    #原链接
author: Alan_xxk                    #作者
licenseName: "CC BY-NC-SA 4.0"      #许可证名称s
image: "api"                        #随机封面 “image: ./cover.jpg”
# date: 2025-12-15                  #创建时间(无显示)
---

<img src='https://www.gitclear.com/snap_changelogs/229cc023-f4a6-4d27-a111-31e19a79c7d9.png' />

# 0.目录
- [0.目录](#0目录)
- [1.美化方法](#1美化方法)
- [2.简单调用（Markdown）](#2简单调用markdown)
  - [2.1.波浪横幅](#21波浪横幅)
  - [2.2.打字机](#22打字机)
  - [2.3.图标](#23图标)
  - [2.4.访客数量徽章](#24访客数量徽章)
  - [2.5.各种徽章](#25各种徽章)
  - [2.6.数据统计](#26数据统计)
  - [2.7.连续贡献天数](#27连续贡献天数)
  - [2.8.Github活跃曲线](#28github活跃曲线)
  - [2.9.网站数据](#29网站数据)
  - [2.10.Github仓库收藏曲线](#210github仓库收藏曲线)
  - [2.11.访客数量图片](#211访客数量图片)
  - [2.12.访客旗帜（不推荐使用—因出现台湾旗）](#212访客旗帜不推荐使用因出现台湾旗)
  - [2.13.名言引用](#213名言引用)
  - [2.14.学习网站徽章](#214学习网站徽章)
  - [2.15.Github仓库图片显示](#215github仓库图片显示)
  - [2.16.图片存储](#216图片存储)
  - [2.17.HTML居中语法](#217html居中语法)
- [3.复杂调用（Github Action或其他）](#3复杂调用github-action或其他)
  - [3.1.贡献热力图—贪吃蛇视图（未完结）](#31贡献热力图贪吃蛇视图未完结)
  - [3.2.贡献热力图—2D+3D（未完结）](#32贡献热力图2d3d未完结)
  - [3.3.信息统计（未完结）](#33信息统计未完结)
  - [3.4.编程时间（未完结）](#34编程时间未完结)
  - [3.5.RSS同步显示标题（未完结）](#35rss同步显示标题未完结)
  - [3.6.Github仓库贡献人员显示（未完结）](#36github仓库贡献人员显示未完结)
  - [3.7.贡献热力图—3D打印（未完结）](#37贡献热力图3d打印未完结)
  - [3.8.赞助按钮（需有港澳或境外银行卡）（未完结）](#38赞助按钮需有港澳或境外银行卡未完结)
- [4.模板](#4模板)


# 1.美化方法
1. ***简介***：在Github个人主页的左侧栏，可以编辑自己的个人信息
2. ***创建***：在Github创建仓库，输入与自己同名名称，可选输入描述，勾选“Public”,勾选“Add a README file”，点击“Create repository”按钮，在仓库Read.me编写内容即可显示在个人主页中，更高级功能还需配置仓库中的Github Action
3. ***快法***：[Metrics](https://metrics.lecoq.io/)（备用网站:[Profilinator](https://profilinator.rishav.dev/) 或 [Profile-Readme-Generator](https://rahuldkjain.github.io/github-profile-readme-generator/) 或 [Profile-Readme-Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)）
1. ***格式***：Markdown，HTML


# 2.简单调用（Markdown）
- 项目汇总：
  1. https://github.com/xiaohuohumax/readme-widget-hub
  2. https://github.com/madushadhanushka/github-readme

## 2.1.波浪横幅
1. ***官网***：https://github.com/kyechan99/capsule-render （自定义:https://capsule-render.vercel.app/）
2. ***属性***：
```bash
![header](https://capsule-render.vercel.app/api?
type=waving&        #横幅形式
height=300&         #横幅高度
color=0:FF6700,100:FFCB00&          #横幅颜色
text=Welcome%20to%20my%20Profile&   #横幅主标题
reversal=false&     #横幅左右翻转
textBg=false&       #主标题背景
fontColor=000000&   #主标题颜色
fontSize=70&        #主标题字号
animation=fadeIn&   #主标题动画
rotate=0&           #主标题旋转
stroke=FFA500&      #主标题边色
strokeWidth=1&      #主标题边宽
desc=——Alanxxk&     #横幅副标题
descSize=20&        #副标题字号
descAlign=87&       #副标题X轴
descAlignY=70)      #副标题Y轴
```
3. ***示例***：
   - *横幅头*：![header](https://capsule-render.vercel.app/api?type=waving&height=300&color=0:FF6700,100:FFCB00&text=Welcome%20to%20my%20Profile&reversal=false&textBg=false&fontColor=000000&fontSize=70&animation=fadeIn&rotate=0&stroke=FFA500&strokeWidth=1&desc=——Alanxxk&descSize=20&descAlign=87&descAlignY=70)
   - *横幅尾*：![header](https://capsule-render.vercel.app/api?type=waving&height=150&color=0:FF6700,100:FFCB00&reversal=false&section=footer&)
4. ***延伸***：
   - *分隔线*：![header](https://capsule-render.vercel.app/api?type=rect&height=2&color=FF8C00)

## 2.2.打字机
1. ***官网***：https://github.com/DenverCoder1/readme-typing-svg （自定义:https://readme-typing-svg.demolab.com/demo/）
2. ***属性***：
```bash
![Typing SVG](        #无法显示图片时显示文字
https://readme-typing-svg.demolab.com/?
lines=First+line+of+text;Second+line+of+text&   #+表示空格;表示另一行
height=50&            #矢量图SVG图片高度
width=400&            #矢量图SVG图片宽度
size=20&              #字体大小
font=monospace&       #字体类型（谷歌字体的monospace,sans-serif,serif等等）
color=36BCF7&         #文本颜色
background=00000000&  #背景颜色
center=false&         #水平居中文本（false则左对齐）
vCenter=false&        #垂直居中文本（false则上方）
multiline=false&      #true则换行,false则删除再打另一行
duration=5000&        #单行打印时间（单位ms）
pause=0&              #行间暂停时间（单位ms）
repeat=true&          #循环播放
separator=;&          #行间分隔符（;,;;,/）
letterSpacing=normal& #字母间距（normal,0.2rem,1px,-1px）
random=false)         #随机播放行
```
3. ***示例***：
   - *一般打字机*：[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=First+line+of+text;Second+line+of+text)](https://git.io/typing-svg)
   - *自定义打字*：[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=The+five+boxing+wizards+jump+quickly)](https://git.io/typing-svg)

## 2.3.图标
1. ***官网***：https://github.com/tandpfun/skill-icons
2. ***属性***：
```bash
![My Skills](       #无法显示图片时显示文字
https://skillicons.dev/icons?
i=js,html,css,wasm& #图标名称
theme=dark&         #明暗主题（light,dark）
perline=15)         #一行数量（1-50）
```
```html
<!-- 居中图标 -->
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,kubernetes,docker,c,vim" />
  </a>
</p>
```
1. ***示例***：
   - *技能*：![My Skills](https://skillicons.dev/icons?i=anaconda,arduino,astro,c,cs,cpp,clion,git,github,matlab,pycharm,py,pytorch,raspberrypi,ros,ubuntu,unity,vim,visualstudio,vscode,)
   - *社交*：![My Skills](https://skillicons.dev/icons?i=discord,gmail,instagram,stackoverflow)

## 2.4.访客数量徽章
1. ***官网***：https://github.com/antonkomarev/github-profile-views-counter
2. ***属性***：
```bash
![](                  #无法显示图片时显示文字
https://komarev.com/ghpvc/?
username=Alanxxk&     #Github用户名称
color=blue&           #右侧颜色（blue,brightgreen,颜色编码）
style=flat&           #徽章风格（flat,flat-square,plastic,for-the-badge,pixel）
label=Profile+View&   #左侧文本（+是空格）
base=1000&            #最低数量
abbreviated=true)     #数量缩写
```
3. ***示例***：![ProfileView](https://komarev.com/ghpvc/?username=Alanxxk&color=orange&style=flat&label=Profile+View&abbreviated=true)

## 2.5.各种徽章
1. ***官网***：https://shields.io/ （可自定义,可静态动态） 或 https://badgen.net/ （可自定义,可静态动态）
2. ***属性***：
```bash
![shields静态徽章](        #无法显示图片时显示文字
https://img.shields.io/
badge/                    #静态徽章标志
github-repo-blue?         #左侧文本-(右侧文本-)右侧背景颜色
style=flat&               #主题选择
logo=github&              #最左侧Logo显示（可以用base64编码）
logoColor=white&          #Logo颜色
logoSize=auto&            #Logo大小
label=git&                #左侧文本（高优先级）
labelColor=red&           #左侧背景颜色
color=green&              #右侧背景颜色（高优先级）
cacheSeconds=10&          #更新时间（单位s）
link=https%3A%2F%2Fshields.io%2Fbadges)   #跳转链接（有些字符要转义）
```
```bash
![shields动态徽章](        #无法显示图片时显示文字
https://img.shields.io/
github/stars/             #动态徽章标志
Alanxxk/Alanxxk)          #按照要求输入
```
```bash
![badgen静态徽章](         #无法显示图片时显示文字
https://badgen.net/
badge/                    #静态徽章标志
github/                   #左侧文本
repo/                     #右侧文本
orange?                   #右侧背景颜色
icon=github)              #最左侧Logo显示
```
```bash
![badgen动态徽章](         #无法显示图片时显示文字
https://badgen.net/
github/stars/             #动态徽章标志
Alanxxk/Alanxxk)          #按照要求输入
```
3. ***示例***：
   - *shields静态徽章*：![shields静态徽章](https://img.shields.io/badge/github-repo-blue?style=flat&logo=github&) 和 ![shields静态徽章-单边](https://img.shields.io/badge/-Python-blue?style=flat&logo=python&logoColor=white)
   - *shields动态徽章*：![shields动态徽章](https://img.shields.io/github/stars/Alanxxk/Alanxxk)
   - *badgen静态徽章*：![badgen静态徽章](https://badgen.net/badge/github/repo/orange?icon=github) 和 ![badgen静态徽章-预设](https://badgen.net/badge/icon/buymeacoffee?icon=buymeacoffee&label)
   - *badgen动态徽章*：![badgen动态徽章](https://badgen.net/github/stars/Alanxxk/Alanxxk)

## 2.6.数据统计
1. ***官网***：https://github.com/anuraghazra/github-readme-stats （自定义:https://gh-stats-gen.vercel.app/）
2. ***属性***：转义字符网站:https://www.urlencoder.org/ 和 语言时间:https://wakatime.com/
```bash
#个人数据
![Alanxxks Stats](      #无法显示图片时显示文字
https://github-readme-stats.vercel.app/api?
username=Alanxxk&       #Github用户名称
theme=highcontrast&     #主题选择
gh-dark-mode-only&      #明暗主题（gh-dark-mode-only,gh-light-mode-only）
count_private=true      #
bg_color=000000&        #透明度（8个0是透明,可加逗号渐变色）
title_color=2f80ed&     #标题颜色
text_color=434d58&      #正文颜色
icon_color=4c71f2&      #图标颜色
border_color=e4e2e2&    #边框颜色
bg_color=fffefe&        #背景颜色
hide_border=false&      #隐藏边框
cache_seconds=21600&    #更新时间（21600second=6hour）
locale=cn&              #语言
border_radius=4.5&      #边角圆润
hide=null&              #隐藏属性（null,stars,commits,prs,issues,contribs）
hide_title=false&       #隐藏标题
card_width=500&         #卡片宽度
hide_rank=false&        #隐藏等级
rank_icon=default&      #备用等级图标（default,github,percentile）
show_icons=true&        #图标显示
include_all_commits=false&  #显示总提交次数（false则当年提交）
line_height=25&         #文本行高
exclude_repo=null&      #排除选定仓库   
custom_title=GitHub_Stats&  #自定义标题（有些字符要转义）
text_bold=true&         #使用粗体字
disable_animations=false&   #禁用卡片动画
ring_color=2f80ed&      #等级圈颜色
number_format=short     #数值格式（short,long）
number_precision=null&  #小数点位数（null,0,1,2）
show=null&              #额外统计显示（reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage）
commits_year=2020)      #统计选定年份
```
```bash
#仓库卡片
![Readme Card](               #无法显示图片时显示文字
https://github-readme-stats.vercel.app/api/pin/?
username=anuraghazra&         #Github用户名称
repo=github-readme-stats&     #Github仓库
show_owner=false&             #显示仓库作者名称
description_lines_count=null& #描述行数（null,1,2,3）
)                             #同理上文大部分选项
```
```bash
#编程语言
![Top Langs](                     #无法显示图片时显示文字
https://github-readme-stats.vercel.app/api/top-langs/?
username=anuraghazra&             #Github用户名称
hide=null&                        #隐藏选定语言（有些字符要转义）
hide_title=false&                 #隐藏标题
layout=normal&                    #布局切换（normal,compact,donut,donut-vertical,pie）
card_width=300&                   #卡片宽度
langs_count=5&                    #显示语言数量（1-20）
exclude_repo=null&                #排除选定仓库
custom_title=Most_Used_Languages& #自定义标题（有些字符要转义）
disable_animations=false&         #禁用动画
hide_progress=false&              #使用紧凑布局
size_weight=1&                    #语言字节数统计权重
count_weight=0&                   #语言仓库数统计权重
stats_format=percentages)         #统计格式（percentages,bytes）
```
```bash
#语言时间
![Harlok WakaTime stats](     #无法显示图片时显示文字
https://github-readme-stats.vercel.app/api/wakatime?
username=ffflabs&             #WakaTime用户名
hide=null&                    #隐藏选定语言（有些字符要转义）
hide_title=false&             #隐藏标题
card_width=495&               #卡片宽度
line_height=25&               #文本行高
hide_progress=false&          #隐藏进度
custom_title=WakaTime_Stats&  #自定义标题（有些字符要转义）
layout=default&               #布局切换（default,compact）
langs_count=null&             #语言数量
api_domain=wakatime.com&      #自定义API
display_format=time&          #数据格式（time,percent）
disable_animations=false)     #禁用动画
```
```html
<!-- 并排对齐方法 -->
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=anuraghazra" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=anuraghazra&layout=compact&langs_count=8&card_width=320" />
</a>

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```
3. ***示例***：
   - *个人数据*：![Anuraghazra's Github Stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&hide_border=false&count_private=true)
   - *仓库卡片*：[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
   - *编程语言*：![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact) 和 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=donut)](https://github.com/anuraghazra/github-readme-stats) 和 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=pie)](https://github.com/anuraghazra/github-readme-stats)
   - *语言时间*：[![Harlok's WakaTime stats](https://github-readme-stats.vercel.app/api/wakatime?username=ffflabs&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

## 2.7.连续贡献天数
1. ***官网***：https://github.com/DenverCoder1/github-readme-streak-stats （自定义:https://streak-stats.demolab.com/demo/）
2. ***属性***：
```bash
![GitHub Streak](                   #无法显示图片时显示文字
https://streak-stats.demolab.com?
user=Alanxxk&                       #Github用户名称
theme=default&                      #主题选择
hide_border=false&                  #隐藏边框
border_radius=4.5&                  #边框圆角（0-248）
background=f2f2f2&                  #背景颜色（可加逗号渐变色）
border=FF8C00&                      #边框颜色
stroke=FF8C00&                      #分隔线颜色
ring=FF8C00&                        #连胜环颜色
fire=FF8C00&                        #圆环内火焰颜色
currStreakNum=FF8C00&               #“目前连续贡献”数字颜色
sideNums=FF8C00&                    #“合计贡献”和“最长连续贡献”数字颜色
currStreakLabel=FF8C00&             #“目前连续贡献”文本颜色
sideLabels=FF8C00&                  #“合计贡献”和“最长连续贡献”文本颜色
dates=FF8C00&                       #日期文本颜色
excludeDaysLabel=FF8C00&            #排除星期几的颜色
date_format=%5BY.%5Dn.j&            #日期格式
locale=zh_Hans&                     #语言选择
short_numbers=true&                 #简略数字显示
type=svg&                           #图片格式（svg,png,json）
mode=daily&                         #连击判定规则（daily,weekly）
exclude_days=Sat&                   #排除星期几的连胜判定
disable_animations=false&           #禁用SVG动画
card_width=495&                     #卡片宽度（最小100px）
card_height=195&                    #卡片高度（最小170px）
hide_total_contributions=false&     #隐藏“合计贡献”
hide_current_streak=false&          #隐藏“目前连续贡献”
hide_longest_streak=false&          #隐藏“最长连续贡献”
starting_year=2024)                 #统计的起始年份
```
3. ***示例***：
   - *一般贡献显示*：[![GitHub Streak](https://streak-stats.demolab.com?user=Alanxxk)](https://git.io/streak-stats)

## 2.8.Github活跃曲线
1. ***官网***：https://github.com/Ashutosh00710/github-readme-activity-graph/ （快速:https://ashutosh00710.github.io/github-readme-activity-graph/）
2. ***属性***：
```bash
![Ashutosh github activity graph](
https://github-readme-activity-graph.vercel.app/graph?
username=Ashutosh00710&   #Github用户名称
bg_color=FF8C00&          #背景颜色
border_color=FF8C00&      #边框颜色
color=FF8C00&             #正文颜色
title_color=FF8C00&       #标题颜色
line=FF8C00&              #线条颜色
point=FF8C00&             #点的颜色
area_color=FF8C00&        #图下颜色
area=false&               #图下面积
hide_border=false&        #边框透明
hide_title=false&         #隐藏标题
custom_title=Alanxxk_Activity_Graph&  #自定义标题（有些字符要转义）
theme=dracula&            #主题选择
radius=8&                 #边框半径（0-16）
height=400&               #图表高度（200-600）
days=40&                  #显示天数（1-90）
from=2025-12-01&          #开始日期
to=2025-12-20&            #结束日期
grid=true&                #显示底格
)            
```
3. ***示例***：
   - *一般图表*：[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=ashutosh00710&custom_title=This%20is%20a%20title&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
   - *自定义图表*：[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=ashutosh00710&bg_color=fffff0&color=708090&line=24292e&point=24292e&area=true&border_color=ff0000)](https://github.com/ashutosh00710/github-readme-activity-graph)

## 2.9.网站数据
1. ***官网***：https://github.com/songquanpeng/stats-cards
2. ***属性***：
```bash
![Harlok WakaTime stats](   #无法显示图片时显示文字
https://stats.justsong.cn/api/
leetcode/?          #网站名称
username=quanpeng&  #用户名称（b站和掘金和CSDN和牛客是id=）
theme=dark&         #主题选择（可参考github-readme-stats）
lang=zh-CN)         #中文语言
```
```bash
![Github Ping](             #无法显示图片时显示文字
https://stats.justsong.cn/api/website/?
url=https://github.com/&  #网站链接
style=flat&               #徽章风格（可参考shields.io）
logo=github)              #徽章图标
```
3. ***示例***：
   - *网站信息*：![Harlok's WakaTime stats](https://stats.justsong.cn/api/leetcode/?username=quanpeng&theme=dark&lang=zh-CN)
   - *网站延迟*：![Github Ping](https://stats.justsong.cn/api/website/?url=https://github.com/&style=flat&logo=github)

## 2.10.Github仓库收藏曲线
1. ***官网***：https://github.com/star-history/star-history?tab=readme-ov-file（自定义:https://www.star-history.com/）（可安装浏览器扩展）
2. ***备用***：https://codetabs.com/github-stars/github-star-history.html
3. ***属性***：
```bash
[![Star History Chart](https://api.star-history.com/svg?
repos=Alanxxk/      #Github用户名称
star-history&       #Github仓库名称
type=date&legend=top-left)](https://www.star-history.com/#
bytebase/           #Github用户名称
star-history&       #Github仓库名称
type=date&legend=top-left)
```
1. ***示例***：
   - *Star历史*：[![Star History Chart](https://api.star-history.com/svg?repos=bytebase/star-history&type=date&legend=top-left)](https://www.star-history.com/#bytebase/star-history&type=date&legend=top-left)

## 2.11.访客数量图片
1. ***官网***：https://github.com/journey-ad/Moe-counter（自定义:https://capsule-render.vercel.app/）
2. ***属性***：
```bash
![访客数量](    #无法显示图片时显示文字
https://count.getloli.com/@Alanxxk? #Github用户名称
name=Alanxxk&   #显示文字（在主题可显示文字时）
theme=3d-num&   #主题名称
padding=7&      #数字个数（1-16）
offset=0&       #数字间距（-500-500）
align=top&      #图像对齐（top,center,bottom）——未见作用
scale=1&        #数字大小（0.1-2）
pixelated=1&    #启用像素模式（0,1）
darkmode=auto&  #启用黑暗模式（auto,0,1）
num=0&          #设置数字
prefix=访客:)   #前缀数字
```
3. ***示例***：
   - *3d-num*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=3d-num&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *normal-1*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=normal-1&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *capo0-2*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=capoo-2&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *asoul*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=asoul&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *rule34*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=rule34&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *moebooru*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=moebooru&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)
   - *gelbooru*：![](https://count.getloli.com/@Alanxxk?name=Alanxxk&theme=gelbooru&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)

## 2.12.访客旗帜（不推荐使用—因出现台湾旗）
1. ***官网***：https://www.flagcounter.com/
2. ***格式***：HTML
3. ***设置***：旗帜显示或地图显示，选择显示方式和属性，无需登录
4. ***示例***：
   - *旗帜显示*：<a href="https://info.flagcounter.com/qpWJ"><img src="https://s01.flagcounter.com/count2/qpWJ/bg_FFFFFF/txt_000000/border_CCCCCC/columns_4/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
   - *地图显示*：<a href="https://info.flagcounter.com/DMTo"><img src="https://s01.flagcounter.com/map/DMTo/size_l/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Flag Counter" border="0"></a>

## 2.13.名言引用
1. ***官网***：https://github.com/PiyushSuthar/github-readme-quotes
2. ***属性***：
```bash
![Readme Quotes](       #无法显示图片时显示文字
https://quotes-github-readme.vercel.app/api?
type=horizontal&        #显示方向（horizontal,vertical）
theme=dark&             #主题选择
quote=hihi&             #自定义引文   
quoteColor=ff0000&      #引文颜色
author=Alanxxk&         #注明作者
authorColor=00ff00&     #作者颜色
backgroundColor=0000ff& #背景颜色
symbolColor=ffff00      #引号颜色
border=false)           #显示边界
```
3. ***示例***：
   - *引用文本*：[![Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)](https://github.com/piyushsuthar/github-readme-quotes)
   - *自定义引用*：![Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&border=true&quote=hihi&author=Alanxxk)

## 2.14.学习网站徽章
1. ***官网***：无
2. ***属性***：无
3. ***示例***：
   - *网络安全*：（https://tryhackme.com/dashboard） ![tryhackme](https://tryhackme-badges.s3.amazonaws.com/alan.xxk.mikasa.png)
   - **：

## 2.15.Github仓库图片显示
1. ***官网***：无
2. ***属性***：
```python
https://raw.githubusercontent.com/  #或直接使用github.com
cumany/   #Github用户名称
cumany/   #仓库名称
main/     #分支名称（注意直接复制网址要删除前面多出的blog）
pic/      #文件夹名称
202209192228895.png   #图片名称
```
3. ***示例***：![图片描述](https://raw.githubusercontent.com/Alanxxk/Astro-Source-Website/main/public/assets/images/Alanxxk_material/Cat_meme.jpg)

## 2.16.图片存储
1. ***官网***：https://www.jsdelivr.com/
2. ***属性***：无
3. ***示例***：
   - *jpg图片*：![jpg图片](https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/assets/images/developer.svg)
   - *gif动图*：![gif动图](https://cdn.jsdelivr.net/gh/sun0225SUN/sun0225SUN/assets/images/coding.gif)

## 2.17.HTML居中语法
1. ***官网***：无
2. ***属性***：
```html
<div id="img" align=center>内容</div>
```
3. ***示例***：无


# 3.复杂调用（Github Action或其他）
## 3.1.贡献热力图—贪吃蛇视图（未完结）
1. ***官网***：https://github.com/Platane/snk （预览:https://platane.github.io/snk/）
2. ***方法***：Github Action和SVG
```yaml
name: generate animation

on:
  # run automatically every 24 hours
  schedule:
    - cron: "0 */24 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the master branch
  push:
    branches:
    - master

jobs:
  generate:
    permissions: 
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg">
</picture>
```
3. ***示例***：
   - *明亮模式*：
   - *黑暗模式*：

## 3.2.贡献热力图—2D+3D（未完结）
1. ***官网***：https://github.com/yoshi389111/github-profile-3d-contrib
2. ***方法***：Github Action（可以添加私有仓库贡献:`Settings→Public profile→Contributions&Activity→Include private contributions on my profile`）
```yaml
name: GitHub-Profile-3D-Contrib

on:
  schedule: # 03:00 JST == 18:00 UTC
    - cron: "0 18 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v5
      - uses: yoshi389111/github-profile-3d-contrib@latest
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          if git commit -m "generated"; then
            git push
          fi
```
3. ***使用***：
```markdown
![](./profile-3d-contrib/profile-green-animate.svg)
```

## 3.3.信息统计（未完结）
1. ***官网***：https://github.com/vn7n24fzkq/github-profile-summary-cards （范例:https://github-profile-summary-cards.vercel.app/demo.html）
2. ***方法***：Github Action
```bash
name: GitHub-Profile-Summary-Cards

on:
  schedule: # execute every 24 hours
    - cron: "* */24 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-summary-cards

    steps:
      - uses: actions/checkout@v4
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env: # default use ${{ secrets.SUMMARY_GITHUB_TOKEN }}, you should replace with your personal access token
          GITHUB_TOKEN: ${{ secrets.SUMMARY_GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}
          # BRANCH_NAME is optional, default to main, branch name to push cards
          BRANCH_NAME: "main"
          # UTC_OFFSET is optional, default to zero
          UTC_OFFSET: 8
```
3. ***示例***：
   - *综合表格*：![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=vn7n24fzkq&theme=default)
   - *仓库语言*：![](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=vn7n24fzkq&theme=default)
   - *提交语言*：![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=vn7n24fzkq&theme=default)
   - *个人数据*：![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=vn7n24fzkq&theme=default)
   - *提交时间*：![](http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=vn7n24fzkq&theme=default&utcOffset=8)

## 3.4.编程时间（未完结）
1. ***官网***：https://github.com/anmol098/waka-readme-stats
2. ***属性***：Github Action
```bash
name: Waka Readme
on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
```
3. ***示例***：

## 3.5.RSS同步显示标题（未完结）
1. ***官网***：https://github.com/gautamkrishnar/blog-post-workflow
2. ***属性***：
```bash
name: Latest blog post workflow
on:
  schedule: # Run workflow automatically
    - cron: '0 0 * * *' # Runs once a day at 00:00 UTC
  workflow_dispatch: # Run workflow manually (without waiting for the cron to be called), through the GitHub Actions Workflow page directly
permissions:
  contents: write # To write the generated contents to the readme

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4
      - name: Pull in dev.to posts
        uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://dev.to/feed/gautamkrishnar,https://www.gautamkrishnar.com/feed/"
```
3. ***示例***：

## 3.6.Github仓库贡献人员显示（未完结）
1. ***官网***：https://allcontributors.org/
2. ***设置***：https://allcontributors.org/bot/installation/
3. ***示例***：无

## 3.7.贡献热力图—3D打印（未完结）
1. ***官网***：https://github.com/github/gh-skyline
2. ***设置***：无
3. ***示例***：无

## 3.8.赞助按钮（需有港澳或境外银行卡）（未完结）
1. ***官网***：https://img.buymeacoffee.com/button-api 或 https://github.com/open-source/sponsors
2. ***设置***：注册登录后，在个人信息界面的`Settings→Buttons&Graphics→Generate`
3. ***示例***：无


# 4.模板
1. ***官网***：
2. ***设置***：
3. ***示例***：