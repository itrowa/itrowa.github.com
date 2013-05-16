---
layout: post
title: 垃圾软件Dr.com
categories:
- Journal
tags: []
published: true
comments: true
---
<p>Dr.com是大家熟知的应用于各大高校、小区、企业等单位进行上网认证的一款臭名昭著的垃圾客户端。在学校使用Dr.com半年来，我已经对这款垃圾软件的各种令人作呕的副作用感到厌恶和绝望了。在学校开始上网以来，我的电脑就出现了各种各样的莫名其妙的网络问题，即使是系统还原、重装系统、更换浏览器等排错也无济于事，但是当我回到家以后，连上了家里的ADSL这些现象统统消失。我这才醒悟，原来一切都是Dr.com这个垃圾软件的错。</p>

<p>那么Dr.com究竟干了些什么事，对我的系统造成了什么影响呢？
<ol>
	<li>严重干扰本地apache服务器的运行。Google就索引了一大堆<a href="http://www.google.com/search?hl=zh-CN&amp;q=dr.com++apache+%E5%86%B2%E7%AA%81&amp;btnG=Google+%E6%90%9C%E7%B4%A2&amp;lr=&amp;aq=f&amp;oq=">类似的帖子</a>。而且不同的机器会有不同的问题，我在本地使用XAMPP软件搭建的服务器就会用Mysql服务无法启动的问题，而且是只要Dr.com登录，这个问题就存在，一注销，Mysql服务器就能正常运行。<br />
出于个人兴趣，我经常在自己的本地机器跑Apache服务器，学习一下网页设计，但是每每无奈遭遇了这个垃圾软件，非常令人沮丧。</li>
	<li>文件上传出现问题。我使用Windows 7，而有段时间我发现无论在什么网站上上传东西都不能成功，当点击“上传”按钮后，上传进度条瞬间就达到100%，然而实际上根本没有任何文件上传成功过。回到家使用电信ADSL一切正常。</li>
	<li>无法使用Windows Update。Windows安全问题历来就是一个严重的问题，某些版本的Dr.com使得系统无法连上微软的更新服务器导致无法更新，从而加大了系统的安全风险。不仅如此，在使用Dr.com时，我还发现有时侯很难更新小红伞的病毒库。</li>
	<li>无法使用代理服务器。只要Dr.com在，无论是GAppProxy还是TOR，或者是别的代理软件，在非IE浏览器中都无法正常使用，使用代理服务器打开任何一个网页，都会弹出一个“application/octet-stream”的下载框。开始我还以为是我的系统有问题，可是回到家以后发现，还是一切正常。</li>
</ol>
使用Dr.com上网实在是一件非常悲惨的事情，时常会出现很多莫名其妙的其他问题，网上已经有了一箩筐。一个连最基本的上网的功能都做不好的解决方案，居然还拥有如此庞大的用户群和客户，实在令人感到费解。</p>

<p>对于这些莫名其妙的毛病，我现在暂时还没有什么好的解决办法。有一个第三方开发的Dr.com Client版本，据说能够解决很多问题，下载地址在：<a href="http://sourceforge.net/projects/drcom-client/">http://sourceforge.net/projects/drcom-client/</a>，官方主页是：<a href="http://www.drcom-client.org/zh_CN/index.html">http://www.drcom-client.org/zh_CN/index.html</a>，但愿这会是一个比较好的解决方案吧。</p>
