---
layout: post
title: VirtualBox如何实现虚拟机和主机的文件共享
categories:
- ! '@奇怪的评测、体验和心得'
- Journal
tags: []
published: true
comments: true
---
<p>最近没事情研究了一下VirtualBox，这个免费的、由Sun公司推出的虚拟机软件的确是一款非常好的工具。</p>

<p>在配置虚拟机中的Windows XP的时候，一切顺利，但是最大的问题就是不知道如何让虚拟机里面的XP访问我的主机上面的磁盘文件。现在我终于搞清楚了，以下是最简单的办法：</p>

<p>1 点击虚拟机窗口的<strong>设备</strong>，单击“<strong>分配数据空间</strong>”：
<img class="alignnone" src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2010/01/step1.jpg" alt="添加数据空间" width="335" height="303" /></p>

<p>2 在<strong>数据空间</strong>对话框里，按键盘上的<strong>Insert键</strong>或者单击“<strong>添加</strong>”按钮：
<img class="alignnone" src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2010/01/step2.jpg" alt="添加一个..." width="466" height="338" /></p>

<p>3 在“<strong>添加数据空间</strong>”对话框中，在数据空间位置选择想共享的主机目录；“<strong>只读分配</strong>”是为了保证虚拟机不对主机上的数据进行破坏；“<strong>固定分配</strong>”能保证下次启动VirtualBox时软件自动添加这个共享目录：
<img class="alignnone" src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2010/01/step3.jpg" alt="添加数据空间" width="322" height="226" /></p>

<p>在虚拟机里系统桌面的“<strong>我的电脑</strong>”图标上点右键，选择“<strong>映射网络驱动器</strong>”，在弹出的对话框中，选择一个驱动器（例如Z:），“文件夹”一行，<br />
填入<code>\vboxsvr</code>
4 然后点<strong>浏览</strong>，接着就能看到刚才添加的数据空间了：
<a href="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2010/01/step4.jpg"><img class="alignnone" src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2010/01/step4.jpg" alt="继续添加" width="470" height="483" /></a>&lt;</p>

<p>5 打开虚拟机上的<strong>我的电脑</strong>，就能看到共享的目录和驱动器了:)</p>
