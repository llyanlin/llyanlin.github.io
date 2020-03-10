---
layout: post
title: '三分钟教你搭建属于自己的博客'
subtitle: '不用敲代码也能搭建属于自己的博客。'
date: 2020-03-09
categories: 个人博客 
cover: 'assets/img/hero.jpg'
tags: jekyll 博客 github pages
---




早在2016年就想维护一个属于自己的网站，那一年，自己在度娘上各种找，各种教程拼接，摸索着在阿里云注册了一个域名，还斥巨资（按当时的收入真的是巨资）买了云服务器，然后还踉踉跄跄给网站完成了备案。当时，自己用 discuz！搭建了一个商城型的网站。后来，由于工作压力太大没有时间维护，一年后云服务器到期停止了续费而停掉了网站。

直到最近，阿里云一直提醒我，我的域名备案信息有误（因为没有了网站），才又起了自己做博客网站的决心。好吧……不多扯了，下面进入主题。

偶然的知道了 github page 可以快速搭建博客，并且了解到博客搭建完后，可以不折腾域名和服务器备案，绑定域名后，使用域名访问，和正常搭建的博客也没太大差别，最重要的是后面写文章只要了解一点点 markdown 语法就能写出漂亮的文档，而且不用担心有广告插播，不用担心会被删帖。于是手又痒痒的在网上找教程，开始搭建了。

下面给大家介绍我博客整个的搭建过程，跟着我的步骤，你也可以拥有属于你自己的博客。

## 前提条件

首先，我们是通过 *GitHub* *Page* 发布个人网页，所以首先你得拥有属于你的 github 账号。

拥有 github 帐号：到 [github]( https://github.com/ ) 官网注册一个账号：https://github.com/join?source=login  （注意，这里一定要记住你的用户名，后面要用到）
![](assets/img/github blog/github blog1.png)
其次，你得了解一下 markdown 语法：https://markdown-zh.readthedocs.io/en/latest/


## 第一步
创建你的 github 仓库（Repository）。
点击右上角【+】- 【New repository】，
![](assets/img/github blog/github blog2.png)

填写你的仓库名称，描述，并配置一个 readme 文档。点击【Create  repository】创建成功。
![](assets/img/github blog/github blog3.png)
**注意**，这里要用 xxxxx.github.io 作为仓库名字，xxxxx 是你注册 github 账号时填写的账号名。

## 第二步
为你的仓库开启 GitHub Page 功能。点击右上【Settings】，
![](assets/img/github blog/github blog4.png)

往下滚动页面，找到 GitHub Page 模块，【Source 】选择 master。
![](assets/img/github blog/github blog8.png)

选择之后，页面会进行刷新，稍等片刻，刷新完成后，再回到 GitHub Page 模块，
你会看到一行提示：` Your site is published at https://lillianlin2018.github.io/`
https://xxxxx.github.io （xxxxx是你一开始注册的 github 账号名）就是你的博客的页面网址了。
![](assets/img/github blog/github blog5.png)

## 第三步
我们再次回到你仓库的【Settings】里，滚动到 GitHub Page 模块，点击【Choose a theme】选择一个你喜欢的模板。确认后，编辑你的第一篇博客文章，并提交更改。
![](assets/img/github blog/github blog6.png)

使用浏览器打开：https://xxxxx.github.io （xxxxx是你一开始注册的 github 账号名）
灯灯灯灯~，恭喜你，拥有了属于你的博客网站，你可以随便折腾它了。
![](assets/img/github blog/github blog7.png)


