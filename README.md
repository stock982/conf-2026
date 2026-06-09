# 重構跨越臺海的現代史 — 會議網站

2026 國際學術研討會「重構跨越臺海的現代史：交纏、分歧與全球連結」雙語靜態網站。

## 本地預覽

```powershell
python -m http.server 8080
```

開啟 `http://localhost:8080/#/zh/home`

## 編輯內容

所有頁面文字、圖片路徑、按鈕、連結都集中在一個檔案：

```
content/site-data.js
```

用任何文字編輯器（VS Code、記事本）打開即可修改。

### 更換圖片

將新圖片放到 `assets/images/` 資料夾，檔名與 `site-data.js` 中的路徑一致即可。

### 海報圖片

- 聯展海報中文版：`assets/images/exhibition-poster-zh.jpg`
- 聯展海報英文版：`assets/images/exhibition-poster-en.jpg`
- 書展海報中文版：`assets/images/bookfair-poster-zh.jpg`
- 書展海報英文版：`assets/images/bookfair-poster-en.jpg`
