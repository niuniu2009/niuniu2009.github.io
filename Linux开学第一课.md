# Linux 开学第一课    



[TOC]



## （1）从贝尔说起：



![image.png](https://upload-images.jianshu.io/upload_images/15665369-daa0a1e0891e9834.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

(1) [AT&T：巨头的百年折腾](https://baijiahao.baidu.com/s?id=1610201096702812748&wfr=spider&for=pc)

(2) [AT&T、朗讯、贝尔实验室的前世今生及兴衰](
https://www.sohu.com/a/117218622_458015)

(3) [贝尔实验室的百年兴衰史 ](https://www.sohu.com/a/229877467_308613)

![img](http://5b0988e595225.cdn.sohucs.com/images/20180429/07daf4d2feb84caaac4d2ce8b38646da.png)



- 11位科学家获得诺贝尔奖；

- 16位获美国最高科学、技术奖——美国国家科学奖章和美国国家技术奖章，均由总统亲自颁奖；

- 4位获得了图灵奖（堪称“计算机界的诺贝尔奖”）；

- 还有更多科学家拿了其它国家的高等奖章，就连实验室成为史上第一个机构获奖者（美国国家技术奖）。

  ![img](http://5b0988e595225.cdn.sohucs.com/images/20180429/2cc5a6f083394a5696256e4e4a8cad57.jpeg)

## （2）MULTICS项目

![æ¸æèç¥­ç¥ åæ°PCåå±å²ä¸çç¥åä"¬ ](http://img5.pcpop.com/ArticleImages/0x0/2/2335/002335350.jpg)

```美国电话及电报公司（AT&amp;T）、通用电器公司（G。E。）及麻省理工学院（MIT）计划合作.
回顾Unix历史，我们就要说一下一个叫MULTICS的项目。上世纪六十年代时，大部份计算机都是采用批处理的方式（也就是说，当作业积累一定数量的时候，计算机才会进行处理）。那时，我们熟知的美国电话及电报公司（AT&amp;T）、通用电器公司（G。E。）及麻省理工学院（MIT）计划合作开发一个多用途、分时及多用户的操作系统，也就是这个MULTICS，其被设计运行在GE-645大型主机上。不过，这个项目由于太过复杂，整个目标过于庞大，糅合了太多的特性，进展太慢，几年下来都没有任何成果，而且性能都很低。于是到了1969年2月，贝尔实验室决定退出这个项目。
熟悉这段历史的人都知道，贝尔实验室中的有个叫Ken Thompson的人，他为MULTICS这个操作系统写游戏了个叫“Space Travel”的游戏，在MULTICS上经过实际运行后，他发现游戏速度很慢而且耗费昂贵 —— 每次运行会花费75美元。退出这个项目以后。他为了让这个游戏能玩，所以他找来Dennis Ritchie为这个游戏开发一个极其简单的操作系统。这就是后来的Unix。（值得一提的是，当时他们本想在DEC-10上写，后来没有申请到，只好在实验室的墙角边找了一台被人遗弃的Digital PDP-7的迷你计算机进行他们的计划，这台计算机上连个操作系统都没有，于是他们用汇编语言仅一个月的时间就开发了一个操作系统的原型）他们的同事Brian Kernighan非常不喜欢这个系统，嘲笑Ken Thompson说：“你写的系统好真差劲，干脆叫Unics算了。”Unics的名字就是相对于MULTICS的一种戏称，后业改成了Unix。
```
## （3）Ken Thompson Unix之父:

![image.png](https://upload-images.jianshu.io/upload_images/15665369-cabe98bd2f8cbfa7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



[26 岁发明 Unix，70 岁还在做编程的技术巨匠](https://www.jianshu.com/p/5388e529ffb8?utm_source=oschina-app)

## （4）C 语言之父 Dennis Ritchie

![Dennis Ritchieimage.png](https://upload-images.jianshu.io/upload_images/15665369-77fc2cbb7180c36f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

https://www.jianshu.com/p/9a55c573b9c8

=======================================================================================

> **Unix就在这样被游戏和玩笑创造了，当时是1969年8月。**
>
> **也就是这一年，Linux之父Linus Torvalds在芬兰出生了。**

=======================================================================================

```1946年：世界上第一台电脑ENIAC在美国宾夕法尼亚大学诞生，目的是用来计算炮弹弹道，重达30吨。

1947年：BELL实验室发明晶体管。

1958年：TI发明集成电路。

1969年之前，BELL实验室、MIT、GE联合开发Multics。
1969年：BELL的Ken Thompson为自己开发了Unics（这个是戏称的非正式的名称，因为思想源自Multics）。

1971年：Intel发布第一微处理器4004。
1973年：UNIX正式诞生，BELL实验室的Dennis开发出C语言，并用C语言重写了Unics，正式取名UNIX。

1977年：UNIX分支--BSD诞生，加州伯克利大学Bill Joy取得了UNIX的源代码，加以修改和完善，成为UNIX重要分支BSD-UNIX。之后的x86上的FreeBSD就是BSD改版而来。

1979年：AT&T宣布收回UNIX版权，不再开放，同时发布System V架构的UNIX。期间众多公司的UNIX系统纷纷出现。
1979年：Intel推出8086/8088 CPU。

1981年：IBM发布IBM PC，x86架构的PC机开始流行。
1984年：x86架构的Minix操作系统诞生。
1984年：Stallman启动GNU项目，目的是开放一个自由、开源的UNIX（Free UNIX）。由于工程浩大，Stallman决定先编写应用程序，如GCC，Emacs等出现。
1988年：XFree86诞生，即x86版UNIX上的GUI系统。

1991年：Linux诞生，Linus Torvalds发布的运行在386机器上的内核程序。

2008年：Google发布基于Linux的手机操作系统Android。
```
## （5）操作系统的历史

* [一张图说清楚操作系统历史](https://upload.wikimedia.org/wikipedia/commons/7/77/Unix_history-simple.svg)

### [操作系统Unix、Windows、Mac OS、Linux的故事](https://www.jianshu.com/p/4a06bbe8ebe4)

```我们来沏杯茶，回顾Unix的传奇，讨论讨论Windows与Mac OS的恩恩怨怨，还有Linux的迅速崛起。```

#### 5.1 Unix 传奇

```Dennis Ritchie 和 Ken Thompson，尽管是游戏和嘲讽，Unix和C诞生了，并且完美地结合成为一个统一体，C与Unix很快成为世界的主导。新的历史，开始了。```

#### 5.2 Ken Thompson到伯克利（Berkeley）

`工程师研发完毕，往往会有休假，一休就是一年。旅游，探险都是好方式，可是 Ken选择了到伯克利（Berkeley）进行教学。`

`由于当时AT&T被美国反垄断制裁，Bell实验室不能销售Unix。只能无偿提供大家学习研究。正是因为这样开放环境，使得Unxi的功能和特性被不断的丰富。在Berkeley，有一个专门研究UNIX小组，他们为UNIX提供了很多新特性，例如著名的 TCP/IP协议。并完成了BSD版本。很快，就有公司看到了BSD的商机，分分购买BSD进行商用。`

![img](https://gss2.bdstatic.com/9fo3dSag_xI4khGkpoWK1HF6hhy/baike/crop%3D0%2C45%2C1024%2C677%3Bc0%3Dbaike116%2C5%2C5%2C116%2C38/sign=a460c74bf51f4134f4785f3e182fb9fe/adaf2edda3cc7cd98f6e6e713101213fb90e91d2.jpg)



#### 5.3 AT&T公司和BSD的战争 利益之战

`AT&T公司对其他机构拿着Unix赚钱自己却一无所获很不爽。那是一个AT&T妄图私有化的Unix的时代。`

`Berkeley BSD小组的Bill Joy开始创办了一家公司，也就是后来全球知名的SUN公司。就销售量来说，AT&T/UNIX始终赶不上BSD/Sun。并且Sun生产的小型工作站，风靡整个市场，很快就将 DEC 击败，并且让DEC退出了历史舞台。`

#### 5.4 UNIX的商机

`BSD 仍然还在官司缠身，可是其他公司都看到了UNIX的商机，分分投靠 AT&T 并开发自己的Unix，其中有著名的IBM的AIX，HP的HP-UX，SUN公司的Solaris，还有西雅图一个不知名的小公司，也生产着一个叫XENIX的Unix。`

#### 5.5 Windows与Mac OS的恩恩怨怨

**IBM提携了一个小兄弟intel**

```1975年，IBM推出了早起的PC兼容机。我们知道，操作系统与CPU是有直接关系，不同的cpu运行的操作系统是不一样的。当时Unix价格昂贵，IBM一台PC兼容机造价2w美元，操作系统都要花4w。这样还是无法民用，因此IBM选择了一家小公司Inter生产的X86系列的cpu。Inter是小公司？没错，当时确实是这样，小到不起眼。而主流生产cpu的却是摩托罗拉，摩托罗拉生产的M6800比Inter的技术和设计上都要先进很多，更重要的是这个可以运行Unix。IBM放弃了兼容机上的Unix，因而不得不自己写出了一个兼容X86的操作系统---PL/M。当然这个东东造价也不菲。```

**bill gates 花了5万美元购买了DOS**

```微软联合创始人Allen同学Tim Paterson原本是打算写个东西用来测试的16位Intel 8086 CPU界面，于是花四个星期写了一个操作系统。当Bill Gates得知之后，马上花5W美元买下了这个系统，Tim Paterson欣喜若狂，四个星期就赚了一大笔，简直像做梦，赶紧和Bill签订合同，Bill得到之后并命名为DOS。随后，Bill通过其IBM董事会成员的妈妈，得以和IBM高层谈判。IBM兼容机的操作系统价格昂贵，不适合卖个普通用户，IBM定义的主要对手是如火如荼的Apple，IBM想要压制apple就需要廉价的计算机。微软可以提供廉价的DOS，当然不是卖操作系统，而是卖操作系统的许可。每台IBM兼容机都捆绑一个DOS。Bill的招数就是捆绑，从dos到IE都是如出一辙，当然特别奏效。IBM也没想多少，他们认为硬件才是赚钱的根本，DOS也便宜。两者结合，果然市场颇受欢迎，Bill也赚到了千万刀。```

**IBMPC兼容机捆绑DOS，都发了大财**

```IBM兼容机逐渐推向市场，与Apple一较高下。此前，在一个车库，两个年轻的极客，一个对机器怀有无比的热情，另外一个则对改变世界十分狂热，两个人黏在一起，创立了一家伟大的公司Apple。与IBM兼容机不一样，Apple的早期微机，采用是摩托罗拉的cpu和unix。Jobs独特的艺术气质与Wozniak的技术天才，让Apple的微机在市场上极受欢迎。```

**apple微机，采用摩托罗拉的cpu和unix, 就是一个字，贵。**

```Jobs对技术和艺术的卓越追求，让他不断的改进Apple的电脑。1973年施乐（Xerox）的PARC研究所开发出GUI接口与鼠标（题外话，历史上有两个著名的雷锋实验室，前面提到的Bell 和 这个 Parc）。但是Xerox本身是生产打印机的，董事会莫名其妙的觉得GUI一旦出现，顾客就不乐意使用打印机，因此对Park实验室的成果冷淡的打入冷宫。```

**施乐公司的GUI和鼠标，被苹果和微软拿走了赚钱了。**

```1979年乔布斯到PARC研究所看到Xerox原型机Alto。敏锐的Jobs立刻发现了GUI和鼠标的商业价值，很快他就说服Xerox公司，以一个极低的价格买下了GUI进行研究。1983年苹果公司推出了Apple Lisa，首次采用GUI的商品化计算机。Lisa一诞生，就震撼了整个微机市场，那个车库里的年轻人因此身价过亿。```

**谁是小偷？**

`Bill找到了Jobs，大加赞赏了Jobs的伟大，然后卑微的祈求一份Apple的GUI，并承诺Microsoft的一切成果都是Apple的。不可一世的Jobs答应了，Bill得到了Lisa原型机，马上组织团队研发，并在1990年5月份推出Windows3.0并一炮而红。商业上取得惊人的成功。打破了任何软件产品的六周内销售记录，从而开始了微软在操作系统上的垄断地位。`

`此时Jobs发现了Bill这个小偷，勃然大怒，可是为时已晚。对此，Bill并不否认，反而很得意讥讽乔布斯说：“我们有一个富邻居——Xerox，他家有一台电视。当我们想偷的时候，发现乔布斯早就偷走了，可他却说我们是小偷。”他们两人，都验证毕加索那句著名的格言：“好的艺术家抄袭，伟大的艺术家偷窃。”`

**苹果赶走了乔布斯，Unix官司缠身，错过了操作系统发展的黄金时期，但是成就了微软。**

`但是Jobs心有不甘，因此着手研发Macintosh，由于Macintosh造价昂贵。在市场上逐步落后与Microsoft的Windows。Windows持续发展着，对于Jobs，Apple正在酝酿着一个地震，1985 Jobs被赶出了Apple。`
`此时，Unix在干嘛呢?？Unix正忙着和BSD打官司，也正是这些时间，错过了操作系统发展的黄金时间，当Microsoft和Apple逐渐由小人物变成巨人的时候，Unix已经脱离了商业的主流。`

`Windows风靡市场，一时洛阳纸贵。可是早期的windows并不稳定，蓝屏是家常便饭。Bill并没有偷到Jobs的核心技术，只获得了GUI。`

`Microsoft死活硬凑的将windows和VMX结合，诞生了Windows NT。NT诞生不久又出现了Server版本，Server的诞生，敲响了另一家公司的丧钟。当时网络已经出现，Novell生产网络操作系统占据网络统治地位，可是NT的出现，Novell的生命也走到了尽头。`

**乔布斯的回归**

`被赶出Apple的Jobs同样没有停止他的步伐，Jobs离开Apple之后创办了如今三维动画巅峰旗帜的Pixar公司.并且Apple在对Microsoft的竞争中逐步走向衰败，Apple董事会不得不重新召回Jobs挽救Apple日益颓废的江山。Jobs果然是帮主，他的回归，Apple散发了第二春，几款革命性的产品iPod，iPhone将Apple再一次走到了世界的巅峰。MacOS成为了人们热衷的操作系统，这个曾经败给Windows的操作系统又回来了，并且在移动断，IOS也成为了霸主，后来Google 的Android加入争斗，那是后话了。`

**google的强大Android**

`Microsoft的 windows xp成为微软史上成功的操作系统。可是Jobs回归之后的Apple，XP丑陋的界面很难和炫目的MacOS较量。Microsoft早期和IBM共同研发OS/2，由于后来和VMX的结合而退出了OS/2。IBM又一次验证了谁跟微软合作谁被坑的规律。可是针对MacOS，Microsoft一直对和VMX的结合产品心有余悸。最终用低价从IBM手下买回了OS/2，并重新拼凑了一个“绚丽”的操作系统Windows Vista。`
 `显然，OS/2被IBM定义为史上最失败的产品，具有讽刺的是，Vista也不约而同的被Microsoft定义为失败的产品。Microsoft不得不在短时间内重新开发。推出了Xp的取代者--Windows7。先如今，Microsoft在互联网遭遇Google强大的统治, 移动方面windows phone也生存在Apple IOS的阴影之下。`

`曾经强大到像日不落帝国的Microsoft，也在谋求着新的蜕变。当然，Microsoft依然统治着桌面操作系统，在服务器端，另外一个崛起的不是Unix，不是MacOS，也不是Wndows的操作系统，他已然加冕成为新的王者。那就是Linux的故事，这个故事也很有趣，伴随自由的运动，黑客的分享的精神。比起之前少了很多商业的争斗气息，更多是那些黑客传奇的故事。我们得重新打开历史书，回到1991那年的夏天，阳光明媚的芬兰赫尔辛基大学的校园里...`

### 故事还远没有结束

`下面该轮到linus Torvalds表演了。`



> 一张图看尽    [操作系统历史](https://upload.wikimedia.org/wikipedia/commons/7/77/Unix_history-simple.svg)

![操作系统SVG图片](D:\temp\temptypora\Unix_history-simple.svg)



## （6）Andrew_S._Tanenbaum 大牛

世界上最流行的操作系统不是 Linux 或 Windows，而是 MINIX

https://linux.cn/article-9040-1.html

你所不知道的，世界上最流行的操作系统MINIX。

![image.png](https://upload-images.jianshu.io/upload_images/15665369-e3f1f2ca7bbbdd9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

https://en.wikipedia.org/wiki/Andrew_S._Tanenbaum

* [Minix](https://en.wikipedia.org/wiki/MINIX)

* [Minix & Intel](https://taihe.github.io/2017/11/09/minix/)
```Minix，这是荷兰阿姆斯特丹自由大学计算机科学系Andrew S. Tanenbaum教授为了教学而开发出来的一个Mini版本的Unix系统，1987年发布第一个版本。那个年代，软件的世界不像今天，随便可以在网上下载一个Linux或者BSD的内核系统来研究。当时因为AT&T公司对于Unix源代码政策的变化，Andrew S. Tanenbaum教授出于教学的目的，自己开发了这套Minix系统。
 这套系统启发了Linus Torvalds，他在研究了Minix源代码之后，认为这套Minix系统并不具有实用性，转而自行开发了Linux的内核。与Minix的微内核不同的是，Linux采用的宏内核架构设计，这也导致操作系统核心设计的一场著名的论战。
 在Linux系统大行当道的今天，谁也不曾想到，Minix隐藏在互联网世界的最深处。
```
 [![Intel](http://upload-images.jianshu.io/upload_images/15665369-8bed2cab08a83931.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)](http://wx4.sinaimg.cn/large/6f625b04gy1flctizm6k4j20v10qt0wx.jpg) 

Intel CPU Chipset Block Diagram
```
 我们随便找了一张第七代的Intel CPU的模块图。Intel的Minix系统运行ME模块中，也就是图中的Intel ME 11.6 Fireware and BIOS Support模块中。当然这种图片是Intel新品出来的时候用于宣传的图，实际上运行一个私有的Minix的系统的芯片是在图中的Intel Z270 Chipset里面，而不是外面。一个有着Rang-3（应用程序的权限级别是3，操作系统的权限级别是0，这个私有Minix系统的权限级别是-3）权限级别的系统，可以获取到打Chipset经过的任何数据。
 由于Minix系统是2000年开始以BSD协议开源了，Intel将这个系统修改之后集成在ME中，除了Intel总部的核心人员，任何人不知道Intel做了何种修改，是否留有后门，没有人可以审核到这个系统。
 这么多年，Intel没有一个实际的具有威胁的竞争对手，在对CPU的升级上一直采用挤牙膏的方式，而在深层次，可能植入一个隐藏式的控制整个互联网的后门。
```

* [全球最流行操作系统MINIX开发者Anderw S.Tanenbaum：很开心 Intel不用给我钱](http://news.mydrivers.com/1/555/555353.htm)



## （7）大牛的学生 Linux Torvalds 改变整个世界的人

* [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds)



![img](https://gss3.bdstatic.com/7Po3dSag_xI4khGkpoWK1HF6hhy/baike/w%3D268%3Bg%3D0/sign=c87aa59942a7d933bfa8e3759570b62e/5882b2b7d0a20cf4f664615276094b36adaf9943.jpg)

### 他的名字是Linus，他是所有程序员们的上帝。

**1969年，随着Unix一起诞生。**

> 1991那年，对于芬兰人绝对是一个有意思的一年。世界上首次全球通对话在诺基亚的Radiolinja网络中完成，诺基亚征服世界的脚步已经无法遏制。
>
> 与此同时，阳光明媚的芬兰赫尔辛基大学的校园里，一个少年正好拥有了一台完全属于自己的电脑，不必再忍受学校机房漫长的等待。他当时对安德鲁·塔南鲍姆（Andrew Tanenbaum）的著作《操作系统：设计与实现》——一本Minix操作指南深深着迷。
>
> 由于AT&T对于Unix商业化，而后将Unix进行了闭源。Andrew所教授的课程《操作系统》却没有了“操作系统”。对此Andrew一咬牙，狠狠心，写出了一个兼容Unix的操作系统。人家就是厉害，你不给我使用，我自己写一个出来用。尽管Andrew的成果很简单，但是还是具备了Unix的基本功能，当然比较mini，因此命名为Minix。Minix作为Unix的变种，彼时的Minix正凭借低廉的价格和简易的操作在大学大行其道。
>  Minix由于过于短小精悍，只能运行这一种机器，其他机器没有驱动。Andrew的学生就写了好多好用驱动来扩展Minix。可是，教授Andrew却觉得自己的操作系统要保持纯洁，不能有其他的代码来源。于是学生们就很郁闷，其中就有个叫Linus的同学。
>
> 拥有自己的PC的Linus却不能将Minix运行在自己的电脑上。Linus也不得不走上了他无数前辈的道路，不让用，不给用，那就自己写一个操作系统来用。仅仅两个月后，一个“千疮百孔但却碰巧可以使用”的磁盘驱动程序和一个小到不能再小的文件系统就诞生了，这就是第0.01版的Linux。随后Linus将操作系统上传至FTP，并公布了全部源代码。在USENET讨论区，Linus阐述其初衷：在新操作系统中，“人们可以自己编写驱动程序，可以随意修改操作系统以适应不同需求，可以尝试在Minix上运行所有程序，这是Minix从未有过的美好一天。”

## （8）了不起的黑客    理查德·斯托曼（Richard Stallman）

![img](https://gss0.bdstatic.com/-4o3dSag_xI4khGkpoWK1HF6hhy/baike/w%3D268%3Bg%3D0/sign=65bd7d44d72a60595210e61c100f53a6/1ad5ad6eddc451dab5799d66b6fd5266d11632ab.jpg)

美好的日子渐渐来临，Unix生态还是老样子，在商业的争斗中裹足不前。Microsoft和Apple的争斗也逐渐明朗，Microsoft靠卖软件大发特发。这让一个黑客很不满。

```理查德·斯托曼（Richard Stallman）登场，他认为所有软件都是人类智慧和思想的结晶。软件应该自由的让人们使用。1983年，Stallman发起了“GNU（GNU’s Not Unix的递归缩写）”计划，目的是创建一套完全自由的操作系统，以“重现软件界合作互助的团结精神”。他以“著佐权”（copyleft）标准为范本拟定了一份通用公用版权协议(General Public License，GPL)。与强调个人版权但限制自由传播的著作权（copyright）不同，GPL更强调公共版权和鼓励自由传播，它允许修改程序、复制软件和销售获利。但前提是公布修改后的全部源代码，必须保证自由思想的传递。GNU计划激发了软件界极大的热情，世界各地的软件奇才们纷纷参与其中。并且开发出包括文字编辑器Emacs、C语言编译器，gcc以及大部分UNIX系统程序库和工具在内的绝大多数软件，很多免费软件的水平甚至都已经超过了相应的付费版本。```

## （9）天作之合 GNU/Linux

`可是问题又来了，GNU编写了很多自由免费的软件，可是这些免费软件却运行在不自由的Unix上，这真是一个巨大的讽刺。Stallman承诺大家要两年内重新写一个操作系统，可是五年过去了，依然看不清成功的那一天。与前面很多故事一样，事情总是环环相扣，可是谁也不知道这环将会扣向哪一环。Stallman苦于没有操作系统，芬兰的那边，Linus只有一个操作系统内核而没有应用软件。`

`于是，他们在各自的领域奋斗多年之后，命运终于安排他们走到了一起，Linus率领Linux加盟Stallman的GNU计划，上帝说要有光，于是牛顿出生了；人类需要自由，于是Linux与GUN结婚。`

`这一“联姻”堪称是软件界的天作之合。`

`1992年，在Linux Kernel平台上工作的开发者只有100位，平台中的核心代码只有几万行。如今，在平台上工作的开发者已经多达1000人，人员的背景也从最初的黑客扩散至更多的行业，平台中的核心代码则已经超过千万行。`



* [linux](https://en.wikipedia.org/wiki/Linux)

   ![Tux the penguin](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png)

> 霸气的Linus says：
>
> Nobody actually creates perfect code the first time around,except me.But there’s only one of me.

参考：

[历史上最伟大的12位程序员](https://www.jianshu.com/p/64c445d70a88)

## （10）什么是linux？

### [Linux内核官网](https://www.kernel.org/)

[Linus Torvalds 的github]( https://github.com/topics/linux)

### Linux内核版本？

![img](http://blog.chinaunix.net/attachment/201404/14/26000296_1397447945NyFj.jpg)

### Linux的发行版本？

#### 常见发行版：

#### ubuntu 

http://wiki.ubuntu.org.cn

#### openSUSE

https://baike.baidu.com/item/Debian/748667?fr=aladdin

#### 深度linux

https://www.deepin.org/

#### 红旗linux

http://www.redflag-linux.com/

#### Red Hat Linux

最高版本为9.0
Red Hat Linux企业版
简称RHEL
目前较新版本为 8.x 系列
http://www.redhat.com 
Fedora Core社区版
https://getfedora.org/   Fedora29 

#### centos7

![Centos-logo-light.svg](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Centos-logo-light.svg/200px-Centos-logo-light.svg.png)

centos 维基百科 https://en.wikipedia.org/wiki/CentOS



## （11）为什么Linux是撼动不了的？为什么你不能自己做一个操作系统？

看这篇文章就懂了。

[Linux 战略或生态圈是什么？](https://www.jianshu.com/p/151a44280c1c)

## （12）Linux的优点



![1550909642422](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550909642422.png)



## （13）Linux的应用领域

#### 1、[Android的前世今生](https://blog.csdn.net/cqkxzsxy/article/details/74911329)

![img](http://si1.go2yd.com/get-image/0EteMrr2vjM)

#### 2、超级计算机

[超级计算机500强六月份榜单：全是Linux，一直都会是](http://baijiahao.baidu.com/s?id=1604420281071834685&wfr=spider&for=pc)

2018最新榜单  https://www.top500.org/list/2018/06/

Linux “完全统治” 了超级计算机

https://linux.cn/article-9065-1.html

#### 3、**电影特技模拟**

![1550907955746](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550907955746.png)

![1550908010312](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550908010312.png)

#### 4、Linux在企业和政府中的应用

`这是大部分大型互联公司都在使用Linux提供Web服务`
`Google用十万台Linux计算机提供搜索服务`
`QQ也靠Linux的服务器`
`NEC、摩托罗拉、诺基亚和三星都有Linux手机`
`全球最大网上书店亚马逊使用的是Linux平台`
`德国慕尼黑市政府的14000台计算的操作系统是Linux`
`美国的天气预报现在靠Linux系统`

#### 5、Linux在嵌入式领域的应用

`嵌入式linux系统的应用可以说现在到处都有，嵌入式linux系统是数字化产品的核心,制造工业、过程控制、通讯、仪器、仪表、汽车、船舶、航空、航天、军事装备、消费类产品等均是嵌入式linux的应用领域。`

看看嵌入式linux都具体应用在我们身边哪些方面，我们一起来了解一下：

**1.消费类电子产品**

`消费类电子产品是指这样一些电子设备,它们能提供信息服务或通过网络系统交互 信息,同时,简单易用、价格低廉、维护简便。`

`水、电、煤气表的远程自动抄表，安全防火、防盗系统，其中嵌有的专用控制芯片将代替传统的人工检查，并实现更高，更准确和更安全的性能。目前在服务领域，如远程点菜器等已经体现了嵌入式系统的优势。`

`后PC时代,计算机将无处不在,家用电器将向数字化和网络化发展,电视机、冰箱、微波炉、电话等都将嵌入计算机,并通过家庭控制中心与Internet联接,转变为智能网络家电,还可以实现远程医疗、远程教育等。目前,智能小区的发展为机顶盒打开了市场,机顶盒将成为网络终端,它不仅可以使模拟电视接收数字电视节目,而且可以上网、炒股、点播电影,实现交互式电视,依靠网络服务器提供各种服务。嵌入式系统为信息家电(网络冰箱、机顶盒、家庭网关、数字机顶盒等)的实现提供了可能和广阔的技术前景。`

![img](http://www.hqyj.com/uploads/allimg/180806/2-1PP6131159131.jpg)

2. **移动计算设备**

`包括手机、PDA、掌上电脑等各种移动设备。中国拥有最大的手机用户,而掌上电脑和PDA等因为易于使用、携带方便、价格便宜而得到了快速发展,PDA与手机已呈现融合趋势。用掌上电脑或PDA上网,人们可以随时随地获取信息。`

`新的手持设备将使无线互联访问成为更加普遍的现象。与互联网联接,结合音频应用,如MP3功能,将会促使移动计算设备市场创造新的销售记录。整合手机模块,为移动计算设备提供语音功能,也将是大势所趋。`

**3.网络设备**

`设计和制造嵌入式瘦服务器、嵌入式网关和嵌入式因特网路由器已成为嵌入式In-ternet时代的关键和核心技术。其中包括路由器、交换机等各种网络设备。基于Linux等的网络设备价格低廉,将为企业提供更为廉价的网络方案。美国贝尔实验室预测:在这阶段“将会产生比PC时代多成百上千倍的瘦服务器和超级嵌入式瘦服务器,这些瘦服务器将与我们这个世界任何物理信息、生物信息相联接,通过Internet自动、实时、方便、简单地提供给需要这些信息的对象”。`

**4.工控、仿真、医疗仪器等**

![img](http://www.hqyj.com/uploads/allimg/180806/2-1PP6131244128.jpg)

`工业、医疗卫生、国防等各部门对智能控制需求的不断增长,同时也对嵌入式微处理器的运算速度、可扩充能力、系统可靠性、功耗和集成度等方面提出了更高的要求。`

`我国工业生产需要完成的智能化、数字化改造和自动控制等工作为嵌入式系统提供了很大的市场。而工控、仿真、数据采集、军用领域一般都要求操作系统支持实时工作。`

**5.交通管理**

`在车辆导航、流量控制、信息监测与汽车服务方面，嵌入式系统技术已经获得了广泛的应用，内嵌GPS模块，GSM模块的移动定位终端已经在各种运输行业获得了成功的使用。目前GPS设备已经从尖端产品进入了普通百姓的家庭，只需要几千元，就可以随时随地找到你的位置。`

`看到了这些，你是不是觉得嵌入式linux的应用在我们生活中随处可见呢?嵌入式linux应用领域广泛，其实不止这些，所以嵌入式产品多，那随之嵌入式的人才需求也很大，选择嵌入式linux学习，是一个很正确的选择，而且也是前景最大的。`

#### 6、Linux在服务器领域的应用

`据权威部门统计，目前Linux在服务器领域已经占据75%的市场份额，同时，Linux在服务器市场的迅速崛起，已经引起全球IT产业的高度关注，并以强劲的势头成为服务器操作系统领域中的中坚力量。`

#### 7、Linux在数据中心的应用

`从最近的统计数据可以看到，全球大量数据中心的服务器已经开始向基于 Linux Server 平台转移。相较 Windows Server 而言，Linux Server 提供了更多优势。包括 Google、Twitter、Facebook 和 Amazon 在内的诸多国际互联网巨头，都在基于 Linux Server 的服务器上运转他们的服务。`

https://www.oschina.net/news/98693/top-10-reasons-use-linux-server

![img](https://ask.qcloudimg.com/http-save/developer-news/dc5buuo631.jpeg)

`云计算、大数据作为一个基于开源软件的平台，Linux占据了核心优势；据Linux基金会的研究，86%的企业已经使用Linux操作系统进行云计算、大数据平台的构建，目前，Linux已开始取代Unix成为最受青睐的云计算、大数据平台操作系统。`

#### 8、Linux在桌面领域的应用

```特别在国内市场，Linux桌面操作系统的发展趋势非常迅猛。国内如中标麒麟Linux、红旗Linux、深度Linux等系统软件厂商都推出的Linux桌面操作系统，目前已经在政府、企业、OEM等领域得到了广泛应用。另外SUSE、Ubuntu也相继推出了基于Linux的桌面系统，特别是Ubuntu Linux，已经积累了大量社区用户。但是，从系统的整体功能、性能来看，Linux桌面系统与Windows系列相比还有一定的差距，主要表现在系统易用性、系统管理、软硬件兼容性、软件的丰富程度等方面。```



#### 9、Linux基金会指出

目前Linux几乎主导了除桌面外的所有计算领域。

![1550909453209](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550909453209.png)

Linux基金会有三个不同等级的会员：银级、金级、白金级。各级别会员需承担的责任有所差别，白金级别会员同时拥有董事会席位，每年需缴纳会费50万美元。

Linux基金会会员列表： https://www.linuxfoundation.org/membership/members/

![1550911457696](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550911457696.png)

![1550911487325](C:\Users\lsr\AppData\Roaming\Typora\typora-user-images\1550911487325.png)



#### 10、微软和Linux，真正的浪漫还是有毒的爱情。



> Linux：我能最后问你一个问题吗？
>
> 微软：爱过！

放在鲍尔默掌权微软的时代，这还真难以想象。那个时候，Linux 就是鲍尔默口里的“癌症”。

2014年10月：微软 CEO Satya Nadella 先开了口：[Microsoft loves Linux](http://arstechnica.com/information-technology/2014/10/microsoft-loves-linux-as-it-makes-azure-bigger-better/) 

近几年，不仅给 Linux 贡献代码，还在微软公有云服务 Azure 上支持 Linux。一方面，微软招募了几百名 Linux 开发者和系统管理员。将 [.NET 核心框架作为一个开源的项目](https://linux.cn/article-4821-1.html)进行了发布，并提供了跨平台的支持（这样 .NET 就可以跑在 OS X 和 Linux 上了）。并且，微软与 Linux 公司合作[把最流行的发行版本放到了 Azure 平台](https://linux.cn/article-5889-1.html)上。事实上，微软已经走的如此之远以至于要[为 Azure 数据中心开发自己的 Linux 发行版](https://linux.cn/article-6269-1.html)了。

![img](http://a.36krcnd.com/photo/2015/1633df491e9349ed5964f23bbf3959f2.png)

《浪潮之巅》里曾提过，在 Google 上市前，微软一直把 Linux 作为最主要的竞争对手。那时候，PC 为王，互联网还不曾那么深刻的改写人类历史发展的轨迹。

但二十多年过去了，当初的必争之地——桌面操作系统，已经成了双方业务的一小部分，双方面对的都是更广阔的天地：互联网、移动互联网、云服务甚至物联网。最终，微软赢得了 PC 操作系统的胜利，Windows 操作系统依然运行在数以万计的 PC 设备上；

但 Linux 基金会指出 ，“目前 Linux 几乎主导了除桌面外的所有计算领域。”



# 作业

### 1、实践作业

（1）虚拟机软件vmware的下载和安装。

（2）在虚拟机中安装centos7。

（3）写出一个傻瓜式的安装教程。

### 2、调研报告

（1）常用的Linux发行版本有哪些？各自有什么特点？

（2）什么是GNU？什么是GPL?

（3）Google公司的andriod，和Linux的关系是什么？