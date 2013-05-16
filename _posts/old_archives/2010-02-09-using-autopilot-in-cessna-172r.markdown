---
layout: post
title: 在FS2004中使用Cessna 172R的自动驾驶仪
categories:
- 通用航空／航模／模拟飞行
tags: []
published: true
comments: true
---
<p>在飞行使用自动驾驶仪是一件非常令人惬意的事情，因为它将飞行员有限的精力得到了大大的解放，使得我们在驾驶飞机的时候不用再紧张地手握操纵杆来完成诸如“保持高度2500”、“保持航向134”等等枯燥而乏味的操作了。在一次航线飞行中飞机往往要跟踪很多VOR导航台、完成很多ATC的高度要求、速度要求，航向要求等，降落时还要跟踪ILS信号，更糟糕的是整个飞行过程中飞行员不仅要处理好这些东西，嘴里还要叽歪叽歪和ATC说个不停，副驾驶也要来瞎搅和，还要注意其它的灰机，要是没有自动驾驶接管一些简单的任务，恐怕飞行员的脑子是双核的都不够！</p>

<p>FS2004的插件飞机Flight 1 Cessna 172R Skyhawk里面模拟了一台KAP140 型号的自动驾驶仪，利用它能完成以下功能：
<ol>
	<li>水平导航，例如<strong>航向保持</strong>、跟踪<strong>VOR航道</strong>或者<strong>GPS路点（waypoint）</strong>、跟踪<strong>ILS</strong>的<strong>LOC信号</strong>，这样开飞机时就不用死盯着VOR指示器上可怜的CDI指针来保持航道了，也不用再为了保持一个特定航向而精疲力竭了，自动驾驶会掌管好飞机的水平位置和方向，你要做的就是监视好这些仪表。</li>
	<li>垂直导航，例如<strong>高度保持</strong>，ILS降落中的GS信号。</li>
	<li>速度控制？开玩笑，这玩意儿是没有的，这么便宜的飞机就将就点吧</li>
</ol>
在C172飞机里面，自动驾驶仪是装在了这个位置：</p>

<p><a href="http://trowa.org/wp-content/media/2010/02/where-is-AP.jpg"><img title="自动驾驶仪" src="http://trowa.org/wp-content/media/2010/02/where-is-AP.jpg" alt="" width="460" height="344" /></a></p>

<p>在模拟飞行中，可以按<strong>Shift+2</strong>打开机载导航设备面板，就能使用自动驾驶仪了。让我们先来看看它长的什么样：</p>

<p><a href="http://trowa.org/wp-content/media/2010/02/c172自动驾驶仪图.jpg"><img title="c172自动驾驶仪图" src="http://trowa.org/wp-content/media/2010/02/c172自动驾驶仪图.jpg" alt="" width="446" height="106" /></a></p>

<p>自动驾驶仪的主要按钮与功能如下：</p>

<p>1.总开关：<span style="color: #008000;"><strong>1按钮</strong></span>接通/切断自动驾驶仪。<strong>所有的自动驾驶仪都有一个“预设”的概念</strong>：那就是在使用自动驾驶仪前，先在机器里面设置好想要的高度、航向等，确认无误后，再行接通自动驾驶仪，而不是先接通了再去手忙脚乱设置参数。</p>

<p>2.高度保持：<span style="color: #008000;"><strong>2</strong></span>显示自动驾驶仪所选择的高度。当按下<span style="color: #008000;"><strong>3</strong></span>时，自动驾驶仪就会激活并且使飞机爬升/下降到这个高度，高度选择可以用<span style="color: #008000;"><strong>4旋钮</strong></span>，此外还能指定一个垂直速率（使用<span style="color: #008000;"><strong>5</strong></span>），选好的垂直速率会在<span style="color: #008000;"><strong>6</strong></span>显示。</p>

<p><a href="http://trowa.org/wp-content/media/2010/02/heading-sel.jpg"><img class="alignright size-full wp-image-554" style="margin: 10px;" title="航向选择" src="http://trowa.org/wp-content/media/2010/02/heading-sel.jpg" alt="" width="70" height="66" /></a>3.航向保持：使用航向保持模式时，首先要在航向指示器使用航向选择器（那个橙色的游标）选择一个航向，然后回到自动驾驶仪，猛击<span style="color: #008000;"><strong>7</strong></span>，飞机就会保持此特定的航向。再按一次<strong><span style="color: #008000;">7</span></strong>还会进入ROL模式。<strong>航向保持模式在自动驾驶里面是非常重要的，因为ATC会冷不防叫你“改变航向至XXX”之类的命令，如果使用自动驾驶仪的话，直接扭一下航向选择器就能轻松完成这些动作了。</strong></p>

<p>4.跟踪VOR或者ILS：调整好VOR或者ILS导航台的频率并激活时，点击<span style="color: #008000;"><strong>8</strong></span>可以跟踪VOR信号，点击<span style="color: #008000;"><strong>9</strong></span>可以跟踪LOC和GS信号。</p>

<p><a href="http://trowa.org/wp-content/media/2010/02/NAV-GPS-sel1.jpg"><img class="alignright size-full wp-image-553" style="margin: 10px;" title="NAV/GPS选择器" src="http://trowa.org/wp-content/media/2010/02/NAV-GPS-sel1.jpg" alt="" width="211" height="136" /></a>5.跟踪GPS路点：当使用GPS导航时，在飞机主面板拨动“Nav/GPS开关”激活GPS模式，自动驾驶仪就可以跟踪GPS的路点，而不是VOR信号了。</p>

<p>自动驾驶仪还有个反向航路进近模式（<span style="color: #008000;"><strong>按钮10</strong></span>），这种模式下定位信标的指示是和正常情况下是相反的，这个用得很少。</p>

<p>Cessna 172R飞机上的自动驾驶仪功能差不多就是以上所说的，虽然简单但是很实用，学会了它，以后大型客机的自动驾驶仪学习起来就要容易些。有了自动驾驶仪的帮助，进行长距离长时间的航线飞行应该不会太累了。</p>
