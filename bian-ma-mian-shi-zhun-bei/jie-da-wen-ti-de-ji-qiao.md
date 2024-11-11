---
description: 解决编码面试问题的最佳技巧
---

# 解答问题的技巧

大多数候选人在编程面试中最大的恐惧是：如果我被问题难住了，不知道该怎么做怎么办？幸运的是，有一些结构化的方法可以解决编程面试问题，这将增加你解决问题的机会。从如何找到解决方案或方法，到优化时间和空间复杂性，这里有一些最重要的技巧和最佳实践，可以帮助你解决编程面试问题。

### ★如何找到编码面试问题 <a href="#how-to-find-solutions-to-coding-interview-problems" id="how-to-find-solutions-to-coding-interview-problems"></a>

当面试官问到编程问题时，应聘者应该先问一些澄清问题，并与面试官讨论一些可能的方法。然而，大多数应聘者往往在这一步陷入困境。值得庆幸的是，有方法可以有条理地做到这一点。

请注意，并非所有技术都适用于每个编码面试问题，您也可以在一个问题上使用多种技术！当您在练习中应用这些技术时，您将形成直觉，知道哪种技术对于手头的问题有用。

#### ◇1. 通过画图 <a href="#id-1-visualize-the-problem-by-drawing-it-out" id="id-1-visualize-the-problem-by-drawing-it-out"></a>

有没有想过为什么编程面试传统上是在白板上进行的，而解释编程问题答案的视频往往使用图表？白板可以轻松绘制图表，这有助于解决问题！编码的很大一部分是了解程序的内部状态如何变化，而图表是用于表示内部数据结构状态的超级有用工具。如果您很难理解如何获得解决方案，请想出问题的视觉表示，如有必要，还要提供每一步的内部状态。

如果输入涉及树、图、矩阵、链表，此技术特别有用。

**示例**

