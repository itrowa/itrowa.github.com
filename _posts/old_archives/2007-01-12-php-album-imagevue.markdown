---
layout: post
title: 试用超酷PHP相册imageVue
categories:
- Journal
tags: []
published: true
comments: true
---
<p><a href="http://photo4.yupoo.com/20070112/142630_353466919_tndbacla.jpg"><img src="http://photo4.yupoo.com/20070112/142630_353466919_m.jpg" title="screenshot" alt="screenshot" border="0" /></a></p>

<p><a href="http://photo4.yupoo.com/20070112/142629_1570232704_wwwvhtce.jpg"><img src="http://photo4.yupoo.com/20070112/142629_1570232704_m.jpg" title="screenshot" alt="screenshot" border="0" /></a></p>

<p>第一眼看到imageVue的演示，给我的感觉实在是无法形容，因为哪怕是本地计算机的相册程序都无法与imageVue媲美。imageVue采用PHP脚本，无需数据库，使用Flash界面，效果十分华丽。如果需要一款用于展示的相册程序，恐怕没有能和imageVue匹敌的程序。好，无需多说，喜欢的话可以先到<a href="http://ablum.acesolo.cn/">这里</a>体验一番。</p>

<p>至于安装的话，还是比较方便的，网上教程太多了，我就懒得写了。推荐这个教程。（<a href="http://www.nuocn.com/blog/read.php/101.htm">链接</a>）<br />
不过这里还是想多说两句：
<ol>
	<li>这个Flash相册效果确实没得说，但其实用性是绝对不大。由于安全性等诸多方面因素，我的建议是只拿它来当一个展示用的相册。</li>
	<li>还是安全方面的。如果希望在线管理的话，千万记得要<strong>修改登陆密码</strong>。打开admin/passwords.php，你应该会看到如下代码：&lt;?php<br />
// Nulled by getout<br />
$data['guest'] = 'guest';<br />
$data['admin'] = '*';<br />
?&gt;</li></ol></p>

<p>找到admin，把它修改为只有自己知道的字符。请注意imageVue的登陆只需要一个密码（不是传统的帐户名+密码），默认就是admin。所以……如果不想被黑，赶快改吧。<br />
改完之后再<strong>将admin目录改名</strong>，以免目录下的passwords.php被人下载。
	<li>既然是图片展览，主人肯定希望参观的人能在欣赏图片的同时聆听优美的旋律。把MP3上传到mp3/文件夹（可以上传多首），再修改imageVue根目录下的config.ini,找到audio = false，把false该为true。这样就实现了歌曲自动开始播放。上传的MP3文件最好不要太大，不然要杀死小猫的。我的建议是把MP3进行一下格式转换，只要保证有基本的音质就OK了。</li>

关于imageVue的介绍基本就是这些，若哪位同学有什么好的心得请一定要告诉我啊。</p>
