---
title: "演習 0: 前提条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Copilot クラウド エージェントの演習を始める前に、必要な環境を準備します。Tailspin Toys リポジトリのコピーを作成し、指示ファイルを編集したり、クラウド エージェントの作業をレビューしたりするための [codespace][codespaces] を起動します。

## ラボ用リポジトリを設定する

ラボで作成するコード用に、[テンプレート リポジトリ][template-repository]から自分のインスタンスを作成します。新しいインスタンスにはラボに必要なファイルがすべて含まれ、演習を通して使用します。

1. 新しいブラウザー ウィンドウで、[Tailspin Toys テンプレート][tailspin-template]を開きます。
2. ラボ リポジトリのページで **Use this template** ボタンを選択し、自分用のコピーを作成します。次に **Create a new repository** を選択します。

    ![Use this template ボタン](../../../_images/ex0-use-template.png)

3. GitHub または Microsoft が主催するイベントでワークショップに参加している場合は、メンターの指示に従います。それ以外の場合は、GitHub Copilot を利用できる組織に新しいリポジトリを作成できます。

    ![リポジトリ テンプレートの設定を入力](../../../_images/ex0-repository-settings.png)

4. 作成したリポジトリのパス（**organization-or-user-name/repository-name**）をメモします。ラボの後半で参照します。

## codespace を作成する

次に、ラボの演習を完了するために codespace を使用します。

[GitHub Codespaces][codespaces] はクラウドベースの開発環境です。ブラウザーで直接コードを記述、実行、デバッグできます。複数のプログラミング言語、拡張機能、ツールに対応したフル機能の IDE を利用できます。

1. 作成したリポジトリを開きます。
2. 緑色の **Code** ボタンを選択します。

    ![Code ボタンを選択](../../../_images/ex0-code-button.png)

3. **Codespaces** タブを選択し、**+** ボタンを選択して新しい Codespace を作成します。

    ![新しい codespace を作成](../../../_images/ex0-create-codespace.png)

codespace の作成には数分かかりますが、必要なサービスをすべて手動でインストールするよりもはるかに短時間で済みます。待ち時間には、次に取り上げる GitHub Copilot の機能を確認できます。

> [!CAUTION]
> 後の演習で codespace に戻ります。今はブラウザーのタブで開いたままにしてください。

> [!NOTE]
> このワークショップは codespace またはローカルの [開発コンテナー][dev-containers]で実行できるように構成されています。どちらもスムーズに進めるために必要な前提条件を備えています。ローカルで実行する場合は、クローンしたリポジトリを VS Code で開き、プロンプトが表示されたら **Reopen in Container** を選択してください。codespace と同じ開発コンテナーが VS Code で作成されます。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## まとめ

おめでとうございます。ラボ用リポジトリのコピーを作成し、Copilot クラウド エージェントと作業するときに使う codespace の作成を開始しました。

## 次のステップ

クラウド エージェントが従うカスタム指示を追加します。[演習 1: カスタム指示][next-lesson]に進みます。

## リソース

- [GitHub Codespaces の概要][codespaces]
- [テンプレートからリポジトリを作成する][template-repository]
- [Codespaces の使用を開始する][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
