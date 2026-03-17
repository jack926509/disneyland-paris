# 🏰 巴黎迪士尼 2026 完整攻略

> 歐洲唯一迪士尼的一站式旅遊指南，涵蓋交通、購票、熱門設施、商店購物。  
> 以 GitHub Pages 靜態網站形式部署，任何人皆可透過瀏覽器瀏覽。

🔗 **線上瀏覽**：`https://<你的GitHub帳號>.github.io/<repo名稱>/`

---

## 📁 專案結構

```
disneyland-paris-2026/
├── index.html      # 主攻略頁面（網站首頁）
├── style.css       # 所有樣式設定
└── README.md       # 本說明文件
```

---

## ✨ 2026 最大亮點

- **2026 年 3 月 29 日**：《冰雪奇緣》全新園區 **World of Frozen** 正式開幕
- 第二園區正式更名為 **Disney Adventure World**（原 Walt Disney Studios Park）
- 全新夜間表演 **Disney Cascade of Lights** 於 Adventure Bay 湖面首演
- **Ratatouille** 料理鼠王設施升級翻新（新增場景、強化投影效果）
- Disney Village 新增 **Disney Wonders**、**Pelé Soccer 歐洲首店**

---

## 📖 攻略內容

| 章節 | 內容 |
|------|------|
| 🚇 市區往返交通 | RER A 線搭乘方式、票價、機場接駁、自駕資訊 |
| 🎟️ 入園購票指南 | 票種比較、購票管道、DPA 快速通關說明 |
| 🎢 熱門設施總覽 | 兩大園區必玩設施、表演秀時刻 |
| 🛍️ 商店購物指南 | Disney Village、限定商品、紀念品推薦 |
| 💡 實用旅遊貼士 | 最佳時段、App 使用、省錢技巧 |

---

## 🚀 部署到 GitHub Pages

### 方法一：從 GitHub 網頁操作（最簡單）

1. 在 GitHub 建立新 Repo（例如：`disneyland-paris-2026`）
2. 將 `index.html`、`style.css`、`README.md` 三個檔案上傳
3. 進入 Repo → **Settings** → **Pages**
4. Source 選擇 `Deploy from a branch`
5. Branch 選擇 `main`，資料夾選擇 `/ (root)`
6. 點擊 **Save**，等待約 1–2 分鐘即可上線

🔗 網址格式：`https://<帳號>.github.io/<repo名稱>/`

---

### 方法二：使用 Git 指令（推薦）

```bash
# 1. Clone 你的 Repo（先在 GitHub 建立）
git clone https://github.com/<你的帳號>/<repo名稱>.git
cd <repo名稱>

# 2. 複製三個檔案到此目錄
#    index.html、style.css、README.md

# 3. 提交並推送
git add .
git commit -m "feat: add Disneyland Paris 2026 travel guide"
git push origin main

# 4. 到 GitHub → Settings → Pages 開啟 GitHub Pages（同方法一步驟 3-6）
```

---

## 🔧 本地預覽

不需要任何框架，直接用瀏覽器開啟即可：

```bash
# macOS / Linux
open index.html

# Windows
start index.html
```

或使用 VS Code 的 **Live Server** 套件即時預覽。

---

## 🛠️ 自訂修改

| 想修改的項目 | 對應檔案 | 對應位置 |
|-------------|---------|---------|
| 頁面文字內容 | `index.html` | 各 `<section>` 區塊內 |
| 顏色主題 | `style.css` | 最上方 `:root { }` 變數 |
| 字型 | `index.html` + `style.css` | Google Fonts `<link>` 及 `font-family` |
| 版面排版 | `style.css` | 對應的 `.grid`、`.card` 樣式 |

### 主色調變數（`style.css` 最上方）

```css
:root {
  --gold:       #C9A84C;   /* 金色（強調色）*/
  --deep:       #1A0A2E;   /* 深紫（背景色）*/
  --rose:       #C96C8A;   /* 玫瑰粉（區塊標題）*/
  --cream:      #FAF5EC;   /* 米白（頁面底色）*/
}
```

---

## 📌 資料來源與更新日期

- 資料截至：**2026 年 3 月**
- 票價採浮動制，以 [Disneyland Paris 官網](https://www.disneylandparis.com) 公告為準
- 設施營運狀態請於出發前確認官方最新消息

---

## 📄 授權

本攻略內容為個人旅遊筆記整理，歡迎自由使用與修改。  
Disneyland Paris 及相關商標為 © The Walt Disney Company 所有。
