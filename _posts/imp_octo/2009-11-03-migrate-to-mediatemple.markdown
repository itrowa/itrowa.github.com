---
layout: post
title: 迁移到了MediaTemple
categories:
- ! '@人-网站和blog'
- Journal
tags:
- host
published: true
comments: true
---
<p><img class="alignnone size-full wp-image-217" title="(MT)" src="http://trowa.org/wp-content/media/2009/11/black-mt-bug__42c5eac.gif" alt="(MT)" width="250" height="140" /></p>

<p>今天我很高兴地宣布我已经把自己的主机迁移到了MediaTemple。没错，就是那个超级尊贵级主机。这样就再也不怕我原来的主机贩子再动<a href="http://trowa.org/archive/232.html">流氓手脚</a>了。</p>

<p>由于种种原因，我在淘宝上那家Dreamhost代理商买的那主机让我感觉非常不理想，不仅不提供SSH方便管理，甚至连操作域名绑定的后台也没有，也无法管理自己的数据库，无法知道磁盘使用量（事实上我连我买的是多大的空间都无法得知），无法获晓流量状况。上次Blog变得一片空白的时候，去问他们客服，他们懒洋洋的，让我去重装，可我连清空数据库的权限都没有，更不能直接rm -rf然后重新上传文件，你要我去把服务器砸了不成？后来没办法，也给我重装了。这个年代，无法想象如此庞大的WordPress一个文件一个文件地用FTP传上去会浪费一个人多少的时间。</p>

<p>我先连上去把老服器的东西打包，数据库备份好，使用<span style="text-decoration: line-through;">豪华</span>奢华级的Plesk后台面板绑定好域名，同时登录我域名的控制面板重新设定A记录，建好数据库，然后远程Shell登录，用PSFTP上传好东西，把wp-config设置好，华丽地打开首页，哇！成功了。</p>

<p>再次呼吁Blogger们选购Host的时候，一定要警惕虚拟主机中的猫腻，别像我一样，买了个Dreamhost的裸机。</p>

<p><img id="myFxSearchImg" style="border: medium none; position: absolute; z-index: 2147483647; opacity: 0.6; display: none;" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAADsElEQVR4nK2VTW9VVRSGn33OPgWpYLARbKWhQlCHTogoSkjEkQwclEQcNJEwlfgD/AM6NBo1xjhx5LyJ0cYEDHGkJqhtBGKUpm3SFii3vb2956wPB/t+9raEgSs52fuus89613rftdcNH8/c9q9++oe/Vzb5P+3McyNcfm2CcPj9af9w6gwjTwzvethx3Bx3x8xwd1wNM8dMcTNUHTfFLPnX6nVmZpeIYwf3cWD/PhbrvlPkblAzVFurKS6GmmGqqComaS+qmBoTI0Ncu3mXuGvWnrJ+ZSxweDgnkHf8ndVTdbiT3M7cQp2Z31dRTecHAfqydp4ejhwazh6Zezfnu98E1WIQwB3crEuJ2Y45PBTAQUVR9X4At66AppoEVO1Q8sgAOKJJjw6Am6OquDmvHskZ3R87gW+vlHz98zpmiqphkkRVbQtsfPTOC30lJKFbFTgp83bWh7Zx/uX1B6w3hI3NkkZTqEpBRDBRzG2AQHcwcYwEkOGkTERREbLQ/8HxJwuW7zdYrzfZ2iopy4qqEspKaDYravVm33k1R91Q69FA1VBRzFIVvXbx5AgXT44A8MWP81yfu0utIR2aVK3vfCnGrcUNxp8a7gKYKiLCvY2SUvo/aNtnM3e49ucK9S3p0aDdaT0UAVsKi2tVi6IWwNL9JvdqTdihaz79/l+u/rHMxmaJVMLkS2OoKKLWacdeE3IsSxctc2D5Qcl6vUlVVgNt+fkPPcFFmTw1xruvT7SCd7nuVhDQvECzJH90h0azRKoKFRkAmP5lKTWAGRdefoZL554FQNUxB92WvYeA5UN4PtSqwB2phKqsqMpBgAunRhFR3j49zuU3jnX8k6fHEQKXzh1jbmGDuYU6s4t1rt6socUeLLZHhYO2AHSHmzt19ihTZ48O8Hzl/AmunD/BjTvrvPfNX3hWsNpwJCvwYm+ngug4UilSCSq6k8YPtxDwfA+WRawIWFbgscDiULcCEaWqBFOlrLazurupOSHLqGnEKJAY8TwBEHumqUirAjNm52vEPPRV4p01XXMPAQhUBjcWm9QZwijwokgAeYHlHYA06KR1cT6ZvoV56pDUJQEjw0KeaMgj1hPEY4vz2A4eW0/e1qA7KtQdsxTYAG0H3iG4xyK1Y+xm7XmEPOJZDiENzLi2WZHngeOjj2Pe+sMg4GRYyLAsx7ME4FnsyTD9pr0PEc8zPGRAwKXBkYOPEd96cZRvf11g9MDe7e3R4Z4Q+vyEnn3P4t0XzK/W+ODN5/kPfRLewAJVEQ0AAAAASUVORK5CYII%3D" alt="" width="24" height="24" /></p>
