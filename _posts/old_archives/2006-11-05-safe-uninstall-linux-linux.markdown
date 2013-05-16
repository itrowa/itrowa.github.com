---
layout: post
title: 安全卸载Ubuntu Linux
categories:
- Journal
tags: []
published: true
comments: true
---
<p><p>Ubuntu在我的硬盘上安家已经有大约半个月了，今天我下狠手把它删除了。原因有两个：</p><ol><li>Ubuntu虽然在很多方面都做得非常人性化，但是它的优势根本不足以让我彻底舍弃Windows而转投Linux。看来桌面版的Linux，还是有很长的一段路要走。</li><li>出于个人因素，我认为研究模拟飞行比研究Linux更有趣。硬盘空间刚好不够用，所以第一想到的就是卸载Ubuntu。</li></ol><p>好，闲话少说，回归正题。由于在这台计算机里有Windows与Linux双系统并存，所以卸载Linux的核心思想就是把系统引导权重新交给Windows，然后释放Linux所占用的系统资源。具体方法也不难，关键是最重要的两个字：安全。</p><ol><li>&nbsp;拿出XP的安装光盘，启动系统，进入故障恢复控制台。依次序键入这两个命令：<br /><span style="background-color: #ffffcc">fixboot</span><br /><span style="background-color: #ffffcc">fixmbr<br /><span style="background-color: #ffffff">命令成功完成后，重起系统。</span></span></li><li><span style="background-color: #ffffcc"><span style="background-color: #ffffff">使用PQMagic等磁盘分区管理软件（推荐使用DOS版），找到Linux所在的分区，直接删除，然后将剩余空间与Windows分区合并，或者为剩余空间重新分区。用硬盘重起到Windows。至此所有工作完成。</span></span></li></ol><p><span style="background-color: #ffffcc"><span style="background-color: #ffffff">不难看出，安全卸载Linux的步骤是先修复引导，再释放Linux占用的系统资源，这样做比先释放Linux占用的系统资源，再修复引导的方法安全许多。因为一旦修复MBR有任何闪失，还可以轻松地用Linux重新恢复MBR，但如果先把Linux删除了，进入系统的途径就少了一条，安全性也有所降低。以上方法在我的机器上没有出现任何问题，如果有疑问，可以参考Microsoft的<a href="http://support.microsoft.com/kb/307654/zh-cn">这篇支持文档</a>。</span></span></p><p>到现在，我对Linux的研究也就告一段落了，以后尝试的发行版，很有可能是Suse这款商业的Linux。</p><p><br />Linux，I&#39;ll be back!</p></p>
