# Bookworm TW

`bookwormtw.com` 根網域的靜態首頁，導流到各項小服務。

## Services

- [成語介紹](https://idiom.bookwormtw.com/)
- [成語遊戲](https://idiom-game.bookwormtw.com/)
- [全台哺乳室地圖](https://milkmap.bookwormtw.com/)
- [童書共讀筆記](https://kidsbook.pages.dev/)

## Stack

純靜態 HTML/CSS，無依賴。部署在 Cloudflare Pages。

## Files

- `index.html` — 首頁，含 JSON-LD (WebSite / ItemList / FAQPage)、OG/Twitter meta
- `robots.txt` — 允許主流搜尋與 AI 爬蟲
- `sitemap.xml` — 根網域與四項子服務
- `llms.txt` — LLM/answer-engine 友善摘要

## Local preview

直接用瀏覽器打開 `index.html`，或：

```sh
python3 -m http.server 8000
```
