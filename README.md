# Kim's Blog

個人部落格 — 技術與生活的混合筆記（FinOps、雲端、AI 與日常）。

基於 [AstroPaper](https://github.com/satnaing/astro-paper) 主題（MIT License）客製：繁體中文介面（zh-TW）、系統字型堆疊、Noto Sans TC 動態 OG 圖、giscus 留言。

## 開發

```bash
npm install
npm run dev     # http://localhost:4321
npm run build   # astro check + build + pagefind 索引
```

## 發文慣例

- 文章放 `src/content/posts/`，slug 用英文 kebab-case
- frontmatter：`title`、`description`、`pubDatetime`、`tags`
- 第一個 tag 是大分類（`tech`／`life`），後接細項 tag

## 部署

push 到 `main` → GitHub Actions（`.github/workflows/deploy.yml`）自動建置並發佈到 GitHub Pages：**https://blueshing.github.io**

設計文件與實作計畫見 `docs/superpowers/`。
