---
layout: post
title: Linux下听音乐有点麻烦
categories:
- Journal
tags: []
published: true
comments: true
---
<p>说到多媒体应用，最基本的三项莫过于视频，图片和音乐了。在Linux下，视频播放可以用大名鼎鼎的mplayer搞定，图片管理可以借助免费的Google Picasa，可是，说到音乐播放，我还真是拿不出个有影响力的软件来。</p>

<p>Linux下的音乐播放器可分为这么几种，一种是偏重于音乐播放的，例如xmms系，停止开发后，软件改成了beep-media-player，而后又衍生出audacious等。它们在界面上和Windows下的Winamp非常相似，由软件主界面块（控制播放、暂停、循环模式、定位等），播放列表块和均衡器块构成，这样的软件通常都能拆成3个部分。另外一种是偏重于音乐管理的，类似于Windows上的Windows Media Player，Mac上的iTunes，这类软件都有一个设计成熟的媒体库，方便以作家、流派、专辑等各种形式索引电脑内的音频文件。</p>

<p>这两种类型的软件都有一个共同的通病：它们对音频文件的标签编码支持度不良。软件读取很多mp3文件和ape文件时得出的信息都是乱码。（至于乱码的原因可以参考<a href="http://www.osxcn.com/ubuntu/mp3-tag-encoding.html">这里</a>。）mp3的编码大致可分为这几种：ID3v1，ID3v2，以及APEv2。其中APEv2的标签编码是统一的utf8，这意味着全球统一，任何一款支持读取APEv2标签的软件都不会出现乱码情况。而ID3v1和ID3v2的编码是不统一的，许多在中文Windows上压制mp3的作者缺乏一点专业精神，他们使用软件默认的GBK编码来写入ID3v1/ID3v2，读取时，Windows下的音乐播放软件能职能判断mp3标签编码并正确显示，而linux下的软件无法判断这种标签的编码。这些音乐播放软件，很多不支持读取<span lang="EN-US">mp3</span>的<span lang="EN-US">APEv2</span>标签，而且又不会智能判断<span lang="EN-US">mp3</span>的<span lang="EN-US">ID3v1/ID3v2</span>标签编码 并正确显示，当然就是乱码。由此可见，<span lang="EN-US">linux</span>下的音乐播放软件，由于这些原因，它们对标签的支持度不良，造成了易用性的降低。<span lang="EN-US"> </span>此外，由于种种原因，<span lang="EN-US">linux</span>下的音乐播放软件给我的感觉都不是特别好。这里，我还是说说我心中理想的音乐播放软件，都有哪些功能：
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>1、</span></span>最基本的几项：控制播放、暂停、停止、定位。</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>2、</span></span>能够支持多种音频格式：<span lang="EN-US">mp3</span>，<span lang="EN-US">wma</span>，<span lang="EN-US">ogg</span>，<span lang="EN-US">ape</span>，<span lang="EN-US">tta</span>，<span lang="EN-US">flac</span>等，并支持<span lang="EN-US">cue</span>读取。</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>3、</span></span>播放列表功能：能将用户选定的音乐文件加入播放列表，还要支持<span lang="EN-US">cue</span>读取；对于标签编码，要能良好兼容；能添加多个播放列表，并方便地在多个播放列表中切换；有顺序播放、循环播放等多种播放模式，还要能快速查找定位到用户制定的音乐文件。</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>4、</span></span>均衡器：提供一个基本的均衡器以供调节音效。</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>5、</span></span>媒体库：提供媒体库功能，能以作家、专辑、时间、流派、用户喜好度等多种方式索引和管理电脑中的音乐；能和播放列表有机结合；能方便地修改标签；</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>6、</span></span>格式转换：能在<span lang="EN-US">wav,mp3,ape,flac</span>等格式间进行转换，能支持以<span lang="EN-US">cue/</span>标签作为转换后音频文件的文件名。</p>
<p style="margin-left: 18pt; text-indent: -18pt"><span lang="EN-US"><span>7、</span></span>附加功能：电台，专辑封面等。</p></p>

<p>能做到前<span lang="EN-US">5</span>点，我认为这就是一个非常好的音乐播放软件了，能全部做到，这个播放软件堪称完美。软件范例，<span lang="EN-US">foobar</span>，千千静听就是很好的例子。</p>
