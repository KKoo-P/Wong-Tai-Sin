# 黃大仙靈籤 - 粉彩東方古典風 / Wong Tai Sin Fortune Sticks - Pastel Eastern Classical Style

## 中文說明

這是一個基於 HTML5、CSS3、JavaScript 和 PWA (Progressive Web App) 技術開發的線上「黃大仙靈籤」互動網頁。本項目採用溫潤優雅的粉彩東方古典色系（如豆綠、胭脂粉、宣紙米白），為使用者提供沉浸且平靜的求籤與解籤體驗。

### 主要功能
* **完整靈籤資料庫**：內建 100 支黃大仙靈籤的完整數據，包含籤序、籤標、籤運（上上、上吉、中平、下下等）[cite: 1]。
* **雙語詩詞對譯**：提供每支籤詩的中文原文及精確的英文翻譯[cite: 1]。
* **多維度分類解讀**：使用者可針對特定訴求（事業、財運、姻緣、健康、學業、家庭）查看專屬的詳細中英文解簽說明[cite: 1]。
* **PWA 離線支援**：支援 Progressive Web App 技術（包含 `manifest.json` 與 Service Worker），可作爲獨立 App 安裝至手機或電腦，並支援離線運行[cite: 1]。
* **響應式網頁設計 (RWD)**：完美適配手機、平板與桌上型電腦等不同螢幕尺寸[cite: 1]。

### 視覺與美學設計
* **粉彩東方色調**：使用豆綠（#8EAE9D）、胭脂粉（#D3A29D）、羊脂白（#FFFFFF）與古典霧面金（#C5A059），營造清新脫俗的古典美感[cite: 1]。
* **中式傳統紋樣**：網頁融入宣紙背景質感與古典祥雲元素，增添東方意境[cite: 1]。

---

## English Description

This is an interactive online "Wong Tai Sin Fortune Sticks" web application built using HTML5, CSS3, JavaScript, and PWA (Progressive Web App) technologies. The project adopts a soothing and elegant pastel Eastern color palette (such as celadon green, rouge pink, and Xuan paper white) to provide users with an immersive and peaceful fortune-telling experience.

### Key Features
* **Complete Fortune Database**: Built-in comprehensive data for all 100 Wong Tai Sin fortune sticks, including stick numbers, titles, and luck levels (e.g., Top-Top, Top-Auspicious, Medium-Smooth, Bottom-Bottom)[cite: 1].
* **Bilingual Verses**: Provides the original Chinese poem for each stick along with its precise English translation[cite: 1].
* **Multi-Dimensional Interpretation**: Users can select specific categories (Career, Wealth, Love, Health, Study, Family) to view dedicated, detailed interpretations in both Chinese and English[cite: 1].
* **PWA & Offline Support**: Supports Progressive Web App features (via `manifest.json` and Service Worker)[cite: 1]. It can be installed locally on mobile devices or desktops and used offline[cite: 1].
* **Responsive Web Design (RWD)**：Perfectly optimized for various screen sizes, including smartphones, tablets, and desktops[cite: 1].

### Design & Aesthetics
* **Pastel Eastern Palette**: Uses Celadon Green (#8EAE9D), Rouge Pink (#D3A29D), Suet Oil White (#FFFFFF), and Matte Gold (#C5A059) to establish a fresh, elegant, and classical aesthetic[cite: 1].
* **Traditional Chinese Elements**: Incorporates a warm Xuan-paper-textured background and classical auspicious cloud motifs to enhance the spiritual atmosphere[cite: 1].

---

## 項目結構 / Project Structure

* `index.html` - 主網頁程式碼（包含全量籤文數據與前端邏輯） / Main application file (contains all data and frontend logic)[cite: 1].
* `manifest.json` - PWA 設定檔 / PWA manifest configuration[cite: 1].
* `sw.js` - Service Worker 快取腳本（需自行建立以實現離線功能） / Service Worker script for offline caching[cite: 1].
* `icon-192.png` - PWA 應用程式圖示 / PWA application icon[cite: 1].