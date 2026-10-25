---
id: "20261024T155624+0900__cursor-animeclubcal__学習__dddee05f"
type: "学習"
bot: "cursor-animeclubcal"
at: "2026-10-24T15:56:24+09:00"
tags:
  - "履歴復元"
  - "リポジトリ"
status: "追記"
source:
  - "commit:dddee05fc7bd155c2e779bdd33f2cefaa4525677"
  - "file:README.md"
related:
  - "20261024T162538+0900__cursor-animeclubcal__学習__42021586"
---

# 初回コミットは README だけ

2026-10-25 に、git log と diff から復元したノートです。当時の会話はリポジトリにありません。

## 依頼の要点

当時の依頼文は git に残っていない。残っているのは、2026-10-24 15:56 JST の `Initial commit` だけである。メッセージ以外の説明は無い。

## やったこと

コミット `dddee05fc7bd155c2e779bdd33f2cefaa4525677` は `README.md` を1ファイル追加している。中身は見出し `# animeclubcal` の1行である。

この時点のツリーに `index.html` も `events.json` も無い。GitHub Pages 用の設定ファイルも無い。公開 URL はリポジトリ直下を配信する形なので、このコミットだけではカレンダーはまだ無い。

次のコミットは約29分後（16:25 JST）で、そこで `events.json` と `index.html` が別々に入る。

## うまくいった・失敗したこと

リポジトリの起点としては足りている。製品の説明にはなっていない。ルートの README は今もこの1行のままで、データの形も画面の読み方もここからは分からない。コミットメッセージも `Initial commit` だけで、何を公開しようとしているかは diff を見ないと分からない。

## 次から気をつけること（ルール化候補）

- 最初の push を、カレンダーがある状態だと扱わない。画面とデータは次の2コミットで初めて入る。
- ルートの `README.md` を学習ログの置き場にしない。ログは `docs/learning-log/` に足し、この1行の README は変えない。
- コミットメッセージが中身を言わない前提でノートを書く。この先のメッセージは `update events.json` と `update index.html` だけである。

## 触ったファイル

- `README.md`（このコミットが追加。復元作業では未変更）
