# 学習ログ

Cursor（`bot: cursor-animeclubcal`）がこのリポジトリを変更するたびに、1枚だけ追記するノートです。公開サイトの `index.html` と `events.json` とは別で、表示やデータの動作には使いません。

このディレクトリは Obsidian Vault `~/Downloads/Grok の 記録/学習/` へ同期されます。ファイル名がノートの id です。既存のノートは書き換えず、新しいファイルを足します。ノートを足すたびに、この README は更新しません。

## 置き場所

`docs/learning-log/YYYY/MM/<id>.md`

`YYYY/MM` はノートの時刻（日本時間）です。

## id

`YYYYMMDDTHHMMSS+0900__cursor-animeclubcal__学習__<8hex>`

`<8hex>` は小文字の16進8桁です。例: `20261024T155624+0900__cursor-animeclubcal__学習__dddee05f`

## front matter

| キー | 内容 |
| --- | --- |
| `id` | ファイル名と同じ id |
| `type` | `学習` |
| `bot` | `cursor-animeclubcal` |
| `at` | 日本時間の ISO 8601（`2026-10-24T15:56:24+09:00`） |
| `tags` | 短い話題のリスト |
| `status` | `記録`（変更と同時）または `追記`（git 履歴から復元） |
| `source` | `commit:` + フル SHA、`file:` + パス |
| `related` | 関連ノートの id。無ければ `[]` |

## 本文

次の見出しをこの順で書きます。

1. 依頼の要点
2. やったこと
3. うまくいった・失敗したこと
4. 次から気をつけること（ルール化候補）
5. 触ったファイル

秘密、鍵、個人情報は書きません。規則の全文は `.cursor/rules/obsidian-learning-log.mdc` です。
