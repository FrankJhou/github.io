# GitHub Pages 超簡單入門範例

這個資料夾包含：

- `index.html` — 首頁
- `style.css` — 簡單樣式
- （可選）之後你可以新增圖片、其他頁面

## 快速上線（使用 GitHub 網頁介面）

1. 到 GitHub 建立一個新資料庫（Repository）。如果你想做「個人主頁」，名稱必須是：`你的使用者名稱.github.io`（例：`octocat.github.io`）。
2. 進入該資料庫後，點 **Add file → Upload files**，把這個資料夾中的所有檔案上傳，然後 **Commit changes**。
3. 到 **Settings → Pages**：
   - **Source** 選 **Deploy from a branch**
   - **Branch** 選 `main`，**資料夾**選 `/ (root)`，按 **Save**
4. GitHub 會自動部署。你的網站網址：
   - 若資料庫名稱是 `你的使用者名稱.github.io`：網址就是 `https://你的使用者名稱.github.io`
   - 否則：`https://你的使用者名稱.github.io/你的資料庫名稱`

> 看到 404？請確認你已經上傳並 **Commit** 了 `index.html`，且 Pages 設定為 `main` 分支的根目錄。

## 客製化

- 打開 `index.html`，把「你的名字」、「you@example.com」等字樣改成自己的資訊。
- 想換色？修改 `style.css` 最上方的色票變數。
- 想新增作品卡片？複製 `<article class="card">...</article>` 那段貼上再改內容即可。

## 自訂網域（選用）

1. 在 DNS 設定新增 CNAME 指向 `你的使用者名稱.github.io`
2. 在 GitHub 的 **Settings → Pages → Custom domain** 填入你的網域；GitHub 會提示 DNS 紀錄設定是否正確。

祝順利上線！
