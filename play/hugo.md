+++
date = "2015-09-25T17:32:05+08:00"
title = "转战 Hugo, 博客迁移之路"
+++

都快要把自己感动,从最初的 Wordpress, 到后来自己开发的 Tellets 在到 XX, 现在又到了 Hugo.

 之所以抛弃 Wordpress 是因为它太笨重了,那些年是租的虚拟主机来挂博客,每年也还会有些投入,但是后来很少维护了,便不在想续费了.
 后面想找一个轻便的能根据文件时生成的博客系统,所幸找到了 Droplet,但发现好多东西都不能满足要求,后来把 Droplet 完全重写成了 Tellts,自己添加的最喜欢的功能是直接配置 Github 的文章引用.Tellets 也是 PHP 的,而且必须要支持文件操作,但很多 PHP 应用服务器都不提供文件操作(例如: 新浪 SEA, 当初的京东云擎),后来主机停了便没有去管了.再后来有点想用 Go 重写 Tellts, 但实在没时间,然后又过了很长一段时间.
 在工作的情况下需要了解 Docker, 顺势也就利用 Docker 基于
