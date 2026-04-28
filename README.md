# Bookworm TW

`bookwormtw.com` 根網域的靜態首頁。

> 一個 PM＋工程師媽媽 Nina，為女兒「雞蛋糕」做的繁體中文小工具集散地。

## Services

- [成語介紹](https://idiom.bookwormtw.com/)
- [成語遊戲](https://idiom-game.bookwormtw.com/)
- [全台哺乳室地圖](https://milkmap.bookwormtw.com/)
- [童書共讀筆記](https://kidsbooks.bookwormtw.com/)
- [台北文化活動](https://taipei-culture.bookwormtw.com/)

## Stack

純靜態 HTML/CSS，無依賴。部署在 Cloudflare Pages。

## Files

- `index.html` — 首頁，含 JSON-LD (WebSite / Person / ItemList / FAQPage)、OG/Twitter meta
- `robots.txt` — 允許主流搜尋與 AI 爬蟲
- `sitemap.xml` — 根網域與五項子服務
- `llms.txt` — LLM/answer-engine 友善摘要
- `_redirects` — www → apex 301

## Local preview

```sh
python3 -m http.server 8000
```
