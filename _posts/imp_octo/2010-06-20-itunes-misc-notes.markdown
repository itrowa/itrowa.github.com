---
layout: post
title: iTunes札记：选集、ID3标签、多个表演者及更多
categories:
- ! '@奇怪的评测、体验和心得'
- Journal
tags:
- 媒体播放
- 管理
published: true
comments: true
---
<p>自从我使用iTunes来接管音乐库管理以来，我电脑上的音乐库到目前为止都运行得非常美好。在音乐库管理方面，我严格遵循着自己制定的法则，那就是当有新的音乐时，我会在添加它们到媒体库之前，花一点儿时间来完善这些音乐的标签和文件名，然后放到以专辑名为名称的目录中。这样，只要在处理新东西的时候稍微花一点儿时间整理一下，就能一劳永逸，这绝对是非常美好的事情。</p>

<p>这次我想说说在整理音乐库的时候，我遇到的一些实际问题，以及可能的解决办法。毕竟“管理方案”总是人想出来的，不可避免地会有不周全的地方，当出现一些现在的方法不能完成的新情况时，就是动手改进管理方案的时候了。</p>

<p><strong>1. 选集</strong></p>

<p>在<a href="http://trowa.org/archive/671.html">《我的数字音乐库管理经验（二）》</a>中，我提到了iTunes这个软件比较独特，专辑名一样的歌曲都不能算是一张专辑的，非得是专辑名和表演者都一致，才能算一张专辑。现在问题就来了。</p>

<p>有这样一张专辑：<a href="http://www.amazon.co.jp/%E3%83%95%E3%82%B8%E3%83%86%E3%83%AC%E3%83%93%E7%B3%BB%E5%88%97%E3%83%89%E3%83%A9%E3%83%9E-%E9%9B%BB%E8%BB%8A%E7%94%B7-%E3%82%AA%E3%83%AA%E3%82%B8%E3%83%8A%E3%83%AB%E3%83%BB%E3%82%B5%E3%82%A6%E3%83%B3%E3%83%89%E3%83%88%E3%83%A9%E3%83%83%E3%82%AF-TV%E3%82%B5%E3%83%B3%E3%83%88%E3%83%A9/dp/B000A3H62W">フジテレビ系列ドラマ 電車男 オリジナル・サウンドトラック [CD+DVD] [Compilation] [Limited Edition] [Soundtrack]</a>。这肯定是一张专辑吧。可是里面不同的歌曲对应着不同的表演者，按照iTunes的对应法则，这张可怜的专辑就要被拆分成好几张同样名称的不同专辑了……</p>

<p>iTunes提供了消除这种毛病的办法。将所有需要合并到一张专辑里面的歌曲全部选中，右击，选择“Get Info”，在出现的菜单中，切换到“Options”选项卡，找到“part of  a compliation”（加入选集），改成“Yes”，再OK，就行了。</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/加入选集.jpg"><img class="alignnone size-full wp-image-729" title="加入选集" src="http://trowa.org/wp-content/media/2010/06/加入选集.jpg" alt="" width="558" height="434" /></a></p>

<p>经过如上改动的歌曲，在iTunes里面会成为一类特殊的专辑 - “选集”。在iTunes中浏览专辑时，你会发现这些在表演者一栏中，具体的表演者会被“various artists”替代：</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/Various-Artists.jpg"><img class="alignnone size-full wp-image-730" title="Various Artists" src="http://trowa.org/wp-content/media/2010/06/Various-Artists.jpg" alt="" width="336" height="404" /></a></p>

<p>按我的理解，凡是勾选了“加入选集”的歌曲，在划分专辑的时候，iTunes就会忽略掉这些歌曲对应的表演者，而只识别“专辑名”这个字段了，就和普通播放软件的理念一样。这就是“选集”在iTunes里面的作用。</p>

<p><strong>2. 解决ID3标签不兼容的问题</strong></p>

<p>我的电脑上老是有些歌曲，它们的标签信息在iTunes或者Foobar2000等软件中都能正常显示，但是在Windows Media Player或者是Windows资源管理器中（其实是一个东西）无法显示。这个问题苦恼了我很久，但是最后我也找到了答案。</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/Windows里面无法识别1.jpg"><img class="alignnone size-full wp-image-731" title="无法识别的ID3信息" src="http://trowa.org/wp-content/media/2010/06/Windows里面无法识别1.jpg" alt="" width="459" height="192" /></a></p>

<p>原来，ID3标签分为ID3v1，ID3v2.3、 ID3v2.4等很多版本。古老的Windows只能支持ID3v1和ID3v2.3这样古老的版本（号称最猛的Windows 7也不例外），而iTunes和Foobar2000等软件都能很好支持ID3 v2.4。所以遇到一些标签版本是2.4的，Windows当然只能视而不见了。</p>

<p>解决的办法是把所有的歌曲的标签都转换为ID3 v2.3的。利用<a href="http://www.mp3tag.de/en/">Mp3Tag</a>这个软件就可以轻松做到。具体转换也很简单，安装好mp3tag后，把要转换的mp3文件拖到主窗口去，然后选择具体要转换的文件（全选即可），按“Ctrl+S”保存，这样就能重写这些文件的ID3信息为2.3版的了。</p>

