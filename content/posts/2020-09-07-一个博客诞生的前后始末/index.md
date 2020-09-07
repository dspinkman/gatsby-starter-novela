---
title: 一个博客诞生的前后始末
author: dspinkman
date: '2020-09-08'
excerpt: >-
  欣赏，感谢，敬佩，这年岁“复古”的分享精神难能可贵。这也是为什么，才疏学浅一届庸人的我，还想不自量力开博客的原因之一。 
  即便知道自己无法输出什么价值和思想，依然愿意践行。
hero: images/A ghost Blog was born_ dspinkman.jpg
---
*2020年5月27午时，盯着ghost后台，决定停止纠结，开始写字。*

##Hello World

Hello World! 是不是应该先礼貌的进行自我简（shen）介（shi）。

**博主其人文科生 ，对代码可以算一无所知。** 甚至不敢称呼自己为“小白”，因为一直心存敬畏的认为那些在别人技术博客下请教的同学虽然总自称“小白”，但起码还是懂一点的。2020年之前正经跟代码产生的交集，仔细想想只有在网上跟着教程不亦乐乎的搞机，从supersu搞到magisk，有时F12看看广告主的官网上用了哪家的流量统计。哦！以及10年前大二的必修课VB。

2020年持续至今的疫情，打乱了人们日常奔走疲于奔命糊口的机械式运转节奏。在这段混乱而灰暗的时间里，一个年纪已然不小的大龄单身青年，除了日常例行为自己的生活和未来感到焦虑之外，也只有折腾点什么让自己专心，给自己找点新鲜的乐趣，或许比沉迷于每个赛季打上王者来的有意义一点。 想来自己也一直是3分钟热度的类型，做事情全凭一下子涌动到顶的激情，褪去之后就翻篇，这大概也是一事无成的终极原因。



##blog由来     

2019年的冬季，因为不可言说的需求接触了[vultr](https://www.vultr.com/)。

2020春节，想用[github某项目](https://github.com/testerSunshine/12306)抢回家的火车票，因为搞不懂headless chrome，彼时又无法在centos8上成功安装图形化界面，而放弃（求不要无情嘲笑，是真的不懂，学习也要过程）。搞笑的是后来想想这个东西在国内IP和windows环境下跑，简单又方便。总之有那么一个阶段，是为了折腾而折腾。

2020年3月，放弃vultr，想着怎么用免费薅的GCP 300美金，发现GCP的低配是真心低配，好像装个centos系统都费劲。GAE看不懂，想玩点什么发现网上傻瓜式教程也不多，最后落了个不可言说之外什么也没干的下场。同期又薅了Aliyun的新手套餐。

2020年4月，搭了[ttrss](https://ttrss.henry.wang/)+[rsshub](https://docs.rsshub.app/)，网上扒教程的时候看到[flowerss-bot](https://github.com/indes/flowerss-bot)，又觉得觉得好好玩。于是作为副产品，用ttrss烧的源+telegraph搞成telegram的bot推送，还能即时预览，真的有意思。不过，这都是得益于那些编写到位又感人的教程。之后毫不意外的经历了信息过载和[FOMO](https://en.wikipedia.org/wiki/Fear_of_missing_out)，至今未能做到日清。

<img class="lazyload" src="https://cdn.jsdelivr.net/gh/dspinkman/pics@latest/2020/06/ttrss_feed.jpg" alt="ttrss_main" />
<center style="font-size:14px;color:#C0C0C0"> 最佳搭档：ttrss自建rss订阅服务，rsshub为未提供订阅源的网站生成自定义rss订阅源 </center>

<br>

然后，就是博客。一选本来是typecho，因为江湖传说体积小轻量又简洁，然而翻别人的blog翻到头烂都没能搞懂怎么弄php的config；心灰之际，无意间看到1个无比贴心的[wordpress docker镜像](https://github.com/mjstealey/wordpress-nginx-docker#ssl-certs)，配有无比周到的readme，真的感人。

WP主题和插件各种瞎玩了几天之后，突然觉得不是很喜欢，确实强大，但也确实为了简单好用而不得不臃肿；中间有一次把本地备份上传服务器之后docker compose重构，莫名其妙遭遇权限问题导致插件无法工作/升级，一顿搜索完了也没找到正解，总之觉得使用体验并不好，接着就换了ghost。

ghost第一印象就是后台简约又好看，瞬间被颜值拉了好感。也有一些不足在慢慢熟悉后发觉，比如主题匮乏，free的就那么几个，好在官方的free theme质量很好；另外，很多在WP通过插件可以解决的问题，到了ghost这里只能自己敲代码。一度觉得自己搞不定，想换回WP，但非常舍不得这个舒适的后台UI，于是决定就这样吧，未来想要搞的更fancy的时候，再慢慢啃吧。

<img class="lazyload" src="https://cdn.jsdelivr.net/gh/dspinkman/pics@latest/2020/06/ghost blog_admin.jpg" alt="ghost_admin" />
<center style="font-size:14px;color:#C0C0C0"> ghost后台的简约风格 </center>

##一点感想

一届文科生现在知道了linux有很多版本，知道了怎么SSH到自己的主机，知道了买域名、dns与cloudflare，知道了https与nginx，知道了docker是个好东西等等等等；总之一些折腾相关的皮毛杂耍。

在没有成体系的学习相关基础之前，依然什么都不懂，也不会；文科生的本质和内核没有改变，这也不能一蹴而就。

不知道热情会持续多久，年纪也大了，信不过自己有精力和能力展开系统的编程学习；好多想要学习的东西，一时也不知道从何起手。

近期清理了一大堆rss订阅源，先立个6月之内订阅日清的小小目标；另外，试着用MD写下这第一篇。

回想这几个月，跟着各种网络教程反复折腾，由衷感叹，很多handy又详实的资料和教程，来自各路神仙的Blog。

**欣赏，感谢，敬佩，这年岁“复古”的分享精神难能可贵。这也是为什么，才疏学浅一届庸人的我，还想不自量力开博客的原因之一。**

**即便知道自己无法输出什么价值和思想，依然愿意践行。**

折腾的过程是乐趣，折腾完了说到底都是工具，总要适时的喊自己停下来享用。

有时候觉得自己还23，拿着到手的nexus 4傻乐。
