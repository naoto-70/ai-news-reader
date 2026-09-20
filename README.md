# AI News Daily

AI 関連ニュースを日本語でまとめる静的サイトです。2026年9月20日から、開発・保守は Codex を主なアシスタントとして進めます。作業ルールは [AGENTS.md](AGENTS.md) に記載しています。

## ファイル構成

- `docs/index.html` — 最新号
- `docs/archive/` — 日付別の過去号
- `.github/workflows/deploy.yml` — GitHub Pages への公開

## 表示・公開

ビルドや依存パッケージのインストールは不要です。ローカルでは `docs/index.html` をブラウザーで開いて確認できます。

`main` ブランチに push すると、GitHub Actions が `docs/` を GitHub Pages に公開します。公開結果はリポジトリの Actions で確認してください。

## ニュースの更新

Codex に対象日を指定してニュース更新を依頼します。出典を確認して日本語で要約し、前号の保存、最新号の更新、リンクの確認を行います。具体的な手順は [AGENTS.md](AGENTS.md) を参照してください。

引き継ぎ時点の最新号は **2026年8月2日** です。リポジトリ内にはニュース収集の定期実行設定はなく、GitHub Actions は公開のみを担当します。Codex による定期更新も、この引き継ぎでは設定していません。以前の環境にある定期実行の有無は未確認です。
