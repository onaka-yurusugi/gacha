# Ultimate Gacha Simulator

ブラウザで動作するガチャシミュレーターです。

## デモ

https://gacha-o2668m9rg-onakayurus-projects.vercel.app

## 機能

- **1回ガチャ**: 単発でガチャを引く
- **10連ガチャ**: 10回まとめてガチャを引く
- **レアリティ演出**: レアリティに応じた演出効果
  - SSR: 虹色エフェクト + パーティクル
  - SR: ダイヤモンド演出
  - R/N: 通常演出
- **獲得履歴**: 引いたアイテムの履歴を表示

## レアリティと排出率

| レアリティ | アイテム | 排出率 |
|:---:|:---|:---:|
| SSR | 神鳥フェニックス | 3% |
| SR | 魔法の盾 | 12% |
| R | 鋼のつるぎ | 25% |
| N | ただの石ころ | 60% |

## 技術スタック

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

## ローカルで実行

```bash
# リポジトリをクローン
git clone https://github.com/onaka-yurusugi/gacha.git
cd gacha

# public/index.html をブラウザで開く
open public/index.html
```

## ライセンス

MIT
