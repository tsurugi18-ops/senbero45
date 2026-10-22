# せんべろ45 タイマー

45分せんべろを管理するPWA（iPad Air 5 横向き向け）。

## 公開URL

**GitHub Pages:** https://tsurugi18-ops.github.io/senbero45/

## リポジトリ

https://github.com/tsurugi18-ops/senbero45

## iPadへのインストール

1. iPadのSafariで上記URLを開く
2. 共有ボタン → 「ホーム画面に追加」
3. オフラインでも起動可

## ファイル構成

| ファイル | 内容 |
|---|---|
| `index.html` | 画面・ロジックすべて |
| `manifest.webmanifest` | PWA設定（standalone / landscape） |
| `sw.js` | Service Worker（オフライン対応） |
| `icon-*.png` | アイコン |
| `SPEC.md` | 仕様書（引き継ぎ用） |

## 更新手順

```bash
# ファイルを編集後
git add .
git commit -m "変更内容"
git push
# GitHub Pages に自動反映（1〜2分）
```

> `sw.js` の `CACHE` 名を上げないとiPadに古いバージョンが残るので注意（例: `senbero45-v2`）。

## 仕様

→ [SPEC.md](SPEC.md) を参照
