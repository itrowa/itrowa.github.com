---
layout: post
title: 用EasyPHP在本地调试Wordpress
categories:
- Journal
tags: []
published: true
comments: true
---
<p>前些日子因为一个插件弄得Blog后台乌烟瘴气,害得我费了九牛二虎之力才将其恢复了过来.现在想来，除了恢复和备份以外,更因该思量一下如何完全防止这种事件发生。最好的途径，就是在本机上进行WP的测试。由于WP需要PHP和MySQL的支持，而分别安装着几样又太麻烦，我们需要的是一款集成程度高的软件。终于，EasyPHP登场了。
<blockquote>EasyPHP 1.8 <font color="#666666">本软件帮助你使用PHP管理数据、开发站点和应用程序。</font>它是调试PHP程序的好东西，集成: Apache 1.3.27, PHP 4.3.3, MySQL 4.0.15, PhpMyAdmin 2.5.3  它在华军软件园的下载地址：<a target="_blank" href="http://www.newhua.com/soft/32078.htm">这里</a></blockquote>
安装十分方便，没有繁杂的设置，还真是Easy。安装好后EasyPHP后，紧接着就要安装Wordpress。首先在浏览器中打开http://127.0.0.1/mysql/进入PHPMyAdmin创建数据库。接着配置wp-config文件，数据库名就是刚才创建的数据库名，用户名改为root,密码改为空.接着把Wp的安装文件传复制到EasyPHP安装文件夹下的www目录。最后在浏览器中打开http://127.0.0.1/wp-admin/install.php完成Wordpress的安装。如果你把Wp的安装文件放到了www的下级目录，则对应的地址是http://127.0.0.1/目录名/wp-admin/install.php。这样本地调试Wordpress的准备工作就大功告成了，以后这里的WP就可以随便折腾了，完全不用担心带来麻烦！</p>
