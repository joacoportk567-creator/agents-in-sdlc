---
slug: zh-cn/real-world-development/cloud
title: "GitHub Copilot 云代理"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[GitHub Copilot 云代理](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)可在云端异步工作。你可以在 GitHub 上分配任务，云代理会在后台接手工作，探索仓库、进行更改并创建 pull request，让你可以继续处理其他事务。

在这些练习中，你将添加云代理要遵循的自定义说明，然后分配 GitHub issue 让它实现任务。你将审查并使用自定义代理来调整其工作方式，通过代理仪表板监控并引导会话，最后审查它创建的 pull request 并迭代改进结果。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 创建仓库和 codespace |
| [1. 自定义说明][ex1] | 上下文 | 添加云代理要遵循的自定义说明 |
| [2. 云代理][ex2] | 异步代理 | 将 issue 分配给 Copilot 云代理 |
| [3. 自定义代理][ex3] | 专用代理 | 审查并使用自定义代理 |
| [4. 管理代理][ex4] | 监控 | 监控并引导代理会话 |
| [5. 迭代改进][ex5] | 审查 | 审查 pull request、迭代改进 Copilot 的工作并选择后续步骤 |

## 先决条件

参加本工作坊之前，请确保你已具备以下条件：

- [ ] 拥有有效的 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划的 GitHub 帐户
- [ ] 已为帐户或组织启用 Copilot 云代理

> [!TIP]
> 没有付费计划？经过验证的学生可通过 [GitHub Education][callout-student-plan-education] 免费使用 GitHub Copilot。**Copilot Student** 计划包含本工作坊使用的代理、MCP、代码审查和 Copilot CLI 功能，因此可以完成所有环境的练习。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> **Copilot Student、Pro、Pro+、Business 和 Enterprise** 均可使用云代理，只有 Copilot Free 除外。对于 Copilot Business 或 Enterprise，管理员必须为组织启用此功能。

> [!NOTE]
> 本练习环境不涉及 MCP。若要探索如何将 MCP 服务器与 Copilot 配合使用，请参阅 [CLI 环境](../cli/)或 [VS Code 环境](../vscode/)。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
