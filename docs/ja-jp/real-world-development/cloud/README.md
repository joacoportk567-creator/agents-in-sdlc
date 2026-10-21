---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot クラウド エージェント"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[GitHub Copilot クラウド エージェント](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)は、クラウドで非同期に動作します。GitHub で作業を割り当てると、クラウド エージェントはバックグラウンドでリポジトリを調べ、変更を加え、pull request を作成します。その間、ほかの作業を続けられます。

各演習では、クラウド エージェントが従うカスタム指示を追加し、GitHub issue を割り当てて実装を依頼します。カスタム エージェントをレビューして作業方針を調整し、エージェント ダッシュボードからセッションを監視・誘導します。最後に pull request をレビューし、結果を改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと codespace を作成する |
| [1. カスタム指示][ex1] | コンテキスト | クラウド エージェントが従うカスタム指示を追加する |
| [2. クラウド エージェント][ex2] | 非同期エージェント | Copilot クラウド エージェントに issue を割り当てる |
| [3. カスタム エージェント][ex3] | 専門エージェント | カスタム エージェントをレビューして使用する |
| [4. エージェントの管理][ex4] | 監視 | エージェント セッションを監視して誘導する |
| [5. 反復][ex5] | レビュー | PR をレビューし、Copilot の作業を改善して次の手順を決める |

## 前提条件

このワークショップを始める前に、次の準備をしてください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかの有効なプランがある GitHub アカウント
- [ ] アカウントまたは組織で Copilot クラウド エージェントが有効になっていること

> [!TIP]
> 有料プランをお持ちでない場合、認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使うエージェント、MCP、コードレビュー、Copilot CLI の機能が含まれているため、すべての環境を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> クラウド エージェントは **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free を除くすべてのプランが対象です。Copilot Business または Enterprise では、管理者が組織で有効にする必要があります。

> [!NOTE]
> このハーネスでは MCP を扱いません。Copilot で MCP サーバーを使う方法を試すには、[CLI ハーネス](../cli/)または [VS Code ハーネス](../vscode/)を参照してください。

## はじめる

**[演習 0: 前提条件から開始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
