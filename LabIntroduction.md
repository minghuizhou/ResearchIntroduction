# ResearchIntroduction 研究组介绍

## 研究领域

言简意赅，我们实验室的主要研究对象是开源软件开发，任何涉及开源开发的效率和质量的方法、技术和工具都在其列。我们的学科领域主要是软件工程，但也涉及系统软件、人机交互、社会计算等领域。

开源软件开发主要涉及三个要素：软件，开发软件的个体和群体，以及开发者开发软件的方法、技术和工具。因此我们的研究也大概分为两类，一类偏人的行为的研究，包括个体行为和群体协作行为；一类偏技术性的研究，例如怎么设计自动化工具支持各种开发活动。前者更多是发现型研究，后者更多是发明型研究。

我们实验室长期而来一直聚焦于在软件工程领域进行**发现型**的研究。为什么软件工程领域需要发现型的研究，而不仅仅是去开发算法、系统与工具呢？第一个原因是，软件开发虽然以数学作为理论基础，并由计算机技术加以支撑，但是**归根结底还是人的活动**。比如说，开发一个软件不仅需要**人**与**技术**进行**极其复杂而又不能出错的交互**；也需要**人**与**人**之间进行**交流**与**组织**；还需要降低技术的**门槛**（例如控制代码的复杂度、编写技术文档等），使得不那么聪明的人也能参与软件开发。由于我们对人类智能的有限认识，这些问题是难以采用数学的方法去解决的，需要通过对历史事件的分析与反思，反复迭代得到最优的解决方案。第二个原因是，真实的软件开发场景极端复杂，很多问题也不太可能存在一个通用的解决方案(所谓的不存在Silver Bullet)，使得**定义合适的技术问题本身就不太容易**，需要科学的证据和观点加以支持。因此，如果没有发现型的研究对**软件工程研究**和**软件开发实践**做出科学的指导，人们可能会在伪技术问题上浪费时间，拍脑袋的管理决策也可能会产生非常可怕的后果。感兴趣的读者可以看一看《人月神话》这本书，了解上世纪60年代IBM开发操作系统时遇到的各种问题。同时期的著名计算机科学家Edsger W. Dijkstra曾经这么评论过当时的“软件工程”：

> The required techniques of effective reasoning are pretty formal, but as long as programming is done by people that don't master them, the software crisis will remain with us and will be considered an incurable disease. And you know what incurable diseases do: they invite the quacks and charlatans in, who in this case take the form of Software Engineering gurus. (翻译：写代码需要很高的姿势水平，可是写代码的人一般都是傻瓜，所以他们总是写不出好软件。总是写不出来，就会引来一帮“软件工程”砖家；但是砖家们的观点啊，都too young, too simple, sometimes naïve!)

当然，随着软件行业近六十年的发展，现在我们已经没有所谓的“软件危机”，倒不如说处在一个“傻瓜竟然也能开发软件”的时代。借助各种软件开发工具和成熟开源生态系统的支持，从小学生到北大青鸟速成班学员，都能在很短的时间内写出实际可用的应用程序。软件行业能走到今天，终究离不开众多软件行业实践者和软件工程研究人员的共同努力。

为了进行发现型的研究，需要采用某种研究范式。我们的研究范式主要是通过**观测/挖掘/分析软件开发活动数据**，或者通过**访谈/发问卷调查相关的人员**来完成。控制变量实验相对较少见，主要原因在于软件开发的高成本和不可控性，使得这种实验不仅在成本上难以接受，也很难得到贴近现实的结果。由于软件开发活动不仅极端复杂还包含人类参与，基本没有采用计算机模拟来回答实际问题的研究。
> 在传统学科中，发现型研究有很多常用的研究范式，比如实地调研(Field Study)、实验室实验、计算机模拟等等，关于这些范式的详细介绍可以参考[Stol, Klaas-Jan, and Brian Fitzgerald. "The ABC of software engineering research." ACM Transactions on Software Engineering and Methodology (TOSEM) 27.3 (2018): 1-51.]。

