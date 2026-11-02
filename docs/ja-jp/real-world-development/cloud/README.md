---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot クラウド エージェント"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[**GitHub Copilot クラウド エージェント**](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、クラウド エージェントがバックグラウンドでリポジトリを調べ、変更を加え、プル リクエストを作成します。その間、別の作業を続けられます。

この演習では、まずクラウド エージェントが従うカスタム指示を追加し、GitHub Issue を割り当てて実装させます。カスタム エージェントを確認して使い、エージェントの進め方を調整します。さらに、エージェント ダッシュボードからセッションを監視して方向を示し、最後にプル リクエストを確認して結果を反復的に改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと Codespace を作成します |
| [1. カスタム指示][ex1] | コンテキスト | クラウド エージェントが従うカスタム指示を追加します |
| [2. クラウド エージェント][ex2] | 非同期エージェント | GitHub Copilot クラウド エージェントに Issue を割り当てます |
| [3. カスタム エージェント][ex3] | 専門エージェント | カスタム エージェントを確認して使います |
| [4. エージェントの管理][ex4] | 監視 | エージェントのセッションを監視して方向を示します |
| [5. 反復][ex5] | レビュー | PR を確認し、Copilot の作業を反復的に改善して、次のステップを選びます |

## 前提条件

このワークショップに参加する前に、次の準備をしてください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかの有効なプランがある GitHub アカウント
- [ ] アカウントまたは組織で GitHub Copilot クラウド エージェントが有効になっていること

> [!TIP]
> 有料プランを利用していない場合でも、認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使うエージェント、MCP、コードレビュー、Copilot CLI の機能が含まれているため、すべての環境の演習を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> クラウド エージェントは **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free 以外のすべてのプランが対象です。Copilot Business または Enterprise では、管理者が組織で有効にする必要があります。

> [!NOTE]
> このワークショップでは MCP を扱いません。Copilot で MCP サーバーを使う方法については、[CLI 版](../cli/)または [VS Code 版](../vscode/)を参照してください。

## はじめに

**[演習 0: 前提条件から始める →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
