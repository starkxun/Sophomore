### 大二下学期课程资料整理





- [x]  **编程**

​	一份编程[指南](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started)

​	推荐学习的书籍：**《计算机程序的结构和解释》**，我们建议至少学完 SICP 的前三章，并完成配套的习题

> [配套课程资源](https://github.com/DeathKing/Learning-SICP)
>
> [课程视频](https://www.bilibili.com/video/av8515129/)







- [x]  **计算机组成原理**

​	学这门课程之前，要先忘掉这门课程名字中的“计算机”三个字。每节课，每个课程阶段都会介绍一种电路。从简单到复杂，从开关到ALU。每个阶段做出来的东西看起来都和“计算机”没什么关系，除了他们都能存储和运算。但是会很清楚的了解到每个阶段做出来的东西其实完全没有“存储”和“运算”功能。他们只不过是一种电路的状态，或者通过一个信号，控制另一部分电路的状态。由于很简单，很容易弄清楚这个东西是如何工作的。最后把所有东西拼成一块CPU的时候，就像你趴在地上拼拼图，拼完最后一块起身俯视的感觉。会了解到高低电平是如何通过各种门电路变成数据，变成屏幕上花花绿绿的程序的。这就是所谓的“原理”。

这门课完全可以用一个词来概括，就是“抽象”。在我看来这也是整个计算机设计中所蕴含的的灵魂。

推荐书籍：**《深入理解计算机系统》**，人称**CSAPP**。这本书是从程序员的角度学习计算机系统是如何工作的，通过描述程序是如何映射到计算机系统上，程序是如何执行的，以及程序效率低下的原因，这样的方式可以让大家能更好的知道「程序与计算机系统」的关系。

CSAPP 涵盖的内容非常多，有**计算机组成 + 操作系统 + 汇编 + C语言 + Linux系统编程**，涉猎的领域比较多，是一本综合性的书，更是一本程序员修炼内功的指引书。

CSAPP 主要包括以下内容：

- 信息表示（如何使用二进制表示整型、浮点数等）；
- C 和汇编语言的学习（通过汇编语言更深入地理解C语言是什么）；
- 计算机体系结构（存储层次结构、局部性原理、处理器体系结构）；
- 编译链接（C语言如何从文本变成可执行文件、静态链接、动态链接）；
- 操作系统的使用（异常控制流、虚拟内存、多个系统调用介绍）；
- 网络及并发编程（并发的基本概念、网络相关的系统调用的介绍）。

[配套学习视频（中文版）](https://www.bilibili.com/video/BV1iW411d7hd)

[课程配套lab](http://csapp.cs.cmu.edu/3e/labs.html)  友情提示，理论课可以逃，但实验课绝对不能逃。算法也好，理论也好，玩具也好，如果自己不亲自拆一遍再装回去，就没办法深刻理解它们是怎么跑起来的。

下面是一些大佬的lab实验笔记

> [《深入理解计算机系统》第三版的实验文件、解答与笔记](https://github.com/Exely/CSAPP-Labs)
>
> [cuzz的博客](https://blog.cuzz.site/2020/10/11/CSAPP_Data_Lab/)
>
> [对csapp全8个实验的记录](https://www.zhihu.com/column/c_1325107476128473088)

《深入理解计算机系统》[电子版](https://hansimov.gitbook.io/csapp/)

《深入理解计算机系统 讲师版》[电子版](https://hansimov.gitbook.io/csapp/labs/data-lab/readme-instructor)

这里也贴一份学习[路线图](https://zhuanlan.zhihu.com/p/77528688)，可供参考

然后来推荐一些游戏：

1. 《人力资源机器》 steam上有卖
2. [缺氧](https://store.steampowered.com/app/457140/_/)

> ​	里面的逻辑电路相关的内容可以提供具体案例,提高对逻辑门的感性认知.同时可以衍生出很多机制相关的思考,比如 具体的问题转化为数理逻辑,小人作业并发冲突,随机地图生成,权限管理,复杂功能分区规划等等.

3. [Human Resource Machine](https://store.steampowered.com/app/375820/Human_Resource_Machine/)

> ​	这个可以最直观的展示指令和运算的关系,上文也说过了和组原大作业有千丝万缕的联系.另外通过关卡提供了较为平稳的曲线,可以提前规避因为理解力不足带来的挫败感.这个游戏还有一个多线程版本：[7 Billion Humans](https://store.steampowered.com/app/792100/7_Billion_Humans/)

4. [Opus Magnum](https://store.steampowered.com/app/558990/Opus_Magnum/) 

> 前置知识要求低,极为艺术的逻辑呈现,完成之后真的会有炼金一般的快感.

5. [TIS-100](https://store.steampowered.com/app/370360/TIS100/)

> 汇编王中王









- [x] **操作系统**

​	 **操作系统是一门实践性很强的，光看书不动手很容易出现背书的情况**  强烈推荐理论加实践。

书籍推荐：**《操作系统导论》**，这本书的习题很值得一做。

国内相关课程：

- ​	[学堂在线清华OS课程](https://www.xuetangx.com/course/THU08091000267/10322317)

- ​	[清华大学操作系统课程(2019)](https://chyyuu.gitbooks.io/os_course_info/content/)

  >   2019年春季开课，16周完成，主要包括：操作系统结构、中断/异常与系统调用、OS启动、内存管理、进程/线程管理、调度、同步扶持、进程间通信、死锁处理、文件系统、I/O系统

- ​	[2020 南京大学计算机系统基础习题课 (蒋炎岩)](https://www.bilibili.com/video/BV1qa4y1j7xk)

  > ​    NJU ICS的主讲老师[蒋炎岩](https://www.zhihu.com/people/jiang-yan-yan-75)是位非常宝藏的老师，乐于分享自己的一些科研内容和世界观。
  >
  > 其中NJU ICS课程不仅有非常详尽的[课程文档](https://nju-projectn.github.io/ics-pa-gitbook/ics2019/)，该文档读起来简直就像是游戏攻略一般过瘾

相关习题：

- ​	[OS课程练习](https://chyyuu.gitbooks.io/os_course_exercises/content/)
- ​    [操作系统实验：基于 uCore OS](https://www.lanqiao.cn/courses/221)

国外相关labs：

- ​	[MIT 6.828](https://pdos.csail.mit.edu/6.828/2018/schedule.html)

6.828是麻省理工学院操作系统课程的一个配套lab，网上有[配套课程](https://www.bilibili.com/video/BV1px411E7ST)，但是没有中文字幕，对听力要求较高。

以下是网上前辈们的6.828笔记，供参考：

> [MIT 6.828 实现操作系统](https://www.zhihu.com/column/c_1273723917820215296)
>
> [实现一个操作系统内核](https://github.com/woai3c/MIT6.828)
>
> [强撸MIT之6.828](https://goushi.me/mit-6-828/)

**系统文档**：CyC2018 大佬的 GitHub Notes 之计算机操作系统 ，看仓库目前已有 99.9k star，在 GitHub 里面搜索「计算机操作系统」直接排序第一页就是这个[仓库](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%20-%20%E7%9B%AE%E5%BD%95.md)。

这里再贴一份博文：[写给大忙人看的操作系统](https://www.cnblogs.com/cxuanBlog/p/12376364.html)

另外，如果你还想自己写一个（模仿） mini os，那么你需要一些前置依赖知识，否则估计会被很多硬件、汇编知识劝退： 

​	筑基内功-- 需要学习计算机原理、C语言（需要熟练运用）、数据结构课程 

​	工欲善其事，必先利其器，掌握以下Linux 下常用命令行：

> pwd、cd、find等，1-2 款趁手的编辑器，推荐掌握 vim 的基本操作 gcc、gdb、ld、make等编译构建链、objdump、nm、readif、dd 等 ELF 文件分析、烧录工具。









- [x]  **计算机网络**

​	鉴于有那么多关于网络服务端和客户端的软件工程，计算机网络是计算机科学中价值最为「立竿见影」的领域之一。

推荐书籍：

1. **《计算机网络（原书第7版）: 自顶向下方法》**，可以在这里读到[英文原版](https://www.ucg.ac.me/skladiste/blog_44233/objava_64433/fajlovi/Computer%20Networking%20_%20A%20Top%20Down%20Approach,%207th,%20converted.pdf)

2. **《图解HTTP》**
3. **《网络是怎样连接的》**

相关课程和lab：

> 推荐Stanford课程[cs144](https://cs144.github.io/)，配合《计算机网络：自顶向下方法》（Computer Networking: A Top-Down Approach）。具体来说就是跟着cs144的课程安排走一遍，**完成课程的lab**啦。

其实觉得cs144的[公开视频](https://search.bilibili.com/all?keyword=cs144&from_source=nav_search_new)讲得挺一般的，但是cs144新的lab真的很棒。lab的很大一部分是让你自己从零开始去写一个真实能用的tcp。写一遍之后，对tcp工作的原理以及设计思想就会有深得多的理解。**毕竟研究表明，能自己实现一个tcp的人，很少有理解不了tcp原理的。**

但是这个lab也有一些问题，坑点大概有以下这些：

1. 有一些设计的选择细节并没有在PDF里给出，我有的时候需要去看test case才会知道Lab希望怎样去设计。不过也许这些内容在上课的时候会提到。另外这也暴露了自学网课的一个问题：没有TA以及同学可以交流。所以大家自学网课的时候也可以找一些小伙伴一起学，搞一个“虚拟课程”甚至是“虚拟大学”。
2. Lab2和Lab3的test case不够多，导致错误或者是与Lab期望的设计不符的实现也能通过全部的test case。然后在Lab4里，这些问题会全部暴露出来......结果就是在做Lab4的时候完全不能信任自己在Lab2和Lab3里的相应实现，这样也大大增加了debug难度。
3. Lab4里有两个test case即fsm_ack_rst和fsm_ack_rst_relaxed期待的行为是完全相反的。实际上在官方的FAQ页面上给出的状态机是与fsm_ack_rst期待的行为一致，但Lab4默认启用的却是fsm_ack_rst_relaxed......
4. 官方提供的VirtualBox Image中的GDB是有bug的，在cmake_build_type=Debug生成的binary上不能正确地打断点。在Lab4之前我还能靠肉眼调试，但是Lab4实在是肉眼调不动了，不得不寻求解决方案。后来问了一位之前也做过这个Lab的清华大佬[@RT Huang](https://www.zhihu.com/people/47ee4a7553348d5300b026fb4a3f4dc2)，他告诉我说他用的是LLDB。我就赶紧换了LLDB，这才能愉快的进行调试。顺带一提，这位大佬在GitHub上有自己完成[这门课程和Lab的笔记](https://github.com/huangrt01/CS-Notes)，也是值得参考的Orz 



不过瑕不掩瑜，这门课程的Lab无疑是非常好的材料。扎实地掌握TCP的最好办法也许就是自己去写一个能用的TCP，写完之后对各种细节就会掌握得扎实很多，对背后的设计思想也会有更深的理解。真是眼红美国名校的课程资源啊，也希望国内的高等教育能迎头赶上吧。



然后下面这些资源可供参考：

​	[15-441/641 Computer Networks](https://computer-networks.github.io/sp19/lectures.html)

​	[30天自制C++服务器](https://github.com/yuesong-feng/30dayMakeCppServer),如果可以，建议自己可以照着教程实现一遍













- [x] **数据结构**

​	这部分建议看书+看视频+刷题。不推荐《算法导论》，一上来就啃这个大块头肯定啃不动。直接推荐一些容易上手的资源：

​	[CMU数据结构公开课1](https://www.coursera.org/learn/algorithms-part1)

​	[CMU数据结构公开课2](https://www.coursera.org/learn/algorithms-part2)

​	[数据结构和算法动态可视化](https://visualgo.net/zh)

刷题平台（OJ）：

- ​	[洛谷](https://www.luogu.com.cn/)

- ​	[vijos](https://vijos.org/)
-    [codeforces](https://vijos.org/)
-    [leetcode](https://leetcode-cn.com/?utm_source=LCUS&utm_medium=banner_redirect&utm_campaign=transfer2china)
-    [code jam](https://codingcompetitions.withgoogle.com/codejam)
-    [lintcode](https://www.lintcode.com/)

一份解题笔记：

​	[用Go语言刷leetcode](https://books.halfrost.com/leetcode/)







- [ ] **web系统开发**

- [ ] **数据库**

- [ ] **汇编语言与接口技术**

- [ ] **单片机**

- [ ] **MATLAB仿真与应用**

- [ ] **Java EE框架开发**

- [ ] **数字图像处理**

- [ ] **嵌入式系统开发**

- [ ] **嵌入式Linux内核编程**

- [ ] **并行计算与分布式系统**

- [ ] **移动设备应用开发**
