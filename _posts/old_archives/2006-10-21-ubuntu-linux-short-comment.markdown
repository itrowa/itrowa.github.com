---
layout: post
title: Ubuntu Linux初装手记
categories:
- Journal
tags: []
published: true
comments: true
---
<p>传说中的Ubuntu6.06终于寄到了我的手中，我本来是准备玩玩LiveCD就算了的，但是Ununtu对我的诱惑实在是太大了，一不留神，这家伙就被我装到了硬盘上。</p>

<p>记得4个月前我曾经装过RedHat9，也因此把一块硬盘上的数据全部弄报废了。为了不重蹈覆辙，这次安装Ubuntu我就格外小心了，具体过程是这样的：
<ol>
	<li>我目前是Windows，Windows所在的主分区不能动，所以在DOS下用PQ Magic在扩展分区上开出两个逻辑分区，一个300M左右（实际应调整为物理内存的1.5倍），文件系统为Swap，另一个分区6G，文件系统为“ext3”，挂载/。其实/home， /usr等目录都应该另外开分区来分别挂载的，但为了保险起见，还是用上面的方法好些。</li>
	<li>用Ubuntu的LiveCD光盘启动计算机，进入CD的菜单时选择“图形界面”。等加载完毕,就能使用了 。Ubuntu的界面非常漂亮，Gnome做出的GUI非常吸引我，所以我就此决定安装到硬盘上了。点击那个Install。耐心等待它加载吧。</li>
	<li>安装分为6步，其他几步不用多说，最重要的就是选择分区的那一块。安装到第5步，程序询问“您需要如何分区”时，选择第3个选项，“手动编辑分区表”。耐心等待第5步的“准备分区”出现，这里由于在DOS里面已经用PQ Magic做好了Linux所用的分区，所以不做任何调整，直接点下一步。</li>
	<li>这时就到了第5步的“准备挂载点”。如果不知道挂载点的知识，这里简单介绍一下：
<strong>在Linux里面，你是看不到诸如DOS与Windows里面的C：，D：，E盘等分区的，你会看见一个以“/”开头的目录结构，紧接着就是/home，/usr，/etc等下级目录。那么这些目录的真正位置在那个分区上呢？这就要引入“挂载”的概念。</strong><strong>挂 载是将目录关联到某个分区的过程。Linux的每一个目录都可以设置它所在的物理位置。比如说Linux的顶级目录“/”，如果你在安装的时候把它挂载到 C盘（也就是Linux所称的hda1）,那么"/"目录物理意义上的位置就在C盘上了,如果把"/home"目录挂载到D盘</strong><strong>（也就是Linux所称的hda5）</strong><strong>,那么"/home"目录物理意义上的位置就会在D盘。如果你硬盘上有足够多的分区，你就能把Linux的目录分配到这些分区上去，使得Linux更易于管理。
</strong></li>
	<li>有了上面的知识，这一步就很容易了，左边选择要挂载的目录，右边选择这个目录的物理位置。“/”就挂载在6G的ext3分区上，而swap挂载在那个300M左右的swap分区上。</li>
	<li>确认你的设置，开始安装。</li>
</ol>
安装过程比较漫长，用了大约1小时。期间Ubuntu会将GRUB设置为系统引导程序。所有安装完成后，系统提示重新起动，并且光驱自动弹出LiveCD。重新启动以后，一个崭新的OS就出现在你的眼前了。</p>

<p>总的来说，我的安装是比较成功的，硬盘也没有出现任何故障。 之前的RedHat带给我的痛苦经历，这次总算没有再次上演。Ubuntu带给了我很多惊喜，它那人性化的操作，友好的界面，完善的软件管理，实在让人很难拒绝这款“For human beings”的Linux。</p>

<p>再来几张图：</p>

<p><a href="http://photo9.yupoo.com/20061021/165525_2006669504_zqawnatm.jpg" rel="lightbox"><img src="http://photo9.yupoo.com/20061021/165525_2006669504_m.jpg" title="screenshot" alt="screenshot" /></a></p>

<p><a href="http://photo9.yupoo.com/20061021/165523_22356783_qrryexqp.jpg" rel="lightbox"><img src="http://photo9.yupoo.com/20061021/165523_22356783_m.jpg" title="screenshot" alt="screenshot" /></a></p>
