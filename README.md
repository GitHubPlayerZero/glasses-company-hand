# 切版作品 ![home-section2-4](https://hackmd.io/_uploads/ByifsmTuC.png =50x) 眼鏡公司

[Website](https://githubplayerzero.github.io/glasses-company-hand/index.html)｜[設計稿](https://xd.adobe.com/view/5b20cbc4-5c64-4b67-814e-633b078a8cd4-0e73/flow/)

## 📌 特色
### 主要特色
- 以 SCSS 手刻格線系統、各種 utility class。
- 使用 EJS 共用相同的佈局。
- 專案環境使用 Vite。

### 其它特色
- 多頁式（8 頁）
- 多欄式（Flex 排版）
- RWD：桌機（優先）、平板、手機
- 風格：主要為原子化（utility）方式，輔以客製化（語意化）、components（元件化）。
<br>

## 💻 專案環境
### 開發環境
- node.js：v20.14.0
- npm：10.7.0
<br>

### 專案結構重點說明
- 📂 assets：靜態資源
    - 📁 images：圖片
    - 📁 scss：SCSS
        - 📁 components：共用元件樣式
        - 📁 layout：EJS 模板客製樣式
        - 📁 mixins：共用 mixin
        - 📁 pages：各頁面客製化樣式
        - 📁 utils：各種 utility 樣式
        - 📄 _variables.scss：變數檔案
        - 📄 _reset.scss：使用 meyerweb
        - 📄 _reboot.scss：切版常會使用的基本初始設定
        - 📄 _base.scss：此專案的全站基本樣式
        - 📚 all.scss：樣式主檔，匯入所有樣式
- 📁 layout：EJS 模板
- 📁 pages：各頁面 HTML
- 📁 public：不需編譯的靜態資源
    - ⭐ favicon.ico
- 🛠️ main.js：專案程式核心設定，會在此引入及初始化所有全局樣式與套件。每一頁 HTML 都會引用此檔案。
- ⚡ vite.config.js：Vite 專案的設定檔。
<br>

## 🎬 Demo



<br>

## ⚔️ 相關技巧練習範例
- [Flex box](https://codepen.io/collection/ZMebzz)
- [background-image](https://codepen.io/codepenplayer/pen/gOQzLxV)
- border-radius
    - [border-radius 四個角分別設定](https://codepen.io/codepenplayer/pen/KKYRBwL)
    - [border-radius 簡寫](https://codepen.io/codepenplayer/pen/LYXryzd)
- [box-shadow](https://codepen.io/codepenplayer/pen/rNQKYMv)
- [linear-gradient](https://codepen.io/codepenplayer/pen/ZEmjqWE)
- [resize](https://codepen.io/codepenplayer/pen/JjQjGMB)
- [accent-color](https://codepen.io/codepenplayer/pen/mdZdEKK)
- [pointer-events](https://codepen.io/codepenplayer/pen/yLGYQwr)
- [SVG 畫圖](https://codepen.io/codepenplayer/pen/BavoqEQ)
- [三角形、下拉選單箭頭](https://codepen.io/codepenplayer/pen/oNJjwKW)

<hr>

✡️ 六角學院 2023 切版夏季班 - 第四週作業
僅作為個人學習、作品集，無商業用途，設計稿版權屬六角學院。
