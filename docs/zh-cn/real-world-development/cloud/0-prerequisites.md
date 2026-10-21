---
title: "练习 0：先决条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

开始 Copilot 云代理练习之前，请先完成准备工作。你将创建 Tailspin Toys 仓库的个人副本，并启动一个 [codespace][codespaces]，用于编辑说明文件和审查云代理完成的工作。

## 设置实验仓库

要创建包含实验代码的仓库副本，请从[模板仓库][template-repository]创建一个实例。新实例包含实验所需的全部文件，供你在练习中使用。

1. 在新的浏览器窗口中，打开 [Tailspin Toys 模板][tailspin-template]。
2. 在实验仓库页面上选择 **Use this template** 按钮，创建自己的副本。然后选择 **Create a new repository**。

    ![Use this template 按钮](../../../_images/ex0-use-template.png)

3. 如果你正在参加由 GitHub 或 Microsoft 举办的活动，请遵循导师提供的说明。否则，请在你有权使用 GitHub Copilot 的组织中创建新仓库。

    ![输入仓库模板设置](../../../_images/ex0-repository-settings.png)

4. 记下所创建仓库的路径（**organization-or-user-name/repository-name**），稍后会在实验中用到。

## 创建 codespace

接下来，你将使用 codespace 完成实验练习。

[GitHub Codespaces][codespaces] 是一种基于云的开发环境，可让你直接在浏览器中编写、运行和调试代码。它提供功能齐全的 IDE，支持多种编程语言、扩展和工具。

1. 打开刚创建的仓库。
2. 选择绿色的 **Code** 按钮。

    ![选择 Code 按钮](../../../_images/ex0-code-button.png)

3. 选择 **Codespaces** 选项卡，然后选择 **+** 按钮创建新的 Codespace。

    ![创建新的 codespace](../../../_images/ex0-create-codespace.png)

创建 codespace 需要几分钟，不过仍比手动安装所有服务快得多。等待期间，你可以探索 GitHub Copilot 的其他功能，我们接下来会介绍这些功能。

> [!CAUTION]
> 你将在后续练习中返回 codespace。暂时请在浏览器选项卡中保持它打开。

> [!NOTE]
> 本工作坊可在 codespace 或本地[开发容器][dev-containers]中运行。两者都已准备好所需的先决条件，可让你顺利完成练习。如果希望在本地运行，请在 VS Code 中打开克隆的仓库，并在出现提示时选择 **Reopen in Container**。VS Code 将构建与 codespace 相同的开发容器。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## 总结

恭喜你创建了实验仓库的副本，并开始创建 codespace。你将在与 Copilot 云代理协作时使用此 codespace。

## 下一步

添加云代理要遵循的自定义说明。继续学习[练习 1：自定义说明][next-lesson]。

## 资源

- [GitHub Codespaces 概述][codespaces]
- [从模板创建仓库][template-repository]
- [Codespaces 入门][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
