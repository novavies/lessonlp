# 坂本瑛希 卓球個人レッスン LP

GitHub Pages向けの静的LPです。HTML / CSS / JavaScriptのみで動作し、ビルドツールは不要です。

## 公開前に変更する箇所

1. `index.html` の canonical URL
   - `YOUR_GITHUB_ID`
   - `YOUR_REPOSITORY`
2. `robots.txt` の Sitemap URL
3. `sitemap.xml` の `<loc>`
4. LINEのボタンリンク
   - 現在はページ内 `#contact` にしています。
   - LINE公式アカウントのURLが分かれば `href` を差し替えてください。
5. Instagram URL / アカウント名が異なる場合は修正してください。

## GitHub Pages公開

```bash
git init
git add .
git commit -m "Initial landing page"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_ID/YOUR_REPOSITORY.git
git push -u origin main
```

GitHubの Repository → Settings → Pages で、Branchを `main` / `/root` に設定します。
