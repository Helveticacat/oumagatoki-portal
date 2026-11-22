# オウマガトキ GUILD PORTAL — Codex引き継ぎパッケージ v2.14

## これは何か

既存リポジトリ `Helveticacat/oumagatoki-portal` に、現時点の完成版HTMLと不足している制作履歴を反映するための差分パッケージです。

## GitHubに適用するもの

- `index.html`：リポジトリ直下の同名ファイルと**置き換える**（最優先）。背景画像・CSS・JavaScriptをHTML内に埋め込み済み。
- `docs/V2_11_UI_RULES.md`, `V2_12_UI_RULES.md`, `V2_13_CHANGELOG.md`, `V2_14_DESIGN_ADDENDUM.md`, 各変更記録：`docs/` に**追加する**。

## 上書きしない既存資料

- `docs/REQUIREMENTS.md`
- `docs/UI_SPEC.md`
- `docs/DESIGN_GUIDELINES.md`
- `docs/references/home_approved.png`
- `docs/references/carriage_approved.png`
- `docs/references/officer_approved.png`

これらはGitHubに既に存在する基幹資料・承認画像です。今回のZIPには重複収録せず、改変もしません。

## その他のファイル

- `assets/v2.14/`：画像を個別に再利用するための控え。**表示のためにアップロードする必要はありません**（HTML内包済み）。
- `previews/`：確認用の参考スクリーンショット。公開サイトへの設置は不要。

## Codexへの指示例

「既存のGitHubリポジトリ `Helveticacat/oumagatoki-portal` を開き、このZIPの `index.html` をルートに適用してください。`docs/` の追補Markdownを追加し、基幹仕様書3点と承認画像3点は残してください。機能を破壊せずに表示確認し、変更をコミットしてGitHub Pagesへの反映を確認してください。実際のギルド情報や秘密情報は追加しないでください。」

## 注意

- 実装は公開操作プロトタイプであり、認証・権限制御・共有保存・データベース連携は未実装。
- ZIPは2026-11-23に作成。GitHubへの直接コミットは行っていません。
