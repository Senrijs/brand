# Senri / Ippo logos

すべて文字をアウトライン化した SVG です(フォントが入っていない環境でも同じ見た目になります)。

## ワードマーク

| ファイル | 使う場所 |
| --- | --- |
| `*-wordmark-light.svg` | 明るい背景(文字 #111418 / スラッシュ #E3412B) |
| `*-wordmark-dark.svg` | 暗い背景(文字 #FFFFFF / スラッシュ #E3412B) |
| `*-wordmark-mono-black.svg` | 1色で刷るとき(黒) |
| `*-wordmark-mono-white.svg` | 朱色や写真の上など(白) |

`senri-` = `senr/`、`ippo-` = `/ppo`、`senri-ippo-` = `senr/ppo`

## アイコン(160×160、角丸36)

| ファイル | 中身 |
| --- | --- |
| `*-icon-dark.svg` | 黒タイル + 白文字 + 朱色スラッシュ |
| `*-icon-light.svg` | 白タイル(枠線あり) + 黒文字 + 朱色スラッシュ |
| `*-icon-accent.svg` | 朱色タイル + 白 |

`senri-` = `s/`、`ippo-` = `/p`

## マーク(点つきスラッシュ「i」だけ)

| ファイル | 中身 |
| --- | --- |
| `mark-accent.svg` / `mark-black.svg` / `mark-white.svg` | 背景なし、1色 |
| `mark-icon-dark.svg` / `mark-icon-light.svg` / `mark-icon-accent.svg` | タイル付き(アイコンと同じ3色) |

## README で使う(GitHub のライト/ダークで自動切り替え)

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/senri-wordmark-dark.svg">
  <img src=".github/assets/senri-wordmark-light.svg" alt="Senri" height="56">
</picture>
```

## 色

- アクセント: #E3412B
- 文字(明るい背景): #111418
- 文字(暗い背景): #FFFFFF

## フォント

ワードマークは JetBrains Mono ExtraBold(SIL Open Font License 1.1)をアウトライン化したものです。
