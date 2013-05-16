---
layout: post
title: 在Ubuntu桌面上跑WordPress
categories:
- Journal
tags: []
published: true
comments: true
---
<p>即使是在本机上建WordPress测试站点，我也希望有个标准的LAMP平台。我原本以为在最标准的Linux上搭WordPress不是件容易的事，哪知道装了Ubuntu后，亲自装下来，才发现这一切都是如此简单。除了下载的时间，整个安装配置过程甚至还不到2分钟……</p>

<p><em>参考资料：<a href="http://www.osxcn.com/ubuntu/ubuntu-feisty-fawn-server.html">http://www.osxcn.com/ubuntu/ubuntu-feisty-fawn-server.html</a> </em></p>

<p>1、打开新立得软件包管理器，－编辑 －使用任务分组标记软件包 －勾选 LAMP Server，如下图：</p>

<p><a href="http://photo8.yupoo.com/20070626/162831_644175898_vzewfhpt.jpg"><img title="screenshot" src="http://photo8.yupoo.com/20070626/162831_644175898_m.jpg" alt="screenshot" width="240" height="180" /></a></p>

<p>2、到客厅泡杯茶或者找点游戏消磨时间。</p>

<p>3、启用 mod_rewrite 模块</p>

<p>sudo a2enmod rewrite</p>

<p>4、配置 apache2.conf</p>

<p>sudo gedit /etc/apache2/apache2.conf</p>

<p>去掉 AddHandler cgi-script .cgi 前的注释 “#”。</p>

<p>然后在任意地方添加这么一段：<br />
&lt;Virtualhost localhost&gt;<br />
DocumentRoot /var/www/<br />
&lt;Directory /&gt;<br />
Options FollowSymLinks<br />
AllowOverride all<br />
&lt;/Directory&gt;<br />
&lt;Directory /var/www/cgi-bin/&gt;<br />
Options ExecCGI<br />
&lt;/Directory&gt;<br />
&lt;/Virtualhost&gt;</p>

<p>重启服务器<br />
sudo /etc/init.d/apache2 restart</p>

<p>搞定。</p>

<p>以后服务器会随Ubuntu的启动而自动启动。</p>

<p>接下来安装WordPress：</p>

<p>将解压的WordPress目录放到/var/www（假设是/var/www/wordpress/），再到http://localhost/phpmyadmin/建个数据库（用户名root，密码为空），然后配置一下WordPress的config文件，接着再到http://localhost/wordpress/wp-admin/install.php，怎么样，一个很熟悉的界面呈现在电脑屏幕前了～</p>
