# Skyline Technologies コーポレートサイト

架空のクラウド基盤プラットフォーム企業「スカイライン・テクノロジーズ株式会社」を紹介する、1ページ構成のコーポレートサイトです。

## 概要

- プロダクト紹介、導入実績、導入事例、採用情報、会社概要をまとめた1ページのランディングページです。
- ビルドツールや依存パッケージは使用しておらず、`index.html` 単体で完結します。
- フォントは Google Fonts(Zen Kaku Gothic New / Noto Sans JP / JetBrains Mono)をCDN経由で読み込みます。

## ブラウザで開く方法

`index.html` をブラウザで直接開くだけで閲覧できます。

- エクスプローラーで `index.html` をダブルクリックする
- または、ターミナルから以下を実行する

```bash
start index.html   # Windows
```

ローカルサーバー経由で確認したい場合は、以下のいずれかを利用してください。

```bash
# Python がインストールされている場合
python -m http.server 8000

# Node.js がインストールされている場合
npx serve .
```

起動後、ブラウザで `http://localhost:8000`(またはコマンドの出力に表示されたURL)にアクセスしてください。