上述加粗的两种研究方法之所以能成为主流范式，主要是要感谢近年来**开源软件**的流行与成功。由于开源软件普遍奉行数据开放的原则，且成功的开源软件往往具有极高的代码质量和项目管理水平，从而这些开源软件项目提供了**海量的真实软件开发活动数据**，从而能够用于回答之前由于缺乏数据而难以回答的大量问题（使用企业数据去做公开发表的研究往往是比较困难的）。于此同时，**“开源”这个模式本身，也带来了大量的全新问题**，例如开源项目要如何可持续发展，企业要如何参与开源等等。

具体到我们实验室的研究而言，我们的**研究对象**主要是开源软件的软件开发活动数据；**研究目标**通常是观察和度量大规模软件项目或生态中人们的开发行为，量化开发者与其环境和软件制品之间的关系，以期理解和掌握控制大型复杂软件系统的方法；**研究风格**通常是从某一个软件开发中普遍存在的实际问题出发，利用数据挖掘与分析对问题本身进行深入和全面的探索；如有必要，通过访谈和问卷验证我们的结论；如有可能，基于前面的结果尝试进行量化与建模，使用模型验证我们的结论，并建立推荐工具，对软件开发各种实践活动进行预测和推荐。

我们常常使用**开源软件量化分析**这个词来总结，也可以使用以下关键词来总结我们实验室当前的研究领域：

| 一级学科       | 软件工程（Software Engineering）                      |
| -------------- | ----------------------------------------------------- |
| 细分领域关键词 | 数据驱动的软件开发（Data-Driven Software Development) |
|                | 软件仓库挖掘（Mining Software Repositories）          |
|                | 软件度量（Software Measurement）                      |
|                | 实证/经验软件工程（Empirical Software Engineering）   |
|                | 软件数字社会学（Software Digital Sociology）          |
|                | 软件数字考古学（Software Digital Archeology）         |

## 研究对象

之前提到，我们实验室的主要研究对象是**软件开发活动数据**。这是一个非常宽广的概念。一般而言，只要是在软件开发过程中产生的数据，都可以称作软件开发活动数据，包括但不限于

* **源代码(Source Code)**：对于开源软件而言，代码显然是最容易获取到的数据，也是最重要的基础数据。有研究可以仅仅观察源代码来总结开发者的使用模式，例如：开发者如何在Java中使用继承(Stevenson and Wood, ICSE 2018)？什么样的Python代码才是“Pythonic”的代码(Peng et al., SANER 2021)？等等。当然，更多的时候，源代码是作为基础数据，与其他数据相结合来回答各种复杂的问题，例如与版本控制数据相结合来研究代码重构，等等。
* **文档(Documentation)**：软件工程教材中常见一个说法：软件就是代码+文档。可见，源代码只有有了配套的文档，才能让一群人都能够真正理解、使用、开发、和维护。文档的类型包括但不限于：代码注释(Comment)、API文档(API Documentation)、教程(Tutorial)、工作流文档(Workflow Documentation)，等等。对文档数据的研究一般有两个方向，一是总结关于各种各样的软件文档的最佳实践；二是利用软件文档辅助其他方面的研究，例如通过API文档的演化来分析软件的兼容性等等。
* **配置文件(Configuration Files)**：现代软件开发不仅需要依赖各种其他软件（工具链/运行环境/框架/库等），还常常需要对其他软件进行深度定制以符合自己项目的需求。为此，便产生了各种各样的配置文件，例如对项目依赖的配置文件、对项目持续集成(Continous Integration)的配置文件、对代码静态分析工具的配置文件、等等。一般而言，对配置文件的研究主要是通过分析已有的配置文件，来观察相关的开发者/生态系统的行为，从而提出改进策略。
* **变更(Changes)**以及变更相关的文档：软件并不是一成不变的，而会持续地变化来适应新的需求。很多工具和管理过程都是为了适应变更而产生的，其中最重要和最著名的就是以git为代表的版本控制系统。git中记录的变更历史数据支撑了几乎所有关于软件演化的研究。
* **开发流程(Development Process)**：为了协同多人协同进行软件开发，需要有高效的软件开发流程。目前，绝大多数开源项目都是采用Bug Report (Issue) + Patch (Pull Request) + Release的开发流程。这个流程中产生的数据，不仅可以用于观察和改进目前的开发流程，还可以用于观察各种人与人之间交互的有趣现象。
* **开发者(Developers)**：开发者在开源社区中自身留下的轨迹，也可以作为一种独特的研究数据。目前，对开发者的刻画研究相对较少，已有研究曾经刻画过开发者的工作习惯、领域专长、任务偏好等等。
* **包管理平台(Package Hosting Platforms)**： Maven, npm, PyPI, etc
* **社交数据(Social Data)**：Mailing List, Stack Overflow, Twitter, Slack, etc