如何[按螺旋顺序返回矩阵的所有元素](https://leetcode.com/problems/spiral-matrix/)？绘制矩阵以及迭代器在每个方向上需要采取的步骤将极大地帮助您看到模式。

#### ◇2. 思考如何手动 <a href="#id-2-think-about-how-you-would-solve-the-problem-by-hand" id="id-2-think-about-how-you-would-solve-the-problem-by-hand"></a>

手工解决问题是指不编写任何代码来解决问题，就像非程序员那样。当您尝试理解给您的示例时，这种情况大多数时候已经自然发生。

有些人没有意识到，有时可行的解决方案只是手动方法的代码版本。如果您能针对每个示例制定一套具体的规则，那么您就可以为其编写代码。虽然您可能无法通过这种方式找到最有效的解决方案，但这是一个可以为您带来一些荣誉的开始。

**示例**

如何在不编写任何代码的情况下[验证一棵树是否是有效的二叉搜索树](https://leetcode.com/problems/validate-binary-search-tree/)？首先检查左子树是否仅包含小于根的值，然后检查右子树是否仅包含大于根的值，然后对每个节点重复此操作。这个过程似乎是可行的。现在你只需要把这个过程变成代码。

#### ◇3. 提出更多例子 <a href="#id-3-come-up-with-more-examples" id="id-3-come-up-with-more-examples"></a>

无论你是否遇到困难，想出更多的例子都是很有用的。它可以帮助你加强对问题的理解，防止你过早地跳入编码，帮助你识别可以推广到任何输入的模式，这就是解决方案！最后，在验证解决方案时，可以将多个示例用作测试用例。

#### ◇4. 将问题分解成更小的独立部分 <a href="#id-4-break-the-question-down-into-smaller-independent-parts" id="id-4-break-the-question-down-into-smaller-independent-parts"></a>

如果问题很大，请从高级函数开始，然后将其分解为较小的组成函数，并分别解决每个函数。这可以防止您被一次性完成所有事情的细节所困扰，并保持您的思维结构化。

这样做也可以让面试官清楚地知道你有一种方法，即使你无法完成所有较小功能的编码。

**示例**

[组字谜](https://leetcode.com/problems/group-anagrams/)问题可以分为两部分 - 对字符串进行哈希处理，将字符串分组。每个部分都可以使用独立的实现细节单独解决。您可以从以下代码开始：

```python
def group_anagrams(strings):
  def hash(string):
    # Fill in later
    pass

  def group_strings(strings_hashes):
    # Fill in later
    pass

  strings_hashes = [(string, hash(string)) for string in strings]
  return group_strings(strings_hashes)
```

然后继续填写每个函数的实现。但是，请注意，有时最有效的解决方案需要你打破一些抽象，并在一次输入中执行多个操作。如果面试官要求你根据你抽象的解决方案进行优化，那么这是一条可能的前进道路。

#### ◇5. 应用常见的数据结构和算法来解决问题 <a href="#id-5-apply-common-data-structures-and-algorithms-at-the-problem" id="id-5-apply-common-data-structures-and-algorithms-at-the-problem"></a>

与现实世界中的软件工程不同，在现实世界中，问题通常是开放式的，可能没有明确的解决方案，而编程面试问题往往规模较小，并且旨在在面试期间解决。您还可以预料到，解决问题所需的知识并不离谱，这些知识在大学期间就已经学过了。值得庆幸的是，常见数据结构和算法的数量是有限的，根据我的经验，一种行之有效的黑客方法是尝试遍历所有常见数据结构并将它们应用于问题。

这些是需要记住并尝试的数据结构，按照它们在编码面试问题中出现的频率排序：

* **哈希映射**：有助于提高查找效率。这是面试中最常用的数据结构，你肯定会用到它。
* **图表**：如果数据以实体之间的关联形式呈现给您，您可能能够将问题建模为图表并使用一些常见的图表算法来解决问题。
* **堆栈和队列**：如果您需要解析具有嵌套属性的字符串（例如数学方程式），则几乎肯定需要使用堆栈。
* **堆**：问题涉及根据优先级进行调度/排序。对于查找集合中的最大 K/最小 K/中位数元素也很有用。
* **树/Trie**：您是否需要以节省空间的方式存储字符串，并快速查找字符串（或至少其中的一部分）的存在？

**惯例**

* 排序
* 二分查找：如果输入数组已排序，并且需要比 O(n) 搜索更快，则二分查找很有用
* 滑动窗口
* 两个指针
* 联合查找
* 广度优先搜索/深度优先搜索
* 从后面穿过
* 拓扑排序

将来，我们将添加有关如何根据问题更好地识别最相关的数据结构和例程的提示。

### ★如何优化你的方法或解决方案 <a href="#how-to-optimize-your-approach-or-solution" id="how-to-optimize-your-approach-or-solution"></a>

在你想出了编程面试问题的初步解决方案后，面试官很可能会问你“我们能做得更好吗？”来提示你优化解决方案。以下技巧可帮助你进一步优化解决方案的时间和空间复杂度：

#### ◇如何优化时间复杂度 <a href="#how-to-optimize-time-complexity" id="how-to-optimize-time-complexity"></a>

**1. 确定解决方案**

解决方案的最佳理论时间复杂度 (BTTC) 是您知道无法超越的时间复杂度。

一些简化的例子：

* 查找数组中数字之和的 BTTC 为 O(n)，因为你必须至少查看数组中的每个值一次
* [查找字谜组数的](https://leetcode.com/problems/group-anagrams/)BTTC为 O(nk)，其中 n 是单词数，k 是单词中的最大字母数，因为您必须至少查看每个单词一次，并且至少查看每个单词中的每个字符一次
* 查找矩阵中岛的数量的 BTTC 为 O(nm)，其中 n 是行数，m 是列数，因为你必须至少查看矩阵中的每个单元格一次

为什么了解 BTTC 很重要？这样你就不会陷入寻找比 BTTC 更快的解决方案的困境。最快的实际解决方案只能与 BTTC 一样快，而不会比 BTTC 更快。BTTC 在实践中不一定能实现（因此是理论上的），它只是意味着你永远找不到比它更快的实际解决方案。如果你的初始解决方案比 BTTC 慢，那么可能有机会改进，以便你能够达到 BTTC（但并非总是如此）。向面试官提及 BTTC 不会有什么坏处，这将被视为一个积极的信号，同时也提醒自己不要试图想出比 BTTC 更快的东西。

有些人可能认为 BTTC 只是数据结构中元素的总数，因为您需要遍历每个元素一次。这并不**总是正确的**。最著名的例子是在已排序的数字数组中查找数字。 sorted 属性会改变很多事情：

* 查找数字将是 O(log(n))，因为您可以使用二进制搜索。
* 查找最大数字将是 O(1)，因为它是数组中的最后一个值。

这就是为什么关注问题给出的每一个细节很重要。小心不要因为缺乏对问题细节的关注而确定错误的 BTTC！

确定正确的 BTTC 后，您现在知道最佳解决方案的时间复杂度介于初始解决方案和 BTTC 之间，并且可以朝着它努力。如果您的解决方案已经具有 BTTC，并且面试官要求您进一步优化，他们通常会寻找两件事：

* 工作量更小。您的解决方案可能是 O(n)，但需要对数组进行两次传递，而面试官正在寻找使用一次传递的解决方案。
* 使用更少的空间。请参阅下面有关优化空间复杂性的部分。

**2. 识别重叠和重复计算**

简单/蛮力解决方案通常会一遍又一遍地执行相同的操作。当代码执行之前已经执行过的昂贵操作时，请花点时间回顾一下，考虑是否可以重用以前计算的结果。动态规划 (DP) 是最明显的可以完全利用过去计算的问题类型。非 DP 问题也可以利用这种技术，尽管不那么简单，可能需要预处理步骤。

**示例**

数组[除自身之外的乘积](https://leetcode.com/problems/product-of-array-except-self/)问题是一个很好的例子，它包含重叠/重复的工作。要获取索引的值，您需要将所有其他位置的值相乘。对数组中的每个值执行此操作将花费 O(n 2 ) 时间。但是，请注意：

* `result[n]`：`Product(nums[0] … nums[n-1]) * Product(nums[n + 1] … nums[N - 1])`
* `result[n + 1]`：`Product(nums[0] … nums[n]) * Product(num[n + 2] … nums[N - 1])`

在计算`result[n]`vs时有大量重复工作`result[n + 1]`！这是一个重用之前计算 的机会。事实上，我们可以利用前缀数组帮助我们在 O(n) 时间内以更多空间为代价得出最终解决方案。`result[n]result[n + 1]`

**3.尝试不同的数据结构**

选择数据结构是编程面试的关键。它可以帮助您解决问题，也可以帮助您优化现有的解决方案。有时值得再次进行迭代您了解的数据结构的练习。

查找时间是否会减慢您的算法速度？一般来说，借助哈希表，大多数查找操作应该是 O(1)。如果解决方案中的查找操作是解决方案时间复杂度的瓶颈，通常可以使用哈希表来优化查找。

**示例**

K个[最接近原点的](https://leetcode.com/problems/k-closest-points-to-origin/)问题可以通过计算每个点的距离、对它们进行排序，然后取 K 个最小值，以一种简单的方式解决。由于排序，这需要 O(nlog(n)) 时间。但是，通过使用堆数据结构，时间复杂度可以降低到 O(nlog(k))，因为当堆的大小限制为 K 个元素时，添加/删除堆仅需要 O(log(k)) 时间。更改数据结构对算法的效率产生了很大的影响！

**4. 识别冗余工作**

以下是一些执行冗余工作的代码示例。虽然犯这些错误可能不会改变代码的整体时间复杂度，但您的编码能力也会受到评估，因此编写尽可能高效的代码非常重要。

**无需不必要地**

这些是第二次检查是多余的 Python 示例。

* `if not arr and len(arr) == 0`- 第一次检查已经确保数组为空，因此无需进行第二次检查。
* `x < 5 and x < 10`- 第二次检查是第一次检查的子条件。

**注意检查**

* `if slow() or fast()`- 此检查中有两个操作，持续时间不同。只要其中一个操作的计算结果为`true`，条件的计算结果就会为`true`。大多数计算机按从左到右的顺序执行操作，因此将 放在`fast()`左侧效率更高。
* `if likely() and unlikely()`- 此示例使用与上面类似的参数。如果我们`unlikely()`先执行并且它是`false`，则我们不必执行`likely()`。

**不要不必要地**

如果您必须在函数中多次引用某个属性，并且该属性必须从函数调用中派生，则如果该值在函数的整个生命周期内都不会改变，则将结果缓存为变量。输入数组的长度是最常见的例子。大多数情况下，输入数组的长度不会改变，请在开始时声明一个变量`length = len(array)`并在函数中使用，`length`而不是`len(array)`每次需要时都调用它。

**提前终止**

提前终止。在得到答案后停止，立即返回答案。以下是利用提前终止的一个例子。考虑这个基本问题“确定字符串数组是否包含字符串，无论是否区分大小写”。它的代码如下：

```python
def contains_string(search_term, strings):
  result = False
  for string in strings:
    if string.lower() == search_term.lower():
      result = True
  return result
```

这段代码能用吗？当然能。这段代码是否尽可能高效？不能。我们只需要知道搜索词是否存在于字符串数组中。只要我们知道存在该值，就可以停止迭代。

```python
def contains_string(search_term, strings):
  for string in strings:
    if string.lower() == search_term.lower():
      return True # Stop comparing the rest of the array/list because the result won't change.
  return False
```

大多数人已经知道这一点，并且在面试之外已经这样做了。然而，在紧张的面试环境中，人们往往会忘记最明显的事情。尽早结束循环。

**尽量减少循环**

我们进一步改进上面的例子，来解决“确定一个字符串数组是否包含一个字符串，不管是否区分大小写”这个问题。

```python
def contains_string(search_term, strings):
  for string in strings:
    if string.lower() == search_term.lower():
      return True
  return False
```

`search_term.lower()`请注意，您在 for 循环的每个循环中都调用一次！这是一种浪费，因为`search_term`在函数的整个生命周期中都不会改变。

```python
def contains_string(search_term, strings):
  search_term_lowercase = search_term.lower()
  for string in strings:
    if string.lower() == search_term_lowercase:
      return True
  return False
```

尽量减少循环内的工作，如果没有改变就不要重复已经完成的工作。

**懒惰**

惰性求值是一种求值策略，它会延迟对表达式的求值，直到需要其值为止。让我们使用与上面相同的示例。我们可以从技术上对其进行一些改进：

```python
def contains_string(search_term, strings):
  if len(strings) == 0:
    return False
  # Don't have to change the search term to lower case if there are no strings at all.
  search_term_lowercase = search_term.lower()
  for string in strings:
    if string.lower() == search_term_lowercase:
      return True
  return False
```

这被认为是一种微优化，大多数情况下`strings`不会为空，但我用它来说明一个示例，即如果不需要，您不必进行某些计算。这也适用于初始化代码中需要的对象（通常是哈希表）。如果输入为空，则无需初始化任何变量！

#### ◇如何优化空间复杂度 <a href="#how-to-optimize-space-complexity" id="how-to-optimize-space-complexity"></a>

大多数情况下，时间复杂度比空间复杂度更重要。但是当你已经达到最佳时间复杂度时，面试官可能会要求你优化解决方案所使用的空间（如果它使用了额外的空间）。以下是一些可用于提高代码空间复杂度的技巧。

**1. 就地更改数据/覆盖输入数据**

如果您的解决方案包含创建新数据结构以进行中间处理/缓存的代码，则内存空间会被分配，有时可能会被视为负面。解决此问题的技巧是覆盖原始输入数组中的值，这样您就不会在代码中分配任何新空间。但是，如果您需要在代码的后续部分中使用输入数据，请小心不要以不可逆的方式破坏输入数据。

一种可行的方法（但您不应该在编码面试之外使用）是改变原始数组并将其用作哈希表来存储中间数据。请参阅下面的示例。

请注意，在软件工程中，改变输入数据通常是不受欢迎的，并且会使您的代码更难阅读和维护，因此，就地更改数据大多是您应该在编码面试中做的事情。

**示例**

[荷兰国旗](https://leetcode.com/problems/sort-colors/)问题可以通过创建一个新数组并以排序的方式用相应的值填充它，在 O(n) 时间和 O(n) 空间内轻松解决。作为额外的挑战和空间优化，面试官通常会要求 O(n) 时间和 O(1) 空间解决方案，这涉及对输入数组进行就地排序。

使用原始数组作为哈希表的一个示例是“[第一个缺失正数”](https://leetcode.com/problems/first-missing-positive)问题。在第一个 for 循环之后，数组中的所有值都是正数，您可以通过对数字对应的索引处的值取反来指示数字的存在。要指示 4 存在，请取反`nums[4]`。

**2. 改变数据结构**

又是数据结构！？是的，又是数据结构！数据结构对于编程面试来说非常重要，掌握数据结构将决定你的面试表现。你是否使用了最佳的数据结构来解决问题？

**示例**

给定一个字符串列表，您想知道其中有多少个字符串以某个前缀开头。有什么方法可以高效地存储这些字符串，以便快速计算出答案？[Trie](https://leetcode.com/problems/implement-trie-prefix-tree/)是一种树状数据结构，可以高效地存储字符串，还可以让您快速计算出有多少个字符串以某个前缀开头。

### ★下一步 <a href="#next-steps" id="next-steps"></a>

如果你还没有，我建议你查看我的[免费结构化编码面试指南](../jie-shao/swe-mian-shi-ta-men-shi-shen-me-yi-ji-ru-he-zhun-bei.md)，其中包含分步指导，例如：

* [如何制定有效的编程面试准备计划](xue-xi-shi-jian-ji-hua.md)- 包括根据剩余时间确定要学习的主题和问题的优先级
* [编码面试最佳实践备忘单](shi-qian-shi-zhong-he-shi-hou-de-zui-jia-shi-jian.md)- 包括在编码面试中如何表现以展现录用信号
* [算法速查表](broken-reference)——包括每个数据结构必须牢记的内容[\
  ](https://www.faangtechleads.com/?utm\_source=techinterviewhandbook\&utm\_medium=referral\&utm\_content=in\_doc\&aff=1e80c401fe7e2)
