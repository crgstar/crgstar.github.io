## プロジェクト概要

crgstar のコーポレートサイト（GitHub Pages）

## ファイル構成

- `index.html` - メインページ（英語/日本語切り替え対応）
- `CNAME` - カスタムドメイン設定（crgstar.com）
- `gymlogue-icon.png` - Gymlogue アプリアイコン
- `kumorb-icon.png` - Kumorb アプリアイコン

## 技術構成

- 静的 HTML + CSS のみ（フレームワークなし）
- ダークモード対応（prefers-color-scheme）
- レスポンシブデザイン
- JavaScript による英語/日本語切り替え（data-en / data-ja 属性）

## デプロイ

GitHub Pages で自動デプロイ（main ブランチ push 時）
