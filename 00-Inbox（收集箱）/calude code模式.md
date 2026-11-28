---
title: calude code模式
source: https://chat.deepseek.com/a/chat/s/60417ae4-00e4-457c-ad14-ea308b81698f
author:
published:
created: 2026-11-26
description: Chat with DeepSeek AI – your intelligent assistant for coding, content creation, file reading, and more. Upload documents, engage in long-context conversations, and get expert help in AI, natural language processing, and beyond. | 深度求索（DeepSeek）助力编程代码开发、创意写作、文件处理等任务，支持文件上传及长文本对话，随时为您提供高效的AI支持。
tags:
  - ClaudeCode
---
### 📊 模式对比与选型一览

| 模式 | 核心行为 | 安全检查 | 自动化程度 | 典型场景 |
| --- | --- | --- | --- | --- |
| **Manual / Default** | 几乎每步都问 | 人工逐次确认 | 低 | 陌生项目、敏感开发[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |
| **Accept Edits** | **编辑自动，命令确认** | 人工审核命令 | 中 | **日常开发**、信任的项目[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |
| **Plan** | **只读，先出方案** | 人工全量审核 | 极低 | 规划重构、探索代码[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |
| **Auto** | AI 分类器自动审批 | **AI 分类器审查** | 高 | 长时任务、批量处理[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |
| **Don't Ask** | **白名单外一律拒绝** | 预配置白名单 | 中高 | CI/CD、受限环境[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |
| **Bypass Permissions** | **全部放行** | **无** | 极高 | **仅限隔离沙箱**、实验环境[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1) |

### 💡 如何选择与切换

一个实用的选型原则是：**日常开发用 `Accept Edits`，敏感/规划场景用 `Default`/`Plan`，长时自动化用 `Auto`，CI 流水线用 `Don't Ask`，`Bypass Permissions` 仅限隔离沙箱**。[\-1](https://cloud.tencent.com.cn/developer/article/2667942?policyId=1004#1)

你可以在会话中通过 **`Shift+Tab`** 快捷键循环切换大部分模式（`Don't Ask` 和 `Bypass Permissions` 通常需要通过启动参数或设置来启用）。