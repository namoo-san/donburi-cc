# donburi.cc

どんぶりシステムズが運営するWebサービスです。

## 技術スタック

- [Astro](https://astro.build/) - 静的サイトジェネレーター
- [Cloudflare Pages](https://pages.cloudflare.com/) - ホスティング
- カスタムドメイン: donburi.cc

## ページ構成

| パス | 内容 |
|------|------|
| `/` | トップページ |
| `/privacy` | プライバシーポリシー |
| `/terms` | 利用規約 |

## 開発

```bash
npm install
npm run dev
```

## ビルド

```bash
npm run build
```

`dist/` に静的ファイルが出力されます。`main` ブランチへのpushでCloudflare Pagesに自動デプロイされます。
