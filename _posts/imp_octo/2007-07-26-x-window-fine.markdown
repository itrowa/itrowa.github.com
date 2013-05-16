---
layout: post
title: X-window的效率并不差
categories:
- Journal
tags: []
published: true
comments: true
---
<p>最近我格式化掉了Windows XP，将整块硬盘让给了ubuntu。当然，格掉XP后肯定重装了一遍ubuntu。这一装可有了惊天发现：刚刚装好后，整个系统的反应速度快得惊人，比XP快了很多！默认设置情况下，竟然比我装好了Nvidia-glx驱动，重新编译xorg.conf，开启桌面效果后的相应速度快上很多！这主要表现在滚屏上。我记得我原来用ubuntu的时候，无论是Firefox还是Gedit，滚屏时都会出现“卡”的情况，特别是在使用Google Reader的时候。我被这种现象折磨得比较恼火，我还一直以为是X-window的效率太差:(。其实在默认状态下Gnome的反应速度是相当不错的。现在问题是，到底是什么导致了后来效率的低下呢？驱动？xorg.conf配置文件？还是compiz桌面效果？</p>

<p><strong>Update： </strong>找到问题所在，果然是桌面效果惹的祸。正所谓什么配置玩什么特效，这话果然不假……</p>
