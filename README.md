# さわってわかるAI駆動開発

このリポジトリは、**初めてAI駆動開発に触れる人向け**に、
要件定義からドキュメント作成までを小さく体験できる演習教材です。

今回の教材では、各演習を **50分以内** で進めやすいように、
対象を絞った「小さな演習単位」に整理しています。

## この教材の使い方

最初に、次の順で見てください。

1. `docs/01-course-map.md` で全体像をつかむ
2. `docs/02-how-to-work.md` で進め方を確認する
3. `exercises/00-start-here/README.md` を読む
4. `exercises/01-requirements/` から順に進める

## フォルダ構成

```text
.
├─ docs/                      # コース全体の案内
├─ exercises/
│  ├─ 00-start-here/         # 最初に読む案内
│  ├─ 01-requirements/       # 要件定義
│  ├─ 02-specification/      # 仕様書作成
│  ├─ 03-design/             # 設計
│  ├─ 04-implementation/     # 実装
│  ├─ 05-testing/            # テスト
│  └─ 06-documentation/      # ドキュメント作成
└─ submissions/             # チーム成果物の保存先
```

## 演習一覧

| 演習 | ねらい | 時間 |
|---|---|---:|
| 00 Start Here | 進め方を理解する | 10分 |
| 01 要件定義 | 何を作るかを決める | 45分 |
| 02 仕様書作成 | どう振る舞うかを決める | 45分 |
| 03 設計 | 実装しやすい形に分解する | 45分 |
| 04 実装 | 最小機能を作る | 50分 |
| 05 テスト | 最低限の確認を自動化する | 40分 |
| 06 ドキュメント作成 | 他人が読める説明にする | 30分 |

## この教材の方針

- 最初から全部作らない
- AIにはたたき台を作らせる
- 人は選ぶ・直す・確かめる役割を持つ
- 難しい内容は後回しにし、まずは流れをつかむ

## 成果物の置き場所

各チームは、演習ごとに次の場所へ成果物を保存してください。

- `submissions/<team-name>/01-requirements.md`
- `submissions/<team-name>/02-specification.md`
- `submissions/<team-name>/03-design.md`
- `submissions/<team-name>/04-implementation.md`
- `submissions/<team-name>/05-testing.md`
- `submissions/<team-name>/06-documentation.md`

テンプレートは各演習フォルダの `06-template.md` にあります。
