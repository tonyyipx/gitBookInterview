---
description: 软件工程师的系统设计面试指南
---

# 系统设计准备指南

系统设计面试的目的是评估应聘者在设计涉及多个组件的真实软件系统方面的技能。系统设计问题通常会提供给更资深的应聘者（具有几年经验）。实习生通常不会被问到系统设计问题，因为很难指望实习生拥有足够且相关的行业经验来很好地回答这类问题。

### 系统设计面试 <a href="#types-of-system-design-interviews" id="types-of-system-design-interviews"></a>

系统设计问题可以采用不同的形式：

* **后端/分布式系统设计**：考生需要设计跨多个服务器或数据中心运行的系统。主题包括后端架构、数据库模式设计、数据复制、容错、消息队列、一致性模型等。
* **API 系统设计**：设计大型系统内的 API，可能是 HTTP API（例如 REST），或者软件组件内的方法。
* **面向对象设计**：面向对象设计面试侧重于设计类、对象及其关系。应聘者经常被要求创建类图、定义接口并讨论设计模式。
* **前端系统设计**：设计复杂客户端应用程序或 UI 组件的架构。重点在于客户端内部发生的事情以及客户端与服务器之间的 API 设计。

作为软件工程师，您遇到的最常见的系统设计类型是后端/分布式系统设计类型。一些常见的后端系统设计面试问题包括：

* 设计一个 URL 缩短器（例如 Bitly）
* 设计社交媒体网站（例如 Twitter）
* 设计一个视频观看网站（例如 YouTube）
* 设计聊天服务（例如 Telegram、Slack、Discord）
* 设计文件共享服务（例如 Google Drive、Dropbox）
* 设计拼车服务（例如 Uber、Lyft）
* 设计照片共享服务（例如 Flickr、Pinterest）
* 设计一个电子商务网站（例如亚马逊、eBay）
* 设计一个求职门户网站（例如 LinkedIn、Indeed）
* 设计一个网络爬虫（例如 Google）

{% hint style="info" %}
信息

系统设计内容仍在进行中，但以下一些资源可以暂时帮助您。
{% endhint %}

### 优质资源 <a href="#quality-resources" id="quality-resources"></a>

* [GreatFrontEnd 的“前端系统设计指南”](https://www.greatfrontend.com/system-design?fpr=yangshun)：一本由我编写的免费系统设计指南，专注于前端的系统设计，例如如何设计 Facebook 的新闻提要、自动完成组件、图像轮播等。
* [快速系统设计](https://www.hellointerview.com/learn/system-design)：由前 Meta 和 Amazon 工程师创建的免费课程，涵盖交付基础知识、高级概念和核心技术。经过实践检验的“常见问题”将引导您了解实际问题中的各种设计决策以及如何解决这些问题。
* [系统设计简讯](https://newsletter.systemdesign.one/)：每周系统设计简讯。还可免费获得强大的系统设计模板。
* [ByteByteGo](https://bytebytego.com/?fpr=techinterviewhandbook)：这是由亚马逊畅销书《系统设计面试》作者 Alex Xu 开设的一门新系统设计课程。课程涵盖系统设计基础知识，然后深入探讨 10 多种著名常见产品的设计（例如[设计 YouTube](https://bytebytego.com/courses/system-design-interview/design-youtube?fpr=techinterviewhandbook)、Facebook 新闻源等）以及多种大数据和存储系统（例如[设计聊天系统](https://bytebytego.com/courses/system-design-interview/design-a-chat-system?fpr=techinterviewhandbook)）。每次深入探讨时，都会解释概念并使用全面的图表，无论资历水平如何，都非常容易理解。
* [Design Gurus 的“Grokking the System Design Interview”](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-system-design-interview)：这可能是互联网上最著名的系统设计面试课程，与其他大多数课程不同的是，它是纯文本的，非常适合喜欢阅读而不是观看视频的人（比如我自己！）。它包含一个流行的系统设计问题库以及系统设计基础知识词汇表。我个人已经完成了这门课程，并强烈推荐其他人使用它。
* [设计大师的《Grokking the Advanced System Design Interview》](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fcourse%3Fcourseid%3Dgrokking-the-advanced-system-design-interview)：我还没有尝试过这本书，但它是由《Grokking the System Design Interview》的创作者编写的，所以应该不错！在我看来，除非你非常资深或正在担任专家职位，否则你可能不需要这本书。
* [Design Gurus 的“最佳系统设计”套餐](https://designgurus.org/link/kJSIoU?url=https%3A%2F%2Fdesigngurus.org%2Fbundles%3Fbundle\_id%3Dbuy-both-system-design-courses)：此套餐允许您以折扣价购买 Design Gurus 的两门系统设计面试课程。最重要的是，它是终身的，而不是基于订阅的。
* [Exponent 的“系统设计面试课程”](https://www.tryexponent.com/courses/system-design-interview?ref=techinterviewhandbook)：该课程涵盖系统设计基础知识，拥有庞大的热门系统设计问题数据库，并配有模拟面试视频。部分问题有文本答案、数据库模式和 API 供参考（我觉得很有帮助）。虽然仅系统设计面试内容的订阅费用可能有点贵，但他们也为[数据结构](https://www.tryexponent.com/courses/swe-practice?ref=techinterviewhandbook)、[算法](https://www.tryexponent.com/courses/algorithms?ref=techinterviewhandbook)和[行为面试](https://www.tryexponent.com/courses/behavioral?ref=techinterviewhandbook)提供了优质的技术内容。一站式平台涵盖技术面试准备的各个方面，其便利性非常诱人。
* [“Gaurav Sen Youtube - 系统设计播放列表”](https://youtu.be/xpDnVSmNFX0)：Gaurav Sen 是一位受欢迎的 YouTuber，他的系统设计视频获得了广泛认可。他的系统设计播放列表为正在准备技术面试或想要了解更多有关如何设计可扩展系统的软件工程师提供了全面的指南。播放列表由多个视频组成，每个视频涵盖与系统设计相关的不同主题。这些视频的设计方式简化了复杂的主题，使初学者易于理解。

### 免费资源 <a href="#free-resources" id="free-resources"></a>

* [系统设计入门](https://github.com/donnemartin/system-design-primer)：目前最全面的系统设计资源。仅当您有大量空闲时间时才推荐。
* [系统设计访谈](https://github.com/checkcheckzz/system-design-interview)：包含许多有关系统设计的技巧、系统设计相关主题以及著名公司的工程博客的链接。
* [系统设计备忘单](https://gist.github.com/vasanthk/485d1c25737e8e72759f)：内容简洁明了。在系统设计面试之前可以作为很好的复习资料。
* [系统设计路线图](https://roadmap.sh/system-design)：分步指南，其中包含有关学习重要主题的文章和视频的链接。

### 书籍 <a href="#books" id="books"></a>

* [系统设计面试——内部指南，第二版](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)：适合初学者了解系统设计的资源，内容易于阅读和理解。
