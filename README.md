# Minecraft-Digital-Circuit

本项目利用Minecraft游戏中的简单信号元件构建出复杂的组合和时序数字“电路”，通过一种直观的三维可视化方式展示一个较为纯粹的可计算模型。这个模型不需要考虑现实中的晶体管电路所涉及到的电气特性和器件工艺等问题，是一个虚拟的图灵完备的逻辑结构。

在saves目录下包含三个存档

用于教学的存档Digital-Circuit-Basic，里面搭建了常用的从简单到复杂的数字电路结构，该存档适用于Minecraft-1.12版本及以上，我自己用的是1.12.2。
这个存档的元件和模块列表说明在“docs/教学存档单元和模块列表.xlsx”。

我以前的大型作品Alpha21016分为两个存档，一个是最终版演示存档，一个是加减乘除计算器演示存档。
之所以分开是因为最终版的存档里为了让CPU的电路简化，四则运算计算器已经被我废弃了，所以我把很久以前刚建完四则运算计算器时的存档单独列出来。
最终版里包含CPU，特殊函数计算器，显示屏，时钟等电路结构。
这两个存档必须在1.4.7版本打开才能顺利运行，因为这个游戏版本过于古老，如果网上寻找不到可以到知乎上私信我。
如果是自行在别处下载的1.4.7游戏程序，需要额外安装能够加载更多区块的插件，因为游戏中超出视野之外的电路是不会运行的。
尽量保证加载范围/渲染距离能覆盖至少320x320的范围，这需要较强的CPU性能，单核性能较强的双核及以上酷睿处理器最为合适。
这个作品并没有全部完成，在游戏中建造十万门以上的大规模数字电路，后期的维护和调试成本过高，因为时间和精力的原因没有将全部的指令集完成，不过CPU已经具有完整的流水线结构。由于年代久远，当时的很多文档资料已经遗失，所以这个项目的电路阅读起来会很困难，而且运行可能存在一些bug。我重新写了CPU部分的演示和结构文档，配有图片将CPU的各个结构描述了一下。

建议直接看教学存档即可了解Minecraft数字电路比较核心的部分。教学存档里都是单独制作的经过反复调试校验的电路模块，可以视作一套标准单元库，输入输出标识以及功能描述都较为清晰。
另外我使用了一个很有用的第三方工具软件，叫MCEdit，可以方便快捷地编辑游戏存档中的三维结构，使得电路搭建比纯手搭节约了很多时间，下载这个工具可以去MCEdit Unified官网。
关于介绍的文档目前没有写完，日后会继续完善。

注意！！！
所有存档如果存在打开无响应或永久加载中的情况，先重启游戏，将渲染距离调低，然后新开一个空存档，进入空存档后再退出到主界面，之后再加载电路存档就可以正常进入了。但是CPU的存档进入后还需要把渲染距离调整回较大的数值，否则电路无法正常运行，在退出存档前再把渲染距离调小就能保证下次能顺利进入存档。这是游戏程序机制的缺陷，暂时没有更方便的解决办法。

更新记录：

2020-08-03更新：教学存档中增加键盘和显示器模块，详见“教学存档单元和模块列表.xlsx”。

2019-09-28更新：增加文档“异或门和全加器最简结构设计原理”，有详细的基础电路设计思路。教学存档中增加了粘性活塞版的与门。

2019-09-23更新：教学存档中增加部分精简版的基础电路模块，quiz中增加第6个问题，内容是关于建造全加器。

2019-09-22更新：教学存档中增加了quiz模块，里面暂时有5个问题，以后还会增加。我给的参考答案在每个问题旁边的小木屋内，每道题并不一定只有唯一解。

2019-09-20更新：教学存档中增加了部分基础电路模块比如或非门，与非门，RS或非触发器等。完善了模块列表文档，列出了每个电路模块的坐标以便于寻找。

【重要声明】本作品不支持任何公众号和自媒体为了吸引流量而进行夸大事实的改编和转载，不希望被反复炒冷饭。目前我只授权了知乎用户Deftercanda和公众号量子位进行了转载，其他所有改编者和转载者均没有被我本人允许。本作品并没有个别自媒体宣传的那样夸张，只是一个基础的数字电路和计算机组成原理的应用。本作品全部开源，非盈利，所有内容以我本人的文章和存档为准。

![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Alpha21016/view02.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Alpha21016/view03.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/view01.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/view02.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/adder.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/screen-night.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/screen-back.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/map.png)
