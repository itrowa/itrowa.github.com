---
layout: post
title: 继续改进WordPress分类列表的函数
categories:
- Journal
tags: []
published: true
comments: true
---
<p>不久前<a href="http://www.trowa.org/archive/119.html">提到</a>过，想要不让分类列表的“Categories”标题显示出来，可以用php list_cats这个Template Tag来代替wp_list_categories，不过今天去Codex逛了一趟，发现这个函数并不是WordPress官方推荐的Tag，要想实现前面那篇文章的效果，可以使用这样的形式：</p>

<p><code>&lt;?php wp_list_categories('title_li='); ?&gt;</code></p>

<p>其实，只是多加了一个title_li=的参数罢了。</p>

<p><em>reference:<a href="http://codex.wordpress.org/Template_Tags/wp_list_categories">http://codex.wordpress.org/Template_Tags/wp_list_categories </a></em></p>
