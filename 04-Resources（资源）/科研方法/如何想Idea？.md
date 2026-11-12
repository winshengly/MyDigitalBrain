---
title: 如何想Idea？
source: https://dy8q0bnq8y.feishu.cn/wiki/MxYVwN0lEiv5HUkLEJccRJI3nTd
author:
published:
created: 2026-11-12
description: 想 Idea 的两步：选择好的研究问题，并寻找问题的解决方案；包括 Problem/Method-driven 与找问题的具体方法。
tags:
  - 科研
  - 科研方法
  - 选题
---

# 如何想Idea？

> [!tip] 核心
> 想 Idea 主要分成两步：选择一个好的研究问题，寻求问题的解决方案。

## Problem-driven vs Method-driven

一般的研究过程可以分为 Problem-driven Research 和 Method-driven Research。

**Problem-driven research**：找到一个重要的问题或者目标，想办法把它做好。例如：

- 大模型在某个任务上性能不好，如何把性能提上去？可以先确定 1–2 个 benchmark，再尝试探索各种相关技术，目标就是把任务做 work；
- 也可以尝试构建 benchmark，把一个问题定义清楚。例如游戏 Agent 方向，假设我们希望探究 LLM 在某个任务上的性能，但目前还没有 benchmark 能支持类似的评估，就可以定义一个新的 benchmark；
- 或者在领域通用的 benchmark 上，对已有技术方案进行问题分析，找到其中存在的关键挑战和问题，比如 GRPO 的效率问题、信用分配问题等，然后尝试改进和优化。

**Method-driven research**：拿着锤子找钉子，基于已有的技术方案，不断解决新的问题。比如 GRPO 刚出来的时候，拿来做多模态推理、Agentic RL；Skill 火的时候，去解决各种数学、医疗、司法垂域问题。

当然，这两种方式很多时候都要融合。大部分情况下我们更偏好 Problem/Goal-driven research，在这个过程中对 method 进行适配和优化。

## 如何找到研究问题？

### 1. 批判性论文阅读

参考 [[如何读论文？]] 中提到的，在阅读论文的过程中尝试“鸡蛋里面挑骨头”，多思考论文存在的不足和问题，从而提出新的问题。

把“读文献”和“提问题”绑在一起，而不是分成两个阶段。要主动思考“如果这篇论文换个数据/换个假设会怎样”。这个习惯越早养成越好——很多研究生前一两年读了大量文献却提不出问题，就是因为读的时候只在“理解”，没有在“批判性质疑”。

### 2. 从失败中寻找机会

思考当前的主流方案有哪些 failure case，主动寻找和复现 failure case，深入分析为什么会出现 failure case，探究其背后的原因，尝试提出解决方案。

> [!note] 飞书原文批注
> 重点：批判性阅读，边读边提问题。
