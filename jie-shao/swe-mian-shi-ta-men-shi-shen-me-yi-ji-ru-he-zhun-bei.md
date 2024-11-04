---
description: 软件工程师面试：您需要准备的一切
---

# SWE面试：它们是什么以及如何准备

👋 大家好，我是[Tony Yip Chak-wai](https://app.gitbook.com/s/Ju5U8038TCdn0p6Rvp6h/)，可以叫我 Tony Yip 或者 Tony。

没有人有时间去研究数百道 LeetCode 问题，好消息是你不需要做那么多题就能真正得到 FAANG 的工作！

我对在东南亚拼车公司 Grab 的工作感到沮丧，想打入 FAANG，但不知道如何去做。经过几个月的研究、学习和实践，我面试了 11 家公司，并成功获得了 9 份来自湾区顶级科技公司的录用通知——Facebook、Google、Airbnb、Palantir、Dropbox、Lyft 和一些初创公司。这是一个乏味的过程，我不想再经历一次。**我经历了这个过程，但有了本指南，您就不必这样做了。**

本指南将**快速概述有关如何准备软件工程师面试（技术和非技术面试）的重要技巧**。如果相关，您可以通过访问本概述文章中的链接或通过网站的左侧边栏深入了解更多详细信息。

如何准备软件工程面试：

1. [最大限度地提高您入围的机会](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#zui-da-hua-nin-ru-wei-de-ji-hui)
2. [了解面试形式](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#liao-jie-mian-shi-xing-shi)
3. [选择一种编程语言](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#pick-a-programming-language)
4. [提高面试所需的计算机科学基础知识](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#bian-ma-mian-shi-de-xue-xi-he-lian-xi)
5. [编码面试练习](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#bian-ma-mian-shi-de-xue-xi-he-lian-xi)
6. [准备系统设计面试（中/高级）](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#zhun-bei-xi-tong-she-ji-mian-shi)
7. [准备行为面试](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#zhun-bei-xing-wei-mian-shi)
8. [谈判报价包](swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md#negotiating-the-software-engineer-offer-package)

### ★最大化您入围的机会

您是否仍然难以入围部分或全部顶级科技公司？你的简历可能是问题所在。

您的简历是入围 FAANG / MANGA 等主要科技公司的最重要的切入点。入围后，与你的编码面试技能相比，你过去的成就明显变得不那么重要了——据我们所知，编码面试技能是可以有条不紊地学习的。因此，能够很好地描述您过去的成就以通过筛选阶段非常重要。

不幸的是，即使是我个人认识的最合格的候选人也不知道如何写一份好的简历而未能入围。事实是，当我们中的许多人没有入围 FAANG / MANGA 这样的顶级科技公司的候选名单时，我们往往会认为自己资质不足 - 但在大多数情况下，这可能只是缺乏良好的框架。

如果你想学习如何撰写一份优秀的软件工程师简历，我在这里撰写了一篇关于如何为谷歌、Facebook、亚马逊、Netflix、苹果等公司[准备软件工程师简历的分步指南](../huo-de-mian-shi-ji-hui/zhuan-xie-ruan-jian-gong-cheng-shi-jian-li.md)，并附有示例供你参考。

### ★了解面试形式

在软件工程师面试中（从早期到后期），您可能会遇到各种面试形式：

#### ◇1. 测试

频率： 偶尔

测验旨在成为第一道过滤器，作为一种快速而肮脏的方式来淘汰极其薄弱（甚至非技术）的候选人。它们是结构化的问题，并且有明确的答案，这使得招聘人员/非技术人员或自动评分人员可以管理它们。它们通常在流程的早期完成。

示例：

* 4 & 5 等于多少（二进制）？答案：4
* 冒泡排序的时间复杂度是多少？答案：O（n^2）

#### ◇2. 在线编码评估

频率： 偶尔

与测验一样，在线编码评估通常在流程的早期进行。给出一个具有格式良好的输入和输出的算法问题，考生需要在在线编码界面中编写代码来解决该问题。 [HackerRank](https://www.hackerrank.com/)是一个非常常见的进行在线编码评估的平台。 LeetCode 将是练习在线编码评估问题解决方面的好方法。然而，在 HackerRank 中，您通常需要编写从 stdin 读取数据并打印到 stdout 的代码，如果候选人不熟悉 API，这可能会让他们犯错。

#### ◇3. 家庭作业

频率：罕见

关于提出算法问题是否是评估个人能力的好方法存在很多争论，因为它们并不是日常工作所需的最相关的技能。带回家作业是一种旨在解决算法面试缺点的形式，让候选人参与更大的项目，让他们展示软件设计技能。

然而，这种面试形式会占用候选人和公司更多的时间，因此在候选人数量较多的大公司中并不常见。这种格式在初创公司和小公司中更为常见。示例

* 构建航班列表应用
* 构建看板应用
* 构建贪吃蛇游戏

#### ◇4. 电话面试

频率：常见

电话面试是最常见的形式，每个候选人在面试时都会至少面对一次。您将被要求通过电话或 VoIP（BlueJeans/Skype/Google Hangout）与面试官交谈。将向您提出一个问题，您将使用在线协作编辑器（CoderPad/CodePen/Google Docs）来解决该问题。

即使编辑器支持执行，您通常也不允许执行代码。因此，不要依赖它来验证解决方案的正确性。根据您申请的角色，格式会略有不同。许多公司喜欢使用[CoderPad](https://coderpad.io/)进行协作代码编辑。 CoderPad 支持程序的运行，因此可能会要求您修复代码以使其可以运行。对于前端面试，许多公司喜欢使用[CodePen](https://codepen.io/) ，值得您花时间熟悉这种基于 Web 的编码环境的用户界面。

在电话面试之前查看[编码面试的最佳实践](../bian-ma-mian-shi-zhun-bei/shi-qian-shi-zhong-he-shi-hou-de-zui-jia-shi-jian.md)以及该做和不该做的事情。

#### ◇5. 现场

频率：几乎总是

如果您已达到此阶段，那么恭喜您！这通常是做出要约决定之前的最后阶段。进入现场阶段的候选人将需要在办公室进行现场面试。如果您是海外候选人，公司甚至可能会安排飞机带您入境并支付您的住宿费用！

现场阶段通常由多轮组成（编码、系统设计、行为），预计持续几个小时。由于您在现场，面试官可能会要求您进行白板练习，通常是解决算法问题或系统设计问题。您也可能必须携带自己的笔记本电脑并现场处理项目/解决编码问题。

对于小型（非上市）公司的现场面试，大多数公司都会允许（并且更喜欢）您使用自己的笔记本电脑。因此，提前准备好开发环境非常重要。

如果公司提供午餐，您还可以与员工共进午餐，在那里您可以了解有关公司文化的更多信息。

### ★选择一种编程语言 <a href="#pick-a-programming-language" id="pick-a-programming-language"></a>

完成简历后，软件工程面试之旅的下一步很简单，不会花很长时间 - 决定一种编程语言。除非您正在面试移动或前端等具有特定领域语言的专家职位，否则您应该可以自由地使用您想要的任何语言进行算法编码面试。

大多数时候，您心中已经有了一种 - 选择您最常用且最舒服的一种。用于编码面试的最常见编程语言是 Python、Java、C++ 和 JavaScript。我不建议仅仅为了编码面试而学习一门全新的语言，因为需要一段时间（至少平均几周）才能足够熟练地掌握一门语言，以便在面试环境中轻松地使用它，而面试环境已经给它带来了足够的压力。自己的。我个人选择的编程语言是 Python，因为它非常简洁并且标准库提供了函数/数据结构。

阅读有关用于编码面试的编程语言的更多信息：[选择编程语言](../bian-ma-mian-shi-zhun-bei/xuan-ze-bian-cheng-yu-yan.md)

### ★编码面试的学习和练习

下一步也是最重要的一步是练习用您选择的编程语言解决算法问题。虽然破解编码面试是一个很好的资源，但我更喜欢通过实际解决问题来学习。

有许多平台可以用于此目的 - 例如 LeetCode、HackerRank 和 CodeForces。从我个人的经验来看，LeetCode 问题最适合面试准备，而 HackerRank 和 CodeForces 更适合竞争性编程。

然而，LeetCode 有数以千计的问题，知道从哪里开始或如何构建你的练习可能会令人畏惧。我在这里提供了推荐的准备计划和结构化资源：

#### ◇编码面试学习计划

建议为编码面试准备留出 3 个月的时间（每周 11 小时，即每天 2-3 小时），以便进行更全面的准备。我[在这里分享了我的 3 个月学习计划](../bian-ma-mian-shi-zhun-bei/xue-xi-shi-jian-ji-hua.md)，其中提供了一份编码面试主题列表，其中包含资源和练习问题，您每周应该按优先顺序完成这些问题。我还将很快添加推荐的 1 个月和 1 周学习计划的内容。

如果您的准备时间少于 3 个月，您可以使用[Grind 75 工具](https://www.techinterviewhandbook.org/grind75)（由我构建）生成自己的学习计划，该工具会根据您剩余的时间生成编码面试的推荐学习计划。其背后的算法包括按优先级对问题进行排序，以及所涵盖主题的广度和深度之间的平衡。

#### ◇实践中使用的资源

市场上有很多资源在争夺你的注意力，很多资源只是在争夺你的钱，但并没有提供任何价值。如果我必须优先考虑 - 这些是我会同时使用的顶级编码面试准备资源：

1. [AlgoMonster 算法怪兽](https://shareasale.com/r.cfm?b=1873647\&u=3114753\&m=114505\&urllink=\&afftrack=)
2. [Grokking the Coding Interview: Patterns for Coding Questions\
   摸索编码面试：编码问题的模式](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-coding-interview)
3. 我的（免费）编码面试最佳实践指南
4. 我的（免费）编码面试技巧指南
5. 我的（免费）算法学习指南

[**AlgoMonster**](https://shareasale.com/r.cfm?b=1873647\&u=3114753\&m=114505\&urllink=\&afftrack=)

除了通过练习和易于理解的指南帮助您掌握重要的编程面试数据结构和算法问题外，AlgoMonster 还具有[综合常见面试问题模式](https://algo.monster/problems/stats)的额外优势，您可以应用这些模式来解决您以前从未遇到过的任何其他问题。由 Google 工程师制作，与 LeetCode 磨练的非结构化性质相比，这绝对是一个优质的平台。数据结构和算法问题涵盖所有常见语言 - Python、Java、C#、JavaScript、C++、Golang 等。[**立即加入即可享受 70% 折扣 →**](https://shareasale.com/r.cfm?b=1873647\&u=3114753\&m=114505\&urllink=\&afftrack=)

[**Grokking the Coding Interview: Patterns for Coding Questions**](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-coding-interview)

Design Gurus 的这门课程扩展了推荐练习问题的问题，但从问题模式的角度进行练习，这是我也同意的学习方法，并且我个人也曾用它来更好地进行面试编码。该课程允许您练习 Java、Python、C++、JavaScript 中的选定问题，并提供这些语言的示例解决方案以及分步可视化。**学习并理解模式，而不是记住答案！**[**立即获得终身访问权限 →**](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-coding-interview)

**我的（免费）编码面试最佳实践指南**

如果您阅读过顶级科技公司使用的[编码面试评估标准](../bian-ma-mian-shi-zhun-bei/bian-ma-mian-shi-ping-fen-biao-zhun.md)，您可能会对评估项目的数量以及如何一致地展示招聘行为感到不知所措。

本[编码面试最佳实践指南](../bian-ma-mian-shi-zhun-bei/shi-qian-shi-zhong-he-shi-hou-de-zui-jia-shi-jian.md)综合了关于编码面试之前、期间和之后应该做什么的可行建议，以展示招聘信号。

我建议在练习编写面试问题时内化并使用该指南作为伴奏 - 以确保您从一开始就培养有关面试的良好习惯和肌肉记忆。

**我的（免费）编码面试技巧指南**

是否有一种结构化方法可以增加您找到编码面试问题的良好解决方案的机会？如何优化方法的时间和空间复杂度？我的编码面试技巧指南教你一些处理以前从未遇到过的问题的技巧 - 例如问题可视化、手动解决、将问题分解为子问题等。

**我的（免费）算法学习指南**

我不确定这些是否有资格作为深入指南 - 它们更像是一页纸的“学习备忘单”，其中包含**最佳学习资源、最佳 LeetCode 练习问题和需要记住的事情**。然而，他们确保您涵盖所有最重要的内容，尤其是当您没有时间时。因为这些也是帮助我获得顶级技术报价的笔记 - 它们绝对有效。

有关编码面试准备的更多提示，请参阅此处我的[完整编码面试准备指南](broken-reference)。

#### ◇尝试模拟编码面试（与 Google 和 Facebook 工程师）

在面试官面前编码可能是一种令人伤脑筋的经历，尤其是如果您以前从未这样做过 - 这就是为什么获得实践经验如此重要的原因。

[Interviewing.io](https://iio.sh/r/DMCa)是目前市场上最好的模拟技术面试资源。它允许您预约与真正的 Google 和 Facebook 工程师进行模拟编程面试，尽管是匿名的。您甚至可以预订特定职位的面试，例如移动、前端、工程管理。更好的是 - 如果您想更轻松地过渡到现实世界的编码面试 - 您可以查看录制的采访并了解电话采访是什么样的。

此外，如果你在模拟面试中表现出色，你将能够解锁“职位页面”，让你可以直接预约 Uber、Lyft、Quora、Asana 等顶级公司的面试。我作为面试官和受访者都使用过[Interviewing.io](https://iio.sh/r/DMCa) ，并且发现这种体验非常好。

### ★准备系统设计面试

如果您是中高级候选人，您可能会在技术面试中遇到系统设计问题。 LeetCode 没有充分涵盖这些内容，而且好的资源仍然更难获得。

系统设计面试的目的是评估候选人设计涉及多个组件的真实软件系统的技能。

#### ◇利用最好的系统设计面试准备资源

一些最好的系统设计面试准备资源包括：

1. [ByteByteGo](https://bytebytego.com/?fpr=techinterviewhandbook) - 这是由 Alex Xu 开设的新系统设计课程，Alex Xu 是《系统设计访谈》书籍的作者，该书籍是亚马逊上的畅销书。课程涵盖系统设计基础知识，然后深入探讨10多个著名常见产品的设计（例如[设计YouTube](https://bytebytego.com/courses/system-design-interview/design-youtube) 、Facebook Newsfeed等）和多个大数据和存储系统（例如[设计聊天系统](https://bytebytego.com/courses/system-design-interview/design-a-chat-system)）。每次深入探讨时，都会解释概念并使用全面的图表，这使得任何资历级别的人都非常容易理解。
2. [Design Gurus 的“Grokking the System Design Interview”](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-system-design-interview) ——这可能是互联网上最著名的系统设计面试课程，它与大多数其他课程的不同之处在于它是纯粹基于文本的，这对于那些更喜欢阅读而不是观看视频（比如我自己！）。它包含流行系统设计问题的存储库以及系统设计基础知识的术语表。我亲自完成了这门课程，并推荐了许多其他人使用它。强烈推荐！
3. [Exponent 的“系统设计面试课程”](https://www.tryexponent.com/courses/system-design-interview?ref=techinterviewhandbook) - 本课程涵盖系统设计基础知识，并拥有一个庞大的流行系统设计问题数据库和模拟面试视频。有些问题有文本答案、数据库模式和 API 供参考（我觉得很有帮助）。虽然仅系统设计面试内容的订阅可能有点贵，但他们还提供[数据结构](https://www.tryexponent.com/courses/swe-practice?ref=techinterviewhandbook)、[算法](https://www.tryexponent.com/courses/algorithms?ref=techinterviewhandbook)和[行为面试](https://www.tryexponent.com/courses/behavioral?ref=techinterviewhandbook)的优质技术内容。涵盖技术面试准备各个方面的一站式平台的便利性非常诱人。
4. [设计大师的“Grokking the Advanced System Design Interview”](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-advanced-system-design-interview) - 我没有尝试过，但它是由创建“Grokking the System Design Interview”的同一个人完成的，所以应该不错！在我看来，除非您非常资深或正在寻求专家职位，否则您可能不需要这个。

[在此处查看其他系统设计准备指南和资源。](../xi-tong-she-ji-mian-shi-zhun-bei/xi-tong-she-ji-zhun-bei-zhi-nan.md)

### ★准备行为面试

每家顶级科技公司都会对软件工程师进行至少一轮行为面试。通常，软件工程师的行为面试包括：

* 分享简历上以前经历的细节
* 提供过去的情况和行为的例子，展示某些行为属性（例如冲突管理技能、数据驱动）
* 分享抱负和职业规划

虽然这些面试看起来很“轻松”或没有结构，但实际上有一种结构化的方式来准备行为面试：

#### ◇1. 了解回答这些问题的 STAR 格式

**STAR**格式可帮助您整理行为问题的答案。这最适用于需要您讲述过去经历或行为的问题。

* **Situation** 情况：分享导致该任务的情况的详细信息
* **task** 任务：解释你需要实现的目标或必须解决的问题；重点关注
  * 范围
  * 严重程度
  * 所需的具体基准/结果
* **action** 行动：解释你为实现目标做了什么，描述你有哪些选择以及你是如何做出决定的
* **result** 结果：描述你的行动结果以及你学到了什么

阅读更多：[回答行为问题的 STAR 格式](https://en.wikipedia.org/wiki/Situation,\_task,\_action,\_result)

#### ◇2. 练习软件工程师最常见的行为问题

请参阅软件工程师[最常见的 30 个行为问题](../xing-wei-mian-shi-zhun-bei/chang-jian-de-xing-wei-wen-ti-lian-xi.md)

有关行为面试准备的更多技巧，请参阅此处的[完整行为面试准备指南](broken-reference)。

### ★协商软件工程师的薪酬待遇 <a href="#negotiating-the-software-engineer-offer-package" id="negotiating-the-software-engineer-offer-package"></a>

最后，面试前你绝对需要准备的最后一件事是软件工程师的薪资谈判。在面试过程中的任何时候，都可能出现关于薪资的谈话。我们还提供有关[谈判策略](../xin-zi-he-bao-jia-tan-pan-zhun-bei/wan-zheng-de-xin-zi-tan-pan-zhi-nan.md)和[软件工程师薪酬](../xin-zi-he-bao-jia-tan-pan-zhun-bei/liao-jie-xin-zi.md)的深入指南。

这就是我要说的全部内容了——要了解软件工程师面试准备过程的每个步骤的更多详细信息，请通过侧边栏或导航到下一页深入了解我的手册中的每个主题！
