# 用户故事(User Story)

- `共享文档不代表达成共识，文档是用来备忘的，就像旅行过程中的照片`
- 停止写出完美文档的执念
- 使用用户故事的目的就是达成共识，之所以叫故事，因为他是要讲的而不是要写的
- 好的故事讨论的是为谁做和为什么做，而不仅仅是做什么
- 如果在向别人介绍一个想法而对方说 ’好巧啊，我们的做法也和这类似‘，就说明着不叫发明，而是一种模式
- 验证产品要解决的问题是否真的存在
- 最佳的解决方案来自于需要解决问题的人和有能力解决这些问题的人彼此协作
- 如果团队没有聚在一起对用户故事进行充分的讨论，就说明使用用户故事的方式不对
- 尝试让你的工作关系更像是一个良好的医患关系，而不是服务员-用餐者的关系

> 在软件开发和产品管理中，一个用户故事是一个非正式的，自然语言描述的一个或多个软件系统功能 - 维基百科

> 所谓用户故事：描述了对用户、系统或软件购买者有价值的功能。 - Mike Cohn

总之，用户故事在软件开发过程中被作为描述需求的一种表达形式，并着重描述角色（谁要用这个功能）、功能（需要完成什么样子的功能）和价值（为什么需要这个功能，这个功能带来什么样的价值）。

## 3C原则

> 因为用户故事的描述信息写在卡片上，Ron Jeffries在2001年用3个C来描述它：

*Card(卡⽚)*：用户故事被写在一个小的卡片上包含故事描述、规则和验收标准，如下所示:

正面

```
<卡片标题>
As a <Role>
I want to <Activity>
So that <Business Value>
```

背面

```
<验收标准>
Given<什么样的条件下>
When<采取什么行动>
Then<得到什么结果>
```

*Conversation(交谈)*：通过与客户或产品负责人(Product Owner)的交流来确定用户故事的细节，确保各方对用户故事的理解正确。

*Confirmation(确认)*：用验收测试来确认用户故事开发的完整度和正确性。

## 为什么使用用户故事

用户故事是敏捷开发模式中需求敏捷化的重要手段：

- 用户故事容易理解，着重角色（Who）和描述商业价值（Why），而不仅仅是功能的描述（What）。
- 通过看板（Kanban）用户故事有了流动，将研发过程中的需求、开发、测试都串联起来。通过优先级排序和开卡（指用户故事kick off），用户故事将需求与开发连接，通过验收条件（Acceptance Criteria, 简称AC），将需求与测试连接。
- 强调沟通与对话， 易于理解和传播隐性知识。通过故事和客户进行深入交流，避免文字的记录产生歧义性，并提供了迅速的反馈周期，促进了对需求的理解。
- 小的故事适合做计划，利于客户和业务部门理解并判断优先级，适合于迭代开发。
- 鼓励延迟细节，支持变更。可以快速写出独立的用户故事，对于优先级低的可以使用史诗（Epic）代替。

## INVEST原则

为了编写优秀的用户故事，我们需要关注下面六个特征：

- *独立的(Independent)*：一个用户故事尽可能独立于其他用户故事，并确保每个单独的用户故事都有其独立的业务价值，避免用户故事间的相互依赖导致排优先级变得困难。
- *可讨论的(Negotiable)*：用户故事是可以讨论的，用户故事不是合同，在保证价值的情况下，细节在与客户讨论中产生。
- *有价值的(Valuable)*：每个用户故事必须对客户或用户具有价值，避免那些只对开发团队有价值的用户故事。
- *可估计的(Estimable)*：可以对用户故事进⾏估计，以确定其优先级、工作量，并安排迭代计划。导致用户故事不可估计的原因如：缺少领域知识、缺少技术知识，故事太大了等。
- *小的(Small)*：大小刚刚好，确保在一个迭代（Sprint）中能够完成。
- *可测试的(Testable)*：用户故事必须是可测试的，测试通过可以确认用户故事被开发人员正确地实现了。

## 好的用户故事

一个好的用户故事包括：

- *角色*：谁要使用这个功能，了解客户或用户使用我们软件的目的。并尽量只为单一用户编写，这样用户故事的可读性通常是最强的。
- *活动*：需要完成什么样的功能。
- *商业价值*：为什么需要这个功能，这个功能带来什么样的价值。一个好的用户故事意味着完成后，客户或用户可以达成一个明确的、有意义的目标。
- *验收标准*：用来描述用户故事达到必须完成的若干个条件，包括正常及异常条件。通常使用“Given<在什么样条件下>，When<采取了什么行动>，Then<得到什么结果>”格式，这样的写法和测试用例类似，可以使开发更好地理解细节，同时也更方便产品负责人进行验收。

As a `role`, I want to `action`, (so that `benefit`).

- `role` -> Who
- `action` -> What
- `benefit` -> Why

--------------------------------------------------------

## 参考

- [敏捷微知识（三）：关于用户故事（User Story）](https://zhuanlan.zhihu.com/p/480197192)
- [用户故事 User stories](https://zhuanlan.zhihu.com/p/105986421)
