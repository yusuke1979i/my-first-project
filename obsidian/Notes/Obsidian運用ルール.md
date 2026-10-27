---
tags: [rule]
---
# Obsidian運用ルール

- Claude は作業開始時に `00_Index.md`・直近の `Sessions/`・関連する `Notes/` を参照する。
- 作業内容はすべて `Sessions/` に記録し、長く使う知識は `Notes/` に切り出す。
- Index のセッション一覧と決定事項を更新する。
- 記録はコードと一緒にコミット・push する。

## 背景
- クラウド環境の Claude はユーザーの PC 上の Obsidian に直接アクセスできないため、Vault をリポジトリ内(`obsidian/`)に置き、git で同期する。
- ローカルでは `obsidian/` フォルダを Obsidian で「フォルダを保管庫として開く」で開く。Obsidian Git プラグインを使うと pull/push を自動化できる。

ルールの本体はリポジトリ直下の `CLAUDE.md`。
