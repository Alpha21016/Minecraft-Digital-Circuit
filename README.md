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

所有存档如果存在打开无响应或永久加载中的情况，可以先将渲染距离调低，然后新开一个空存档，之后从空存档退出到主界面，之后再进电路存档就可以打开了。

2019-09-20更新：增加了部分基础电路模块比如或非门和与非门，完善了模块列表文档，列出了每个电路模块的坐标以便于寻找。
2019-09-22更新：增加了quiz部分，里面有4个问题，并不一定有唯一解，我给的参考答案在每个问题旁边的小木屋内。

![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Alpha21016/view02.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Alpha21016/view03.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/view01.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/view02.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/adder.jpg)
![Image text](https://github.com/Alpha21016/Minecraft-Digital-Circuit/blob/master/images/Basic/map.png)
