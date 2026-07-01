# 🧭 台灣軟韌體工程師職涯導航 (Taiwan FW/SW Career Navigator)

這是一個專為即將取得碩士學位的科技業新鮮人打造的單頁互動式網頁應用程式 (SPA)。本專案彙整了全台軟韌體 (Firmware/Software) 職缺的地理分佈、公司分級 (Tier) 落點分析，以及第一份工作的選職實戰指南，幫助新鮮人做出更明確的職涯規劃。

## ✨ 核心功能 (Features)

* **📍 科技聚落與地理分佈：** 透過互動式圓餅圖與動態資訊卡片，視覺化呈現竹科、大台北、桃園與台中等地的產業特性與代表企業。
* **🏆 公司排名與落點分析：** 實作動態散佈圖 (Scatter Plot)，直觀對比各 Tier 公司（一線 IC、頂尖系統廠、一般系統廠）在「新人年薪」與「生活品質 (WLB)」上的權衡關係。
* **🎓 新鮮人實戰指南：** 採用互動式標籤頁 (Tabs) 設計，將龐大的職涯建議梳理成「產業領域」、「技術深度」、「企業文化」與「面試建議」四大模塊，提升閱讀體驗。

## 🛠️ 技術棧 (Tech Stack)

本專案採用無構建工具 (Build-tool-free) 的輕量化架構開發：

* **前端框架與排版：** HTML5, [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* **資料視覺化：** [Chart.js](https://www.chartjs.org/) (via CDN)
* **互動邏輯：** Vanilla JavaScript (ES6+)
* **部署平台：** [Vercel](https://vercel.com/)

## 🚀 如何在本地端運行 (Local Setup)

本專案無需安裝 node modules 或任何本地伺服器環境即可運行。

1.  將此儲存庫 Clone 到本地端：
    ```bash
    git clone [https://github.com/你的GitHub帳號/你的專案名稱.git](https://github.com/你的GitHub帳號/你的專案名稱.git)
    ```
2.  進入專案資料夾。
3.  直接使用瀏覽器（如 Chrome, Edge, Safari）開啟 `index.html` 檔案即可預覽完整功能。
    *(推薦使用 VS Code 的 Live Server 擴充功能獲得更好的開發體驗)*

## 🌐 網站部署 (Deployment)

本網站已自動化部署至 Vercel。任何推送到 `main` 分支的更新都會自動觸發 CI/CD 流程並更新至正式網址。

* **Live Demo:** https://fw-sw-website.vercel.app/

## 🤝 貢獻與反饋 (Contributing)

這是一份持續更新的指南。如果您有更精確的產業資訊或建議，歡迎提交 Issue 討論，或是發起 Pull Request 協助完善這份圖鑑！

---
*Created for future engineers in Taiwan.*
