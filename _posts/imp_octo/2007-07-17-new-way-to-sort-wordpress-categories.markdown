---
layout: post
title: 新方法列出WordPress分类
categories:
- Journal
tags: []
published: true
comments: true
---
<p>设计主题时，一般情况下都是调用wp_list_categories('') 这个函数来显示WordPress的分类项目。它生成的样式是类似这样的：
<img title="before" src="http://photo8.yupoo.com/20070717/193518_1460470241_ttmojalt.jpg" alt="before" />
不幸的是，我写的主题需要分类列表横向排列，而且那个“Categories”对于我来说是多余的。我去WordPress Codex上翻了一下wp_list_categories('')的用法，发现还没有隐藏这个Categories的参数。难道就此罢休？</p>

<p>转念一想，既然wp_list_categories('')没法满足我的需求，何必再一颗树上吊死呢。后来我终于找到了一个既能显示分类列表又不会生成“Categories”的妙招，代码如下：</p>

<p>&lt;ul&gt;<br />
&lt;?php list_cats(FALSE, '', 'ID', 'asc', '', TRUE, FALSE, FALSE, FALSE, TRUE, FALSE, FALSE, '', FALSE, '', '', '1,33', TRUE); ?&gt;<br />
&lt;/ul&gt;</p>

<p>我们先手动把ul写好，剩下的li由上面的那一长个WordPress函数来写，这样既达到了目的，又不会让那个讨厌的“Categories”出现。</p>

<p>改进后：</p>

<p><img title="after" src="http://photo8.yupoo.com/20070717/195106_725429771_wmtvwdpz.jpg" alt="after" /></p>

<p>技术性问题解决了，接下来调整一下CSS，就完美了。</p>

<p><em>reference:<a href="http://codex.wordpress.org/Designing_Headers">http://codex.wordpress.org/Designing_Headers </a></em></p>
