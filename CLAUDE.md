## プロジェクト概要

crgstar のコーポレートサイト（GitHub Pages / crgstar.com）

## ファイル構成

- `index.html` - メインページ（英語/日本語切り替え対応）
- `CNAME` - カスタムドメイン設定（crgstar.com）
- `kumorb-icon.png` - Kumorb アプリアイコン
- `gymlogue-icon.png` - Gymlogue アプリアイコン

## 技術構成

- 静的 HTML + CSS + JS（フレームワークなし・単一ファイル）
- Google Fonts: Manrope
- カラー: セージグリーン系（primary: #84A98C / secondary: #445964）
- ダークモード対応（prefers-color-scheme + CSS変数）
- レスポンシブデザイン（640px breakpoint）
- JavaScript による英語/日本語切り替え（data-en / data-ja 属性）
- フェードアップのエントランスアニメーション

## サイト構成

ヘッダー → アプリ一覧（Kumorb, Gymlogue） → Contact CTA → フッター

## アプリ状況

- **Kumorb** - リリース済み（[App Store](https://apps.apple.com/app/kumorb/id6757797196)）
- **Gymlogue** - Coming Soon

## デプロイ

GitHub Pages で自動デプロイ（main ブランチ push 時）
