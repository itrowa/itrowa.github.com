---
layout: post
title: 系统大清理
categories:
- Journal
tags: []
published: true
comments: true
---
<p>从我机器上第一次安装windows 7 到现在，大概也有一年的时光了！现在回想起以前的一些事情，真是觉得好笑，比如一个破破烂烂，摇摇欲坠的XP系统，明明越用越坏，还拼命地往里面塞各种软件……</p>

<p>自从用上了windows 7以来，我也慢慢习惯了系统内置的各种功能，这下我终于从折腾的泥沼里面跳了出来。说到底，“折腾”到底是什么意思？不就是几个软件装来装去，电脑的文件移动来移动去么？这样的“折腾”只能说是浪费时间而已。与其有这点时间干这点破事，还不如好好静下心来，研究自己真正感兴趣的事情呢。</p>

<p>所以，我现在对系统的“折腾”便停止了下来。现在对于系统的维护，大多是基于“不得不做”的必要性，例如每周整理一下文件（好像给房价打扫卫生一样），大概每隔一个月卸载一些不用的软件（好像是把不要的家具扔了？）。大致就是如此。</p>

<p>最近干的几件事情，第一件就是把用了N年的<a href="http://www.google.com/search?q=GDI%2B%2B&amp;ie=utf-8&amp;oe=utf-8&amp;aq=t&amp;client=firefox-a&amp;rlz=1R1GGLL_zh-CN___CN387">GDI++</a>给扔了。
<blockquote>MacType原名（GDI++），字体渲染引擎，能使文字显示得更清晰、更有立体感。GDI++是一个开源项目，它能接管Windows系统的GDI字体渲染功能，实现比Mac系统更华丽的字体渲染效果！使用PC的朋友再也不需要羡慕 Mac上清晰的中文字体了，因为GDI++是有过之而无不及的。</blockquote>
GDI++让我的电脑字体的显示效果有了一个质的飞跃，在特别是对网页字体的渲染让人是爱不释手。可是毕竟是第三方的字体渲染引擎，首先它没法渲染系统里面所有的字体，比如iTunes，那个讨厌的宋体死活都还是那个样子。第二，有些软件使用GDI++渲染会出现问题，比如Treesize(一个磁盘占用分析软件)，使用GDI++后，图表里面的中文字体变成了乱码。卸载后恢复正常：</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/Treesize乱码.jpg"><img class="alignnone size-full wp-image-744" title="Treesize乱码" src="http://trowa.org/wp-content/media/2010/07/Treesize乱码.jpg" alt="" width="485" height="344" /></a></p>

<p>还有电路仿真软件Multisim，这个软件本来是非常好的，电路放大了1万倍，里面的字母和图形都应该是清晰的，可惜在GDI++的作用下，放大了的电路全部是锯齿-_-。后来卸载了GDI++，发现multisim原来如此美好，才意识到是GDI++的问题。</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/Multisim.jpg"><img class="alignnone size-full wp-image-746" title="Multisim" src="http://trowa.org/wp-content/media/2010/07/Multisim.jpg" alt="" width="519" height="372" /></a></p>

<p>第二件事是把谷歌拼音个卸载了。换了个QQ拼音。为什么呢？</p>

<p>谷歌拼音的确比较简洁大方，可是从某一天开始，谷歌个人词库无法正常同步了（又怀疑是XX部门）。再加上其它输入法也有一些很不错的人性化功能，有一次无意中用了下QQ拼音，感觉真不赖。虽然现在朝腾讯吐口水的很多，不过说实话，最近QQ的软件确实做得质量不错，的确是把“先抄袭，再创新”这条发家之路走到极致了。</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/QQ拼音.jpg"><img class="alignnone size-full wp-image-747" title="QQ拼音的双拼设置" src="http://trowa.org/wp-content/media/2010/07/QQ拼音.jpg" alt="" width="424" height="129" /></a></p>

<p>例如，我平常使用的是自然码双拼方案，可我女朋友还停留在全拼阶段，两人共用电脑的话，不得打架了？其实用这个“使用全拼双拼混合输入”就能比较完美解决了。其它还有很多不错的功能，值得多多挖掘。</p>

<p>再有就是把电脑里面不经常用的全部扔掉。这样竟然腾出了将近50G的空间，真是华丽的一击啊：</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/腾出的空间.jpg"><img class="alignnone size-full wp-image-748" title="腾出的空间" src="http://trowa.org/wp-content/media/2010/07/腾出的空间.jpg" alt="" width="531" height="495" /></a></p>

<p>最后我再想说一下关于英文版的Windows系统。不知道大家用一些软件的时候是否会出现软件界面上的单词显示不全的情况，特别是一些布局比较紧凑的软件，例如win7 codecs 的设置页面：</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/显示不完整的win7-codecs.jpg"><img class="alignnone size-full wp-image-749" title="显示不完整的win7 codecs" src="http://trowa.org/wp-content/media/2010/07/显示不完整的win7-codecs.jpg" alt="" width="492" height="330" /></a></p>

<p>注意看上面的界面中，有些英文单词过长，显示得不完全。但是在英文版的系统中：</p>

<p><a href="http://trowa.org/wp-content/media/2010/07/显示完整的win7-codecs.jpg"><img class="alignnone size-full wp-image-750" title="显示完整的win7 codecs" src="http://trowa.org/wp-content/media/2010/07/显示完整的win7-codecs.jpg" alt="" width="496" height="328" /></a></p>

<p>则一切正常。这是我原来百思不得其解的问题，一直搞不清楚为什么有些软件像被切了一个边一样。现在相信答案终于明了了：英文软件是外国佬写的，而外国佬用的是英文版的系统。英文版的系统中的英文字体和中文系统中的英文字体显示是不一样的，英文系统中的字体会小不少，所以一个在英文系统里面显示得正常的软件，放到中文环境里面会出现某些问题。</p>

<p>为了一劳永逸地解决这个问题，我干脆去弄了一套Windows 7的英文语言包，把系统换成了英文版的。这样可以学点英语，英语的字体也更舒服了。</p>
