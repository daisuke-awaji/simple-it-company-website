# Simple IT Company Website

シンプルで現代的なIT企業のウェブサイトです。

## 特徴

- 📱 完全レスポンシブデザイン
- 🎨 モダンでクリーンなUI
- ⚡ 軽量で高速
- 🎯 SEO対応
- ✨ スムーズなアニメーション効果

## 技術スタック

- HTML5
- CSS3
- JavaScript (Vanilla)

## セクション

1. **Hero** - 会社のメインメッセージ
2. **About** - 会社概要と実績
3. **Services** - 提供サービス一覧
4. **Contact** - お問い合わせフォーム

## セットアップ

### 必要なもの

- モダンなWebブラウザ

### 起動方法

1. リポジトリをクローン
```bash
git clone https://github.com/daisuke-awaji/simple-it-company-website.git
cd simple-it-company-website
```

2. `index.html` をブラウザで開く
```bash
open index.html  # macOS
# または
start index.html # Windows
# または
xdg-open index.html # Linux
```

または、シンプルなHTTPサーバーを起動：

```bash
# Python 3の場合
python -m http.server 8000

# Node.jsのhttpサーバーの場合
npx http-server
```

ブラウザで `http://localhost:8000` にアクセス

## カスタマイズ

### 色の変更

`style.css` の `:root` セクションで色を変更できます：

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-gray: #f3f4f6;
    --white: #ffffff;
}
```

### コンテンツの変更

- 会社名: `index.html` の `.logo` と `<title>`
- サービス内容: `index.html` の `.service-card` セクション
- 連絡先情報: `index.html` の `.contact-info` セクション

## ライセンス

MIT License

## 作成者

TechVision