<p>转换后的文件，可以在Windows里面完美显示：</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/转换后可以完美识别.jpg"><img class="alignnone size-full wp-image-732" title="转换后可以完美识别" src="http://trowa.org/wp-content/media/2010/06/转换后可以完美识别.jpg" alt="" width="565" height="288" /></a>
<p style="padding-left: 30px;">进阶阅读：ID3的版本问题其实是个非常令人头疼的问题。最原始的ID3v1功能是在有限，比如支持的字符数太少，很多歌曲的歌名都显示不全；随后而来的ID3v2.3解决了这些问题，但是这种规范支持的编码太多太乱，Unicode字符集也仅支持UTF-16，这导致了很多乱码问题，用Linux的同学们都恨死它了；后来推出的ID3 v2.4才正式支持UTF8。可惜的是2.4版的规范还不是很普及，一般的便携式mp3播放器以及Windows系统都没法读取。</p>
<p style="padding-left: 30px;">鉴于以上情况，选择UTF-16编码的ID3 v2.3是一个最保险的方案了。UTF-16保证了尽可能不出现乱码；而ID3 v2.3保证了最强的兼容性。mp3Tag的编码保存方案，正是写入UTF-16的ID3 v2.3标签：</p>
<p style="padding-left: 30px;"><a href="http://trowa.org/wp-content/media/2010/06/mp3-tag-默认设置.jpg"><img class="alignnone size-full wp-image-733" title="mp3 tag 默认设置" src="http://trowa.org/wp-content/media/2010/06/mp3-tag-默认设置.jpg" alt="" width="550" height="462" /></a></p>
<strong>3. N个表演者的困惑</strong></p>

<p>这个世界上还有一种叫“合唱歌曲”的东西，就是一首歌曲，是双人合唱，甚至是多人合唱。</p>

<p>比如我就有一张这样的专辑，名字叫“Metal Gear Solid 2 Sons of Liberty Original Soundtrack”，其中一首曲目““Metal Gear Solid” Main Theme”的表演者就是两个人：TAPPY和Harry Gregson-Williams。可是“表演者”只有一个框，怎么填入多个人呢？在Windows里面，是可以直接在一个框里面输入多个表演者的：</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/编辑属性.jpg"><img class="alignnone size-full wp-image-726" title="属性里面，可以指定多个表演者。" src="http://trowa.org/wp-content/media/2010/06/编辑属性.jpg" alt="" width="377" height="515" /></a></p>

<p>可以看出，不同的表演者之间是用<code>;</code>连接起来的。而Windows在逻辑上把这一行字识别成了2个人。</p>

<p>在iTunes里面可就不支持这个办法了，笨笨的iTunes用一个"/"来替换掉了“;”并且把“TAPPY/Harry Gregson-Williams”识别成了一个人。虽然通过搜索TAPPY或者搜索Harry Gregson-Williams都能找到这首歌曲，但是，iTunes并没有把它们分成真正意义上的两个人。这也许是ID3标签在设计的时候就没有考虑到的细节：“表演者”这个字段只有一个，但是遇到多个表演者的时候，不得不采取折衷的手段（例如在要分开的人中间加上“;”），但是这些手段并没有得到所有软件的共识，不能算是最好的解决方案吧。</p>

<p><strong>4.多张CD的专辑也有麻烦</strong></p>

<p>iTunes管理专辑的时候，遇到多张CD的专辑的情况，应当是专辑名一致，而光盘编号设置为不同的值，这样就能正确把多张CD纳为一张专辑了。</p>

<p>但是……</p>

<p>我总是会遇到新的麻烦。拿这张《放課後ティータイム》来说，它是2CD的，但是，CD1和CD2拥有着不同的名字，CD1的名字叫Studio Mix，CD2的名字叫Live Mix：</p>

<p><a href="http://trowa.org/wp-content/media/2010/06/112.jpg"><img class="alignnone size-medium wp-image-728" title="放課後ティータイム封底" src="http://trowa.org/wp-content/media/2010/06/112-300x232.jpg" alt="" width="300" height="232" /></a></p>

<p>但是，它们虽然名字不同，但是确实是同一张专辑。如果按照音乐管理法则的桎梏，要么抛弃每一张CD的名字，要么把它们变成2张不同的专辑。总之，没有一个完美的解决办法。</p>

<p>在音乐库管理里面，我认为实际情况总是比理论上要复杂很多倍。上面的例子就看出了，基于ID3编码方案的元数据管理其实还是无法应对所有的情况，尽管人们总是费劲脑子想要将世界上的所有事物都用数据库管理起来，很多时候还是力不从心啊。</p>

<p>一些进阶阅读材料，以供参考：</p>

<p><a href="http://www.linux-wiki.cn/index.php/Mp3%E6%A0%87%E7%AD%BE%E4%B9%B1%E7%A0%81%E9%97%AE%E9%A2%98%E5%88%86%E6%9E%90%E4%B8%8E%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88">Mp3标签乱码问题分析与解决方案</a></p>

<p><a href="http://www.unicode.org/faq//utf_bom.html">UTF-8, UTF-16, UTF-32 &amp; BOM</a></p>

<p><a href="http://www.ilounge.com/index.php/articles/comments/ask-ilounge-12-7-07/">Ask iLounge 12-7-07</a>（关于选集问题的问答）</p>
