# ぼくのブラックホール

小さなブラックホールが宇宙のものを食べて大きくなる、子ども向けブラウザゲーム。

- 単一の `index.html`（Three.js r128 は CDN 読み込み）。ビルド不要。
- スマホ / タブレットのタッチ操作に対応。
- セーブ・記録はブラウザの localStorage に保存（端末ごと）。

## ローカルで見る
`index.html` をブラウザで開くだけ（または `npx serve .`）。

## Vercel にデプロイ
1. Vercel で「Add New → Project」からこのリポジトリを Import
2. Framework Preset: **Other**、Build Command / Output Directory は空のまま
3. Deploy

## 今後
- BGM 音源ファイル用のフォルダ構成、Android 化（Capacitor）
- 課金範囲（無料/有料）の仕様検討
