---
layout: post
title: 3个方法修改Windows 7默认用户目录位置
categories:
- Journal
tags:
- windows
- windows 7
- 人性化
- 管理
published: true
comments: true
---
<p><p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">从 XP一下子迁移到Windows 7，应该很多人都和我一样感到很不习惯吧？比如杜罗华一直使用“我的文档”来作为用户目录，图片，音乐，视频等都放在“我的文档”下面，而且修改了默认路 径到非系统盘的位置。不过到了Windows 7时代，重新使用这个功能似乎变得有些困难：原来在XP下直接可以在“我的文档”属性里面修改这个目录的位置，但是在Win7中一个新出的“库”替代了这 些位置……不过经过仔细研究，发现，Windows 7也能和XP一样修改默认用户目录的位置，而且自定义功能更加强大：</p>
<p style="margin: 0in; font-weight: bold; font-family: 微软雅黑; font-size: 12pt;">一、Windows 7 的用户目录的结构</p>
<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">在XP中，默认情况下每个用户的目录会放在?:Documents and SettingsuserMy Documents中，“我的图片”，“我的音乐”等也都放在这个目录中，而在Windows 7 中使用了更为合理的树形结构：?usersyourname，而这个目录下“Documents”,“Music”，“Pictures”等目录都 是平行平行排列的，不像XP那样，图片、音乐放在My Documents下面。也就是说在Windows 7中降低了“Documents”这个目录的重要性，而突出了“<span style="font-weight: bold;">个人文件夹</span>”的概念：</p></p>

<p><p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;"></p>

<p>[caption id="attachment_234" align="alignnone" width="472" caption="开始菜单中的个人文件夹"]<a><img class="size-full wp-image-234" title="开始菜单中的个人文件夹" src="http://www.trowa.org/wp-content/media/2009/07/开始菜单中的个人文件夹.jpg" alt="开始菜单中的个人文件夹" width="472" height="648" /></a>[/caption]
<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;"></p>
<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">而打开个人文件夹后，“我的文档”也只是和“音乐”，“图片”等平行排列的一个分类而已，是不是更科学了呢：</p></p>

<p><p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;"></p>

<p>[caption id="attachment_235" align="alignnone" width="497" caption="更科学的个人文件夹"]<a href="http://www.trowa.org/wp-content/media/2009/07/个人文件夹.JPG"><img class="size-full wp-image-235" title="个人文件夹" src="http://www.trowa.org/wp-content/media/2009/07/个人文件夹.JPG" alt="更科学的个人文件夹" width="497" height="342" /></a>[/caption]
<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">个人文件夹里的目录</p>
<p style="margin: 0in; font-weight: bold; font-family: 微软雅黑; font-size: 12pt;">二、三种方法修改默认用户目录位置</p>
<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">修改“我的文档”已经成为自XP时代以来稍微理解Windows XP的用户都会做的事情，大多数人总是担心位于系统盘的XP突然崩溃掉，重装系统会导致放在系统盘里面的文档丢失，所以修改目录的做法非常盛行。到了 win7时代，虽然系统变慢的几率小了不少，其实还是有必要改一下用户目录的路径的，因为你的音乐、图片和系统文件放在一起，不怎么符合科学管理的理念 嘛……下面就详细介绍一下这三种修改用户目录位置的方法：</p></p>

<p><ol style="margin-left: 0.75in; direction: ltr; unicode-bidi: embed; margin-top: 0in; margin-bottom: 0in; font-family: 微软雅黑; font-size: 9pt; font-weight: bold;" type="1">
	<li style="margin-top: 0pt; margin-bottom: 0pt; vertical-align: middle; font-weight: bold; color: #333399;"><span style="font-weight: bold; font-family: 微软雅黑; font-size: 9pt; color: #333399;">在资源管理器中修改
</span><span style="font-weight: normal; font-family: 微软雅黑; font-size: 9pt; color: #000000;">其实弄清楚了Windows      7对于用户目录的理解后，修改目录位置的思路几乎和XP一模一样：首先打开你的个人文件夹<br />
，看到一大堆目录了吧，分别打开这些目录的属性，切换到“位置”选项卡：</span></li></ol></p>

<p>[caption id="attachment_236" align="alignnone" width="383" caption="修改每个位置的属性"]<a href="http://www.trowa.org/wp-content/media/2009/07/修改属性.JPG"><img class="size-full wp-image-236" title="修改属性" src="http://www.trowa.org/wp-content/media/2009/07/修改属性.JPG" alt="修改每个位置的属性" width="383" height="460" /></a>[/caption]</p>

<p>修改到你想要的地方就行了。（小问题：怎么修改以后，“我的音乐”等名字变得很奇怪而且无法修改了呢？这个问题是原来在XP时代的时候给“我的音      乐”目录改名了造成的，这样你的那个音乐目录下面会有一些隐藏文件导致无法再改名了，所以解决方法也简单，把你的音乐Copy到另外一个干净的目录里面就      行了。）<br />
简单吧。
	<li style="margin-top: 0pt; margin-bottom: 0pt; vertical-align: middle; font-weight: bold; color: #333399;"><span style="font-weight: bold; font-family: 微软雅黑; font-size: 9pt; color: #333399;">利用注册表编辑器
</span><span style="font-weight: normal; font-family: 微软雅黑; font-size: 9pt; color: #000000;">按下Win+R打开运行窗口，输入Regedit，进入注册表编辑器，定位到：HKEY_CURRENT_USERSoftware      MicrosoftWindowsCurrentVersionExplorerUser Shell Folders，发现很多秘密了吧：
</span><span style="font-weight: normal; font-family: 微软雅黑; font-size: 9pt; color: #000000;" /></li></p>

<p>[caption id="attachment_237" align="alignnone" width="499" caption="注册表编辑器"]<a href="http://www.trowa.org/wp-content/media/2009/07/利用注册表编辑器修改.JPG"><img class="size-full wp-image-237" title="利用注册表编辑器修改" src="http://www.trowa.org/wp-content/media/2009/07/利用注册表编辑器修改.JPG" alt="注册表编辑器" width="499" height="285" /></a>[/caption]</p>

<p>其实第一种方法就是“图形化”修改注册表，和第二种方法原理是一样的，不过，修改注册表的方法功能更强大，连开始菜单，缓存目录等位置都可以设置，不过在修改之前一点要明白每个简直代表着哪个目录的路径哦，不要弄错了。
	<li style="margin-top: 0pt; margin-bottom: 0pt; vertical-align: middle; font-weight: bold; color: #333399;"><span style="font-weight: bold; font-family: 微软雅黑; font-size: 9pt; color: #333399;">利用mklink命令
</span><span style="font-weight: normal; font-family: 微软雅黑; font-size: 9pt; color: #000000;">这应该是一种高级方法，这是我在网上看到的，可以去用Google搜索《用mklink.exe实现系统和用户文件的分区存放》。优点是非常彻底，甚至连个人文件夹的默认位置都可以“硬链”到其他地方，缺点是有些麻烦，会不会有问题我还要在看下。</span></li>

<p style="margin: 0in; font-family: 微软雅黑; font-size: 9pt;">以上便是修改默认用户目录位置的三种方法，以后应该能找到更好的方法来解决windows 7的问题，到时候Trowa Studio会再发文章……</p></p></p></p>
