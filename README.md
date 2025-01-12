# README

人们普遍接受了广义相对论（下称“广相”）在引力现象上所取得的巨大成功．Albert Einstein 为了推广相对性原理，使之也能够囊括引力，选择了另辟蹊径，从引力同惯性、时空几何学的关系上入手，终于在 1915 年 11 月完成了他 8 年奋斗的最后一幕——场方程．后人以“体系的精髓”冠之．在先后经历三大实验验证后，各大报纸相继对此刊登头条：“现代物理学赢来了一次伟大胜利．”

这些“神秘”数学符号固然令人费解，但我们暂时不需要完全知晓这些东西的含义．只需知道，**方程的左边关乎着引力**，**而右边关乎着物质**．这与此前 Newton 的描述方式是类似的，他选择让引力同场源的质量成正比，在距离上满足平方反比律．

比较 Einstein 和 Poisson 的方程，很明显后者的记号要通俗些，前者那可怕的符号诚然多少“败坏”了广相的名声．不过大可不必妄自菲薄，因为它们都代表了人类智慧漫漫长征的里程碑，且都以必要的概念框架为前提：Newton 理论需要微积分，而 Einstein 理论需要额外的几何学罢了．为了陈述 Newton 理论所必须的知识，已被纳入到了本科一年级教学中，譬如 3 维 Euclid 空间、坐标系、函数、导数、质量和力这样一些概念，相信诸位具有一般的数学和物理背景的读者并不陌生．至于广相的结构，或许人们就远不是这样熟悉了，但其所必须的知识并不比微积分难到哪儿去，一旦接受了，这两个方程都将变得更自然、更简单．

想要真正了解一个理论，仅仅知道怎样写出控制它的框架还远不够丰富．广相是与 20 世纪物理学所作的一些最蔚为奇观的预言联系在一起的，也许读者或多或少在 Hawking 的科普贡献中听说过一些概念，比如引力坍缩、黑洞、奇点、宇宙膨胀……这些东西在 1915 年时还未为人知，所以它们与场方程的提出没有关系．只有当后来人们懂得围绕场方程的解，去研究整体的动力学应用时，才会注意到这些现象．这件事花的时间长得相当惊人，可能人们对其中的艰辛事迹的熟悉程度，甚至还远不及对场方程背后孤勇奋斗的了解程度．因而本书将会着重讲解广相的经典应用和前沿话题，而对某些历史作简短一瞥．

本书致力对引力及时空的话题做一个全面、深入的讲述，由其教程之出发点，仅为了帮助相关专业的学生及从业人士建立必要的数学、物理基础，为理解前沿领域中相关论文作准备．本书主要内容分为三个部分：必要的基础（主要为经典内容）、对许多话题的概述（上世纪末以及千禧年的前沿、基础概念的探讨）以及随时可供查阅的附录．书的末尾附上了参考资料及索引以飨读者．

谨以此序阐明 Part I 内容之深度、广度，有如下考虑：

以理工类专业大一学习的微积分和线性代数为基础．具体地，笔者将假定读者已完整地、熟练地掌握多元微积分的场论符号，了解一点分析学和线性空间，故本书所穿插的数学知识只会是上述内容中没有完整涉及的部分．在介绍新内容时，笔者将在教程中尽可能多地提示读者，新内容与其所学过的哪些内容相关（甚至精确到某些书籍的章、节、页码）．希望读者在比较后能够同意，笔者在此教程中介绍的新知识不是完全陌生的．

穿插刨析后续物理理论所需要的基础数学概念．例如，在引入时空的概念（第X章）时，需要用到集合的划分与等价类的知识，因此笔者会在期间穿插集合关系的知识．亦如，作为基础概念的各类张量，在本教程中会事先简化成“向量复合出来的数组”，并引入微分几何（第X章）后将其定义为线性变换．按照上一条假定考虑读者的数学基础，仍需要比较详尽地介绍有限维向量空间及其上的线性变换的知识．

采用坐标依赖（详细讲解并使用 Einstein 求和约定）与无坐标依赖（数学系符号为主，抽象指标仅作简介）交互的表达风格．笔者希望这种做法本身能彰显广相的建立者希望实现的物理客观性，既物理规律（数学表达式）不依赖包括坐标系的选择在内的任何主观选择；但同时在面对具体应用问题时，仍然保留建立曲线坐标系的权利．此时向量和线性变换的坐标关系需要曲线坐标系的知识．

本书将不会设置习题，仅讲解足够读者学习进程的例题，为了使过程详尽将会使用彩色标注的方式。仅为了证明某定理所需的数学概念和引理，要么给出简介，要么放在附录中讲解．

定理的证明过程，仅供有兴趣的读者参考，故未必都提供．不提供时，笔者尽可能提出其他提供了证明过程的参考资料（具体到章、节、页码）．例如：Reynolds 传输定理的证明（附录XX）、等距变换的表示定理的证明（附录XX）．

本教程用不到的数学知识，不作介绍，部分放入附录．例如，在拓扑学（第X节）中提到了部分公理集合论的公理，但又假定关于自然数、算术运算、偏序、全序、数学归纳法等知识为暂时无需，包括 Peano 公设在内的相关的内容．故关于微分几何章节的最终状态，深度上似乎要介绍玩微分拓扑，但广度上又不完整．这是笔者故意为之的．因为本教程的目标不是要向读者大肆介绍数学知识，而是补充看懂广相前沿进展的最少必要的、作了严格定义的数学知识．

一般情况下，概念的定义仅通过字体的改变来暗示．例如，\emph{集合（set）}是具有某种特性的事物的整体．仅在需要时，定义才以带编号的方式引入．而定理、引理和例子则均带编号．定义是极其重要的．它在文中只出现一次，因此难免要经常反复回顾．不采用带编号式的引入，只是因为需要定义的概念很多，如果每个定义都带编号定义将会严重打断行文的流畅性，让本就不易的内容雪上加霜，而代价则是使定义失去了引用链接的便利，故在此敬请读者在学习时要不厌其烦地翻阅回顾定义．

Part II 将在其完成时再介绍

夏璇

于北京