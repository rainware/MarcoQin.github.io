---

layout: post
title: 关于文档在开发中的重要性
category : Python
tagline: "Supporting tagline"
tags : [develope, python, document]

---

&ensp;&ensp;入了这行刚满5个月. 从最开始写代码时讨厌写文档, 注释, 到现在每写代码必先写文档, 其中的转变也是巨大.

&ensp;&ensp;虽然现在也算是"菜鸟"级别, 但也已经认识到文档的重要性了.

&ensp;&ensp;刚入行时, 经验不足. 在第一个月的时候, 完成任意一个需求都需要火急火燎甚至加班加点才能成. 在这种情况下, 自然没有心情去写什么文档, 甚至代码注释都几乎没有.

&ensp;&ensp;当然, 这样做的代价很快就显现出来了. 在随后的时间里, 我最初入职时写的代码混乱无比, 甚至我自己都难以维护(其实还是可以维护的...咳咳..).

&ensp;&ensp;之后, 随着手头的任务难度越来越大(当然, 技术也是越来越好= =!), 仅仅靠在脑袋中存储大量的"局部变量和函数"已经无法满足业务需求了. 此时, 便将编码的重点放到初始的设计上.

&ensp;&ensp;因为在学生时代的某些关系, 我的打字速度向来十分快, (巅峰时期好像是5000字/小时..)而且我也向来觉得码子速度跟编码效率有着很大的关系.

&ensp;&ensp;为了提高效率, 花了一天时间学会了vim, 做了自己的配置, 并逐渐将Python的编写放到vim上(pycharm负责调试).

&ensp;&ensp;打字速度和vim的使用确实提高了我的编码效率, 但是, 很快我就意识到, code的速度瓶颈并不在打字速度和IDE的选择上.

&ensp;&ensp;使用vim做IDE确实能在一定程度上提高效率, 但是目前的效率瓶颈, 已经转移到最初的设计以及后续的调试debug上了, 实现的过程反而只需要较少的时间.

&ensp;&ensp;此时, 文档的作用便凸显出来了.

&ensp;&ensp;在实现新的业务前, 首先从提出需求的人的角度考虑, 粗略写出业务流程. 紧接着是数据库的设计, 各种类及公用方法的设计.

&ensp;&ensp;这些东西我更习惯使用Markdown书写, 因为格式简洁清除, 而且使用vim能加快编辑效率, 省去了很多令人烦躁的鼠标操作.

&ensp;&ensp;文档的书写需要一定的规范.

&ensp;&ensp;首先我是比较讨厌规范的, 因为公司内部同事自己定义的文档格式比较反人类, 大量的操作用在排版及鼠标操作, 非常难受.(这也是刚开始为何不喜欢写文档的原因)

&ensp;&ensp;不过因为公司整体活特别多, 时间都非常紧, 每次都将大量的feature压入一个小小的sprint, 导致几乎没人写文档, 之前定义的文档格式也几乎是废弃状态.

&ensp;&ensp;这种时候, 已经没人管我写怎样格式的文档了嘎嘎. 遂用非常舒心的方式写自己看的文档. 数据库设计, API定义, 及一些其他的东西.

&ensp;&ensp;有了文档的帮助, code 的过程便轻松了许多(尽管还是每天从早到晚干不完的活. 效率越高, 自己inprogress选项中增加的任务便越多, 挡都挡不住. 服了...)

&ensp;&ensp;总之, 写此文的目的仅仅是发一发牢骚, 顺便能引起某些路人的同感便已经ok了~

PS: 目前在努力学Objective-C, 近期应该会写相关学习进度吧. Python部分的经验和坑也会慢慢写起来, 以备不时之需.

PS: update: 删除一些牢骚

PPPPPS: 幸亏有几个很naice的朋友, 也许是坚持下去的动力吧.
