# はじめに

このリポジトリは軽量な仕様駆動開発を行うためのテンプレートリポジトリです

## 使い方
[`.litespec/README.md`](.litespec/README.md) を読んでください。

## おすすめの使い方（概要）

### 既存仕様や関連ドキュメントがある場合

1. 既存ドキュメントを LLM に渡す
2. [`AGENTS.md`](AGENTS.md) を読ませ、[`.litespec/SPEC.md`](.litespec/SPEC.md) と [`.litespec/specs/`](.litespec/specs/) へ反映させる
3. 不足項目は TODO として残し、実装前に埋める

### まだ仕様が固まっていない場合

1. [`AGENTS.md`](AGENTS.md) を前提に、一問一答で初期仕様を固めるよう LLM に依頼する
2. 回答を「確定事項 / 未確定事項」に分ける
3. [`.litespec/SPEC.md`](.litespec/SPEC.md)（全体）と [`.litespec/specs/`](.litespec/specs/)（機能詳細）に整理して反映する

詳細な手順とプロンプト例は [`.litespec/README.md`](.litespec/README.md) を参照してください。
