---
title: "如何想Idea？ - 飞书云文档"
source: "https://dy8q0bnq8y.feishu.cn/wiki/MxYVwN0lEiv5HUkLEJccRJI3nTd"
author:
published:
created: 2026-11-12
description:
tags:
  - "科研"
---
💡

想Idea主要分成两步：选择一个好的研究问题，寻求问题的解决方案。

Problem-driven vs Method-driven

一般的研究过程可以分为Problem-driven Research 和 Method-drvien Research

简单来说，

•

Problem-driven research：找到一个重要的问题或者目标，想办法把它做好，比如：

◦

大模型在某个任务上性能不好，如何把性能提上去？你可以先确定1-2个benchmark，再尝试探索各种相关的技术，目标就是把任务做work。

◦

也可以尝试去构建benchmark，把一个问题定义清楚，比如，游戏Agent方向，假设我们希望探究LLM在xx任务上的性能，但是现在还没有一个benchmark能支持类似的评估，你就可以去定义一个新的benchmark

◦

或者在领域通用的benchmark上，对已有的技术方案进行问题分析，找到其中存在的关键挑战和问题，比如，GRPO的效率问题、信用分配问题等等，然后去尝试改进和优化。

•

Method-driven research：拿着锤子找钉子，基于已有的技术方案，去不断解决新的问题。比如，GRPO刚出来的时候，拿来做多模态推理、Agentic RL；Skill火的时候，去解决各种数学、医疗、司法垂域问题；

当然，这两种方式很多时候都是要融合的，大部分情况下我们更偏好Problem或者说Goal-driven research，在这个过程中，去对method进行适配和优化。

如何找到研究问题？

1.

批判性论文阅读

参考 [📑如何读论文？](https://dy8q0bnq8y.feishu.cn/wiki/Ow8fw2HtEiixDgkWlkbckdvHnef) 中提到的，在阅读论文的过程中，要尝试去“鸡蛋里面挑骨头”，多去思考论文存在的不足和问题，从而提出新的问题。把“读文献”和“提问题”绑在一起,而不是分成两个阶段，要主动思考“如果这个论文换个数据/换个假设会怎样”。这个习惯越早养成越好，很多研究生前一两年读了大量文献却提不出问题，就是因为读的时候只在“理解”，没有在“批判性质疑”。

2.

从失败中寻找机会

要思考当前的主流方案有哪些failure case，主动寻找和复现failure case，深入分析为什么会出现failure case，探究其背后的原因，尝试提出解决方案

1

评论（1）

跳转至首条评论

用户345810月16日 09:20 （编辑过）

重点：批判性阅读，边读边提问题

0 字

- 帮助中心

- 快捷键