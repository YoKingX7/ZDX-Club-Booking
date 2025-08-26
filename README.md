# 豬大仙的命理探險家俱樂部

-   【六角學院】團隊專題 #C-6 組｜ 2025 切版專題班
-   以 **Bootstrap + Vite** 打造的前端切版專案。
-   目標：打造一個 **實用且可落地** 的命理預約諮詢平台原型（前台流程 + 基礎互動）。
    > 傳統產業數位轉型 × 預約服務平台開發計畫

---

## 核心目標

以嶄新的視覺與友善互動，讓「命理」從神秘走向日常：

-   使用者可 **線上了解服務、完成預約**
-   命理師可 **設定可預約時段、管理申請**
-   後續規劃 **內容創作、評價、審核與數據** 等擴充模組

---

## 技術與開發

-   **Vite**（開發伺服器與建置）
-   **Bootstrap 5**（切版與元件）
-   **SCSS**（樣式管理）
-   **EJS**（樣板分離）
-   **Node.js ≥ 18**

---

## 快速開始

### Node.js 版本

-   專案的 Node.js 版本需為 **v18 以上**
-   查看版本：`node -v`

### 指令列表

-   `npm install`：初次下載專案請先安裝套件
-   `npm run dev`：執行開發模式
    -   若未自動開啟瀏覽器，請手動輸入  
        `http://localhost:5173/ZDX-Club-Booking/pages/index.html`
-   `npm run build`：執行編譯（不會開瀏覽器）
-   `npm run deploy`：自動化部署至 GitHub Pages

### 資料夾結構

-   assets # 靜態資源

    -   images # 圖片
    -   scss # SCSS 樣式

-   layout # ejs 模板
-   pages # HTML 頁面

### 注意事項

-   已將 `pages/index.html` 預設為首頁，**請勿更名**
-   `.gitignore` 已忽略不應上傳的檔案（如 `node_modules`），**請勿移除**
-   Vite 的 `npm run dev` 已自動監聽，**不需**再使用 Live Sass Compiler 監看

---

## 部署 GitHub Pages（gh-pages）

> 請在 vite.config.js 設定 base: '/<repo-name>/'

1. 建議先在 GitHub 建立 Repository：`ZDX-Club-Booking`

2. 初始化並推上遠端

```cmd
git init # 若已經初始化過就可以不用輸入
git add .
git commit -m 'first commit'
git branch -M main
git remote add origin [GitHub Repositories Url]
git push -u origin main // 僅限第一次輸入，往後只需要輸入 git push
```

3. 初始化完畢後，執行 `npm run deploy` 進行自動化部署

---

## 聲明

本專案為前端切版與流程模擬，不涉及真實個資。若後續串接後端或郵件服務，請補充隱私與資安說明。
