---
layout: post
title: LaTeX与Word（源代码与所见即所得）谁更好？
categories:
- Journal
tags: []
published: true
comments: true
---
<p>我还记得几周前我曾经狂热地表示了我对LaTex或者Markdown这种标记语法的支持(<a href="http://dynamii.tk/2012/04/12/word-latex-%e5%92%8cdocbook/">#</a>)，甚至还扬言一定要建立一个只能写标记语言的博客，于是我在毕业设计的文献翻译环节中开始了我的实践。</p>

<p>我的这篇文献翻译，公式相当的多，上标下标，矩阵……该有的东西都有了，开心的我一边儿查询LaTeX语法，一边照着敲代码，心想，哈哈，LaTeX和Markdown就是爽，纯键盘就把我要的公式敲完了，如果是用Word，我还必须用该死的鼠标来做上下标，那将多么影响翻译的效率啊。</p>

<p><img src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2012/LaTeX_and_Word.jpg" alt="" /></p>

<p>倒腾了半天我总算在Vim里面把翻译的大概完成了。这个时候，我好像不这么想了……因为，这些标记语言是需要编译的~！只看源格式的话，我不知道BOSS会不会往我脑袋上扔反斜杠。如果说Markdown语法的“源文件”看起来还比较易读的话，那么LaTeX的“源代码”看起来就惨不忍睹了，尤其是在表述分式或者矩阵等等式子的时候。</p>

<p><img src="http://i1198.photobucket.com/albums/aa450/itrowa/blog_post_2012/LaTeX_and_Word_2.jpg" alt="" /></p>

<p>现在想一想当初推广LaTeX的人宣传的是什么——更好的排版。看过一些成品的我自然也会为了LaTeX的排版而喝彩，但是，LaTeX的另一个让人吐血又极度让人兴奋的特性是公式的输入。</p>

<p><strong>为什么我会喜欢这种方式的输入？</strong>那它和Word比较，Word输入上下标，分数，求和，积分等都需要鼠标操作和定位，LaTeX中统统都是敲字符搞定。</p>

<p><strong>为什么我不喜欢这种方式的输入？</strong>敲完了LaTeX代码，在输出正式的文档以前，你只能看到那堆破代码，如果要检查错误的话我想这是一场噩梦。但Word在痛苦的操作以后，就能看到真正可以阅读的公式了。多爽！</p>

<p>最后我找到了一个完美的解决方案，要是能在Word中插入的公式的时候使用LaTeX语法，输入完成后自动转换为Word中的公式，检查错误的时候又自动变成LaTeX代码，岂不两全其美？</p>

<p>这便是我得到的答案——MathType了。使用这玩意儿就可以轻松把LaTeX格式的公式转换成Word里面的公式对象，这算是部分解决了公式输入和查看的矛盾，这样，文章排版还是拿给傻乎乎的Word来做，但是公式的输入可以用MathType来搞定。</p>

<p>这儿有文章可以参考下~
<ul>
	<li><a href="http://hi.baidu.com/mecfan/blog/item/a6e0d0083dc2718fd1581b87.html">http://hi.baidu.com/mecfan/blog/item/a6e0d0083dc2718fd1581b87.html</a> MathType转化为LaTeX公式语言 图解教程（转载）</li>
	<li><a href="http://hi.baidu.com/xuzuozhou/blog/item/030d9c8ba3c41d739e2fb44f.html">http://hi.baidu.com/xuzuozhou/blog/item/030d9c8ba3c41d739e2fb44f.html</a> [转]使用MathType输入数学公式的技巧</li>
</ul>
&nbsp;</p>
