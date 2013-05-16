---
layout: post
title: 微软雅黑应用指南
categories:
- Journal
tags: []
published: true
comments: true
---
<p>微软雅黑是Microsoft在Vista操作系统上使用的中文字体，据说这也是第一款支持ClearType技术的中文字体，其造价每个字高达100美元，一共收录了20000个汉字（不完全统计），这种耗资巨大的字体，装到XP上简直是漂亮极了！</p>

<p><strong>理论知识篇</strong>
<blockquote><span><span>ClearType</span></span> <span><span>技术是一种增强文字的显示效果的技术，可以让您显示器上显示的文字更加清晰圆润。</span></span></blockquote>
下面的这张对比图可以清楚的看到ClearType与普通效果的区别。</p>

<p><!--more--></p>

<p><img src="http://www.trowa.org/att/2007/08/cleartype2.gif" alt="cleartype" /></p>

<p>ClearType中，系统平滑了字体的顷斜部分，使得字体看起来少了一些锯齿感，多了一些柔和的感觉。但是，ClearType的开启需要字体的支持，然而我们通常使用的宋体是不支持这个特效的，所以到目前为止，中文字体的显示非常糟糕，一排一排的锯齿让人看了以后非常难受。微软的大爷们大概看到了这种窘境，所以终于在以视觉效果著称的Vista中加入一种支持ClearType的新字体——微软雅黑。其实微软雅黑这种字体不算好看，只因为它支持ClearType，所以才能大放光彩。在不起用ClearType的情况下，微软雅黑的效果并不强。</p>

<p>所以，在使用微软雅黑的时候，必须启用ClearType。</p>

<p><strong>基础篇</strong></p>

<p>1.首先下载微软雅黑字体。</p>

<p>点击下载：<a href="http://www.51files.com/?PSCB27KZ9U92R5CXEM3C" target="_blank">微软雅黑0.71</a></p>

<p>2.安装。解压后，将TTF字体文件复制到C:/Windows/fonts/文件夹下以完成字体的安装。</p>

<p>3.打开“桌面属性”，切换到“外观”选项卡，再单击“效果”，勾选“使用下列方式使屏幕字体的边缘平滑”，然后选择“清晰”。</p>

<p><img src="http://www.trowa.org/att/2007/08/zhuomianxiaoguo.gif" alt="cleartype tuning" />
4.打开你的浏览器，单击“工具”，选项。找到“字体”一栏，并把“默认字体”由“宋体”改为“微软雅黑”。</p>

<p>至此所有的设置均告完成。在浏览器中打开你喜欢的网页，就会发现上边的字体变得非常好看了。</p>

<p><strong>高级篇（<span style="color: #ff0000;">请慎用</span>）</strong></p>

<p>在浏览器中充分享受微软雅黑的快乐后，你一定会对XP系统里的字体——宋体嗤之以鼻。这时把系统字体换为微软雅黑就至关重要了。以下将介绍怎样把WindowsXP的默认字体改为“微软雅黑”。</p>

<p>在中文版的WindowsXP中，系统默认的字体是“宋体”，这个字体虽然可以在“桌面属性”中更改，但是很麻烦，而且很多程序都设定默认的字体是“宋体”，而不理会系统的字体是微软雅黑。这样实际使用下来会出现一半是宋体，一半是雅黑的窘况。一种最简单的办法就是，将“雅黑”的名字改成“宋体”，以此来“蒙骗”系统。不过Cfan上说过这种方法并不好，因为系统调用字体时会扫描字体文件中的相关信息来判断是否是需要调用的字体，而仅非通过文件名。如果用上面的方法来“蒙骗”系统，就会得到系统的“惩罚”：整个系统中文字是一片乱码。</p>

<p>所以，要想真正蒙骗过系统的火眼金睛，不仅要让微软雅黑替换掉宋体，还要把微软雅黑的相关信息也变为宋体的信息。《电脑爱好者》介绍过如何完成此项操作，具体内容在2006年第15期的31页。修改好了的字体有提供下载：
<a href="http://www.box.net/public/ojcqjjoxjs"><img src="http://www.box.net/index.php?rm=box_v2_file_button&amp;text=simsun.rar&amp;author=acesolo@gmail.com" alt="" border="0" /></a></p>

<p>替换步骤：先将“宋体” SIMSUN.TTC文件备份，再利用DOS启动盘引导后进入fonts目录进行字体的替换。</p>

<p>重起机器后，如果你看到的是美丽清澈的“微软雅黑”，那么恭喜恭喜，你可以永远告别“宋体”了！</p>

<p><span style="color: #0033ff;">Update(2006-9-15)</span></p>

<p>由于不同显示器在性能上的差异，导致某些电脑在打开ClearType后出现字体模糊的情况。如出现这种现象，请下载微软推出的ClearType调节程序。安装完成后在控制面板增加一个ClearType Tuning的按钮，双击之后请按照提示对ClearType进行优化。</p>

<p><a href="http://www.box.net/public/okkll4qet1"><img src="http://www.box.net/index.php?rm=box_v2_file_button&amp;text=Clear%20type%20Tuning.rar&amp;author=acesolo@gmail.com" alt="" border="0" /></a></p>