## 研究问题

但凡软件工程领域，任何研究问题都需要与提高开发效率和软件质量相关，即相关性（relevant）。另外需要具有的特点：

1. 前沿性(novel)：选题应聚焦于有新意的问题，进行创新和深入的研究。

2. 普遍性(non-trivial)：问题和解决方案需要有一般性，不能只针对极个别群体。

我们的研究主要围绕着**开源软件**与**开源社区**，使用这些数据来解答**代码**、**文档**、**社区**与**生态**有关的问题。关于我们正在研究的具体问题，可以参考“推荐文献”一节中后面的列表。

## 研究方法

### 数据集

大量研究会直接使用GitHub上的项目数据，也有一些非常常用的公开数据集，例如Libraries.io, GHTorrent, World of Code等。此外，互联网上成千上万开源项目的数据都是开放的，可获取的软件开发活动数据非常多。一般来说，开源项目都会支持在线问题追踪系统，版本控制系统和邮件列表等，例如[Mozilla 的在线issue tracking system](https://bugzilla.mozilla.org/show_bug.cgi?id=1000000)、[Linux kernel 的在线代码库(mainline code repository)](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git)、[Linux kernel 的在线邮件列表(mailing-list)](https://lkml.org/)等。可以编写爬虫，面对你的实际研究问题，获取各种各样的数据。

### 分析方法

总的来说，使用什么样的分析方法，完全取决于你手边正在进行的课题的情况。一般而言，要得到简单的描述性结果，按直觉进行简单的数据分析与可视化即可；如果要得到相关性或者因果的结论，则需要用到各种统计学工具，例如相关性分析、回归分析、显著性检验等等；如果需要对复杂现象进行系统性的描述与总结，一般则采用某种定性研究的方法，例如主题分析(Thematic Analysis)等。

本文不想过多地局限于介绍某些具体的工具，一方面是因为，为了进行某种分析去自学相关工具应当是一个必备技能；另一方面，不同人对不同工具有不同的偏好，使用的效率往往也是不一样的。这里提供一个（并不完整的）常用工具列表：

* 原始数据处理：Shell Scripts, Perl, Python

* 数据分析：R language, Python + pandas + matplotlib + Seaborn, Jupyter Lab

* 定性分析：interviews, surveys, open coding, thematic analysis


## 推荐阅读

### 领域科普文章

1. Brooks Jr, Frederick P. *No Silver Bullet – Essence and Accident in Software Engineering*. April, 1987.
2. Brooks Jr, Frederick P. *The Mythical Man-Month: Essays on Software Engineering*. Pearson Education, 1995.
3. 邹欣. 构建之法: 现代软件工程. 人民邮电出版社. 2017年6月.
4. Eric Raymond. 大教堂与集市. (有中文版，卫剑钒翻译，卫sir是北大软件所博士毕业)
5. 周明辉, 郭长国. 基于大数据的软件工程新思维.  中国计算机学会通讯. 第十卷第3期. 2014年3月.
6. 周明辉, 张伟等. 开源软件的量化分析.中国计算机学会通讯. 第十二卷第2期. 2016年2月.
7. 周明辉, 张宇霞, 谭鑫. 软件数字社会学. 中国科学信息科学. 2019. 49(11). 1399-1411.

**注解：** [1] [2] 是软件工程早期的重要文献，[1] 最早阐述了“软件工程没有通用解决方案”的核心论点，可直接Google到全文；[2] 则记录了IBM在60年代组织开发System/360操作系统的经验教训，国内有中译版，但是翻译非常生硬，推荐寻找英文PDF原版阅读；[3] 是一本软件工程入门教材，可在网上买到，和其他教材相比，内容简短易懂，行文生动有趣，非常适合作为闲暇读物；[4] [5] [6] 是关于我们实验室研究领域的概述。

### 领域早期工作

1. Mockus, Audris, Roy T. Fielding, and James D. Herbsleb. "Two case studies of open source software development: Apache and Mozilla." *ACM Transactions on Software Engineering and Methodology (TOSEM)* 11.3 (2002): 309-346.
2. Herbsleb, James D., and Audris Mockus. "An empirical study of speed and communication in globally distributed software development." *IEEE Transactions on Software Engineering* 29.6 (2003): 481-494.
3. Mockus, Audris, and David M. Weiss. "Globalization by chunking: A quantitative approach." *IEEE Software* 18.2 (2001): 30-37.
4. Parnas, D.L. (December 1972). "On the Criteria To Be Used in Decomposing Systems into Modules". Communications of the ACM. 15 (12): 1053–58.
5. Conway, M. E. (1968). "How Do Committees invent?" Datamation 14(4): 28-31.

注解：使用数据探索开源开发和全球分布式开发是本领域的开拓性工作(也是读起来有美感的论文)，需要尤其关注其研究问题和研究方法及其跟软件开发效率和质量的关系。Parnas是软工先驱，他在软件模块化方面的工作至今无人逾越[4]。康威定律[5]是社会管理学文献，Brooks根据他在IBM 360项目的经验在其《人月神话》中主张康威定律在软件开发中的应用和重要性，从此社会技术一致性思想在软件工程延展。

### 组内主要工作


#### 软件项目如何吸引和指导newcomer（涉及developer expertise，newcomer onboarding and retaining，long term contributor等）

1. Zhou, Minghui, and Audris Mockus. "Developer fluency: Achieving true mastery in software projects." *Proceedings of the eighteenth ACM SIGSOFT International Symposium on Foundations of Software Engineering*. 2010.
2. Zhou, Minghui, and Audris Mockus. "What make long term contributors: Willingness and opportunity in OSS community." *2012 34th International Conference on Software Engineering (ICSE)*. IEEE, 2012.
3. Zhou, Minghui, and Audris Mockus. "Who will stay in the floss community? modeling participant’s initial behavior." *IEEE Transactions on Software Engineering* 41.1 (2014): 82-99.
4. Minghui Zhou. Onboarding and Retaining of Contributors in FLOSS Ecosystem. *In book "Towards Engineering Free/Libre Open Source Software (FLOSS) Ecosystems for Impact and Sustainability"*, Springer, Singapore, pp:107-117, 2019. 
5. Tan, Xin, Minghui Zhou, and Zeyu Sun. "A first look at good first issues on GitHub." *Proceedings of the 28th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering*. FSE 2020.
6. Wenxin Xiao, Hao He et al. "Recommending Good First Issues in GitHub OSS Projects". ICSE 2022

#### 开源社区：Linux代码提交实践和社区可扩展性

1. Zhou, Minghui, et al. "On the scalability of Linux kernel maintainers' work." *Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering*. 2017.
2. Xu, Yulin, and Minghui Zhou. "A multi-level dataset of Linux kernel patchwork." *2018 IEEE/ACM 15th International Conference on Mining Software Repositories (MSR)*. IEEE, 2018.
3. Tan, Xin, and Minghui Zhou. "How to communicate when submitting patches: An empirical study of the linux kernel." *Proceedings of the ACM on Human-Computer Interaction* 3.CSCW (2019): 1-26.
4. Xin Tan and Minghui Zhou. "Scaling open source software communities: Challenges and practices of decentralization." *IEEE Software* (2020).

#### 开源项目中的公司参与

1. Zhou, Minghui, et al. "Inflow and retention in OSS communities with commercial involvement: A case study of three hybrid projects." *ACM Transactions on Software Engineering and Methodology (TOSEM)* 25.2 (2016): 1-29.
2. Zhang, Yuxia, et al. "Companies' domination in FLOSS development: An empirical study of OpenStack." *Proceedings of the 40th International Conference on Software Engineering: Companion Proceeedings*. 2018.
3. Zhang, Yuxia, et al. "Companies' participation in OSS development: An empirical study of OpenStack." *IEEE Transactions on Software Engineering* (2019).
4. Zhang, Yuxia, et al. "How do companies collaborate in open source ecosystems? An empirical study of OpenStack." *2020 IEEE/ACM 42nd International Conference on Software Engineering (ICSE)*. IEEE, 2020.

#### 软件依赖/开源供应链

1. Hao He, et al. A Large-Scale Empirical Study on Java Library Migrations: Prevalence, Trends, and Rationales. FSE 2021. Aug 2021.
2. Hao He, et al. A Multi-Metric Ranking Approach for Library Migration Recommendations. Proceedings of the 28th IEEE International Conference on Software Analysis, Evolution and Reengineering. 2021
3. Hao He, et al. MigrationAdvisor: Recommending Library Migrations from Large-Scale Open-Source Data. ICSE 2021 Tool Demo.
4. Xin Tan, et al. An Exploratory Study of Deep Learning Supply Chain. ICSE 2022.
5. Kai Gao, et al. On the Variability of Software Engineering Needs for Deep Learning: Stages, Trends, and Application Types. Transaction on software engineering. 2022/03. accepted

## 正在进行的课题（2022.03）

1. **SE for AI**：
   1. 开发者在应用深度学习时遇到的困难？
   2. 深度学习框架的API演化情况？开发者在不同深度学习框架之间的流动情况？
   3. 不同深度学习框架的比较：技术/应用演化和未来
2. **(开源)软件供应链**：
   1. 供应链结构、要素的度量和风险节点的刻画
   2. 什么因素会影响一个(供应链中)软件包的下游项目数量？
   3. 如何消解软件供应链上的安全漏洞？
   4. 不同生态中软件包之间的迁移情况的共性和差异性？
   5. Dependabot等依赖管理工具的使用情况如何，有没有改进点？
3. **软件开发中关键制品(和工具)的实证研究（landscape, challenges and improvement）**：
   1. 开发者是如何写注释的？注释是如何演化的？
   2. 新的检测代码与注释不一致的工具？
   3. 软件项目是如何组织和撰写Release Note的？
   4. 现有的Release Note生成工具的使用情况？有没有改进点？
   5. 现有代码静态分析工具的使用情况？有没有改进点？
4. **各种bot/dashboard的改进和研发**
   1. release note自动生成bot
   2. good first issue自动推荐bot
   3. dependency update bot
   4. license compilance check bot
   5. ...

注解：我们组目前的代表工作在于研究程序员、制品及环境的量化关系(跟组长个人意趣有关)。研究对象从个体(成熟度、学习途径、环境影响)到群体(沟通、协作和群智)，到生态(可持续性、可演化性)，以及软件供应链（依赖和风险）。
