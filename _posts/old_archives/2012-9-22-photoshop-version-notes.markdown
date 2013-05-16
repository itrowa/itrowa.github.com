---
layout: post
title: "Photoshop版本研究笔记"
date: 2012-09-23 00:06
comments: true
categories: journal
---

好久没有更新Blog了。其实最近我一直都在考虑各种问题……做的事情也相当多。顺便，最近我准备把这大半年来搞的一些事情，甚至是老久以前干的事情，都放在Blog上做一些总结吧。首先是原来令人困惑的Photoshop版本、Adobe Camera Raw版本，以及Adobe对各种相机专有Raw格式文件支持情况的问题。

刚刚开始用PS来解码Raw格式文件的时候，我杯具地发现不是每个PS都可以顺利打开我的尼康D3100的Raw文件的；有些版本的PS，即使下了更新包也不行，有的版本就行。Photoshop的版本号是CS3，CS4，CS5...而对应这些PS版本的Camera Raw的版本号又是怎么样的呢？一番调查后，我有了自己的结论。

##版本号问题
Photoshop的版本号和Camera Raw的版本号是绑定的~！
具体请参考<http://www.adobe.com/cn/downloads/updates/ >

例如，
cs4 对应 camera raw 5.x<br/>
cs5 对应 camera raw 6.x<br/>
cs6 对应 camera raw 7.x<br/>

需要说明的是，PS CS4是无法升级到Camera Raw 6.x版本的。其其它的PS版本也类推。

而且，不是每个版本的Camera Raw都能支持到最新相机的Raw文件的，例如，Camera Raw 6.x就打不开尼康D3200的NEF文件，至少要Camera Raw 7.1才可以。（见<http://www.adobe.com/support/downloads/detail.jsp?ftpID=5391>）所以，你有一台尼康D3200，又要使用Photoshop打开照相机的Raw文件，应该使用Photoshop CS6才可以！尼玛的Adobe坑爹是不。

我的相机是尼康D3100，支持D3100的Camera Raw版本号至少是 6.3，这意味着，如要使用Camera Raw打开D3100原版的`.NEF`文件，必须要Photoshop的版本至少是CS5.

大家可以在<http://www.adobe.com/support/downloads/product.jsp?product=106&platform=Windows> 查看Camera Raw的各个更新版本。在这里可以查询到你的相机的Raw格式图像最先是被哪一个版本的Camera Raw支持，这样你就可以选择Photoshop的版本了。

如果你有一台很新的相机，又想用老版本的Photoshop来处理它产生的Raw文件，那也是可以的。Adobe推出了一个DNG Converter，可以将厂商的Raw格式文件转换成Adobe公司的DNG格式，这样在老版本上的Camera Raw也能顺利打开。

##关于Camera Raw升级：
ACR的更新将同时作用与PS和Bridge，若一格Raw文件在PS的ACR中打不开 在Bridge中同样打不开。推荐使用官方的ACR升级 而不是按网上流传的那样，直接拷贝Camera Raw.8bi，我自己试验过，Bridge根本不认可这个升级，而且这样的升级以后就无法安装PS的外挂插件了。

##note
我坚持认为Photoshop应该安装原版的，升级补丁也要使用原版的，原来我就是使用了精简版，后来出现很多莫名其妙的错误，有一次安装了一精简版本的Photoshop，导致Camera Raw插件无法更新，后来想换用原版，结果发现原版的安不上！郁闷至极。

