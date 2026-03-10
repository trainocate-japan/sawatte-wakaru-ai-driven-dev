# `.cursor/rules` 形式のファイル構成例

このフォルダは、演習04で使う **`.cursor/rules` 形式の最小サンプル** です。  
Cursor の Project Rules を、1つの長い文ではなく **目的ごとに分けて管理する例** として使えます。

## ねらい
- ルールを「共通」「実装」「レビュー」などに分けて管理する
- 実装時とレビュー時で、見たい観点を整理しやすくする
- チームでルールを更新しやすくする

## フォルダ構成例

```text
.cursor/
  rules/
    00-project-overview.mdc
    10-coding-basics.mdc
    20-implementation-focus.mdc
    30-review-checks.mdc
```

## 使い方
1. この `cursor-rules-folder-example` を参考に、実際の実装プロジェクト直下に `.cursor/rules` フォルダを作る
2. 各 `.mdc` ファイルの内容を、今回の技術やチーム方針に合わせて調整する
3. 実装前に Cursor へ、要件・仕様・設計とあわせて参照させる
4. レビュー時は `30-review-checks.mdc` の観点を重点的に使う

## 分け方の考え方
- `00-project-overview.mdc`  
  この演習の目的や、勝手に機能追加しないことなど、全体方針を書く
- `10-coding-basics.mdc`  
  命名、関数分割、読みやすさ、エラー処理などの基本ルールを書く
- `20-implementation-focus.mdc`  
  実装時に特に守りたいことを書く
- `30-review-checks.mdc`  
  コードレビュー時の観点を書く

## 補足
- 実際の Cursor の運用では、チームやバージョンにより細かな形式差がある場合があります
- このサンプルは、**研修で考え方を学ぶための構成例** です
- まずは内容をシンプルにし、増やしすぎないことを優先してください
