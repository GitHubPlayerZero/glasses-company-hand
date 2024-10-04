# 切版作品：眼鏡公司

[Website](https://githubplayerzero.github.io/glasses-company-hand/index.html)｜[設計稿](https://xd.adobe.com/view/5b20cbc4-5c64-4b67-814e-633b078a8cd4-0e73/flow/)

## 📌 特色
- 以 SCSS 手刻格線系統、各種 utility class。
- 使用 EJS 共用相同的佈局。
- 專案環境使用 Vite。
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
### 桌機
- 首頁

[首頁_dt.webm](https://github.com/user-attachments/assets/e6df5f50-a66a-4a83-b4e3-ab92597521eb)

- 系列鏡框

[系列鏡框_dt.webm](https://github.com/user-attachments/assets/2bfbad6f-dfee-46ed-be74-d1fe7afc0c0b)

- 門市據點

[門市_dt.webm](https://github.com/user-attachments/assets/82c14487-4de3-41a7-b177-abd9ee0f7653)

- 部落格

[部落格_dt.webm](https://github.com/user-attachments/assets/6efea69f-21c4-4d39-b2bd-b1215148c4a4)

<br>

### 平板
- 首頁

[首頁_pad.webm](https://github.com/user-attachments/assets/b5ab5b05-a9c6-406a-a0d0-c24fae3ab456)

- 門市據點

[門市_pad.webm](https://github.com/user-attachments/assets/85a51955-de5f-41de-9f49-ebd8f064880b)

- 部落格

[部落格_pad.webm](https://github.com/user-attachments/assets/7d2f2ae2-5103-4758-abe7-e439a1d3f570)

<br>

### 手機
- 首頁

[首頁_mobile.webm](https://github.com/user-attachments/assets/343ae79b-9adc-4e2d-b06c-b948179f0f94)

- 系列鏡框

[系列鏡框_mobile.webm](https://github.com/user-attachments/assets/708d23d9-90ae-4d02-9619-7a4bdb1647fb)

- 門市據點

[門市_mobile.webm](https://github.com/user-attachments/assets/3e956d92-fc15-4adb-b0b8-6c89578eeb32)

- 部落格

[部落格_mobile.webm](https://github.com/user-attachments/assets/f1777f60-d11e-492b-9bfc-26fdaad9a9f0)

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

✡️ 六角學院 2023 切版夏季班 - 第四週作業<br>
僅作為個人學習、作品集，無商業用途，設計稿版權屬六角學院。
