# YOUKOKU STUDIO — Nagano Edition

長野の山並みと四季に着想を得た、淡い水彩トーンの YOUKOKU STUDIO 特設セールスページです。
完全無料で運用できるよう、フレームワークやビルドツールを使わない素の HTML / CSS / JavaScript で構成しています。

## 構成

```
.
├── index.html             # ページ本体(信州・長野テーマ)
├── assets/
│   ├── css/style.css      # 水彩トーンのスタイル一式
│   └── js/main.js         # スクロール演出・パララックス・落ち葉アニメーションなど
├── apps/                  # 掲載している各アプリ(Rhythm / Focusly / Kakeibo / Kotoba / Nocta)
└── icons/                 # ファビコン・ホーム画面アイコン用
```

## ローカルで確認する

ビルド不要です。`index.html` をブラウザで直接開くか、簡易サーバーを立てて確認してください。

```bash
python3 -m http.server 8000
# → http://localhost:8000 を開く
```

## 無料で公開する(GitHub Pages)

1. GitHub の `Settings` → `Pages` を開く
2. `Source` を `Deploy from a branch` にし、`main` ブランチ・`/ (root)` を選択して `Save`
3. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

## ライセンス

自由に改変・商用利用していただけます。
