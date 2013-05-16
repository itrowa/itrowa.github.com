---
layout: post
title: 再次让Windows7的桌面更高效化
categories:
- Journal
tags:
- windows
- 管理
- 设计
published: true
comments: true
---
<p>当人类欲望和现实冲突……不满便开始了……</p>

<p>使用Windows 7已经3个月了，我总体的感觉是Windows 7确实添加了很多非常人性化的功能，比如在启动程序方面，这个“超级任务栏”上就可以摆放常用的程序，像极了苹果的Dock，而又保持了Windows任务栏的外观，真是佩服微软的创意啊。</p>

<p>可是对于我这种装几十个软件的人来说……任务栏还是窄了点，因为一排任务栏，也只能放10多个程序，而且东西一多，非常凌乱，看来在外观上，还是敌不过苹果的Dock啊，Dock可是放的程序越多，越好看～</p>

<p><a href="http://trowa.org/wp-content/media/2009/11/sshot-2009-11-10-22-26-161.jpg"><img class="alignnone size-full wp-image-264" title="Windows7 任务栏" src="http://trowa.org/wp-content/media/2009/11/sshot-2009-11-10-22-26-161.jpg" alt="Windows7 任务栏" width="460" height="287" /></a></p>

<p>这样一来，不是又回到了XP的混乱年代了嘛？？</p>

<p>其实对于启动快捷方式，Windows就提供了一种类似于Win+R的功能，那就是直接按Win键调出开始菜单，然后直接搜索要的东西，系统便会即时搜索了。不过我觉得这个搜索框太不“专一”了，不仅会搜索开始菜单的程序，还把其它文件也给你翻出来，而且速度还有一定的延迟。所以我必须找更专业的方法。</p>

<p>答案就是Launchy。这个类似于Win+R的高级货可以索引开始菜单以外的快捷方式，比如我就把常用的绿色软件的快捷方式放到一个地方，还可以自己去名字，然后定义Win+Esc键（很顺手的），在需要的时候调出Launchu的主界面，启动Photoshop只要输PS回车，要打极品飞车直接NFS回车，太爽啦！</p>

<p>不过这种方法也不是万能的，因为人的需求是无限的……比如在设计网页的时候，常常需要访问Xampp目录，访问不同版本的WordPress主题目录，所以需要一个快速访问这些地方的方法。把这些目录的快捷方式放到桌面上？这太低级了。用Launchy？因为这些不同的目录他们的名字却一样，这就给识别不同的目录带来了一定的困难。</p>

<p>不过办法总比困难多，利用Windows 7的资源管理器的收藏夹功能就很好：</p>

<p><a href="http://trowa.org/wp-content/media/2009/11/sshot-2009-11-10-22-56-11.jpg"><img class="alignnone size-full wp-image-265" title="搜藏夹访问常用位置" src="http://trowa.org/wp-content/media/2009/11/sshot-2009-11-10-22-56-11.jpg" alt="搜藏夹访问常用位置" width="460" height="330" /></a></p>

<p>不过我的思想不是直接在侧边栏打开相应的链接，而是把收藏夹缩起来，需要的时候，点击“收藏夹”进入，在把收藏夹里的项目以“详细信息”的模式显示，这样，你要的是哪个目录，不就一目了然了。不过，这个方法需要点三下：打开“资源管理器”→打开“收藏夹”→打开你要的目录。累啊。</p>

<p>还有一个解决办法，就是让这个收藏夹最小化在任务栏……</p>

<p><img id="myFxSearchImg" style="border: medium none; position: absolute; z-index: 2147483647; opacity: 0.6; display: none;" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAADsElEQVR4nK2VTW9VVRSGn33OPgWpYLARbKWhQlCHTogoSkjEkQwclEQcNJEwlfgD/AM6NBo1xjhx5LyJ0cYEDHGkJqhtBGKUpm3SFii3vb2956wPB/t+9raEgSs52fuus89613rftdcNH8/c9q9++oe/Vzb5P+3McyNcfm2CcPj9af9w6gwjTwzvethx3Bx3x8xwd1wNM8dMcTNUHTfFLPnX6nVmZpeIYwf3cWD/PhbrvlPkblAzVFurKS6GmmGqqComaS+qmBoTI0Ncu3mXuGvWnrJ+ZSxweDgnkHf8ndVTdbiT3M7cQp2Z31dRTecHAfqydp4ejhwazh6Zezfnu98E1WIQwB3crEuJ2Y45PBTAQUVR9X4At66AppoEVO1Q8sgAOKJJjw6Am6OquDmvHskZ3R87gW+vlHz98zpmiqphkkRVbQtsfPTOC30lJKFbFTgp83bWh7Zx/uX1B6w3hI3NkkZTqEpBRDBRzG2AQHcwcYwEkOGkTERREbLQ/8HxJwuW7zdYrzfZ2iopy4qqEspKaDYravVm33k1R91Q69FA1VBRzFIVvXbx5AgXT44A8MWP81yfu0utIR2aVK3vfCnGrcUNxp8a7gKYKiLCvY2SUvo/aNtnM3e49ucK9S3p0aDdaT0UAVsKi2tVi6IWwNL9JvdqTdihaz79/l+u/rHMxmaJVMLkS2OoKKLWacdeE3IsSxctc2D5Qcl6vUlVVgNt+fkPPcFFmTw1xruvT7SCd7nuVhDQvECzJH90h0azRKoKFRkAmP5lKTWAGRdefoZL554FQNUxB92WvYeA5UN4PtSqwB2phKqsqMpBgAunRhFR3j49zuU3jnX8k6fHEQKXzh1jbmGDuYU6s4t1rt6socUeLLZHhYO2AHSHmzt19ihTZ48O8Hzl/AmunD/BjTvrvPfNX3hWsNpwJCvwYm+ngug4UilSCSq6k8YPtxDwfA+WRawIWFbgscDiULcCEaWqBFOlrLazurupOSHLqGnEKJAY8TwBEHumqUirAjNm52vEPPRV4p01XXMPAQhUBjcWm9QZwijwokgAeYHlHYA06KR1cT6ZvoV56pDUJQEjw0KeaMgj1hPEY4vz2A4eW0/e1qA7KtQdsxTYAG0H3iG4xyK1Y+xm7XmEPOJZDiENzLi2WZHngeOjj2Pe+sMg4GRYyLAsx7ME4FnsyTD9pr0PEc8zPGRAwKXBkYOPEd96cZRvf11g9MDe7e3R4Z4Q+vyEnn3P4t0XzK/W+ODN5/kPfRLewAJVEQ0AAAAASUVORK5CYII%3D" alt="" width="24" height="24" /></p>
