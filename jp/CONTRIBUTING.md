# 貢献方法

## 概要

プルリクエストを送る場合、以下のガイドラインを満たしているか確認してください。

* 新しいコード例の追加や既存コード例の改善は歓迎されます。
* スペルや文法を確認してください。

## コード例のバージョンに関する注意事項

全てのコード例には、下記のようなヘッダーを含める必要があります。

```markdown
---
version: 3.5.1
example_title: JSON操作
---
```

次のルールに従い `version` 属性の変更を行います。

* メジャー  ：コンテンツ全体の作成（もしくは作成し直し）。新しいコンテンツには翻訳が必要です。
* マイナー：一部のコンテンツや文章などの追加、削除。
* パッチ： スペルミスやタイプミス。おそらく翻訳を必要としないもの。

[SemVer.org](https://semver.org) のパターンにしたがいます。 これは、翻訳を必要とする新しいコンテンツを決定し、翻訳者に知らせる際に使用するため重要となります。

## 新しいコード例の追加

新しいコード例を追加するには、`./examples` の適切なディレクトリの配下に、新しいフォルダとファイル、もしくはコード例に応じたファイルを作成します。どのようなコード例を作成する予定かは、`.plan` ファイルを確認してください。保留されているコード例があれば、自由に作業を行ってください。あなたが変更した箇所を読んでレビューをしたり、共にコーディングを行いマージされるのを楽しみにしています。

ご協力に感謝いたします！

## スタートガイド

### 1. リポジトリをフォークしクローンする

[このリポジトリ](https://github.com/v-community/v_by_example/fork) をフォークし、フォークからクローンを作成します。フォークが何なのか、どのように使うのか分からない方は、[こちら](https://help.github.com/articles/fork-a-repo/)がとても参考になります。

### 2.作業を行いプッシュする

作業を行う準備は整いました。作業が完了したら、変更内容を自身のフォークにプッシュし[プルリクエスト](https://help.github.com/articles/using-pull-requests/)を送りましょう。

## ライセンス

このコードは、MITライセンスの下で自由に使用できます。