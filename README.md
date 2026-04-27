# 老人的白板 (Old Man's Whiteboard)

一個輕量、流暢且功能強大的網頁數位白板工具。本專案採用原生 HTML5 Canvas 與 JavaScript 開發，搭配 Tailwind CSS 打造現代化介面，旨在提供極致簡單卻功能齊全的創作體驗。

## 🌟 核心特色

完全離線且隱私：單一 HTML 檔案即可運行，所有繪圖數據均儲存在瀏覽器本地快取（LocalStorage），保護隱私。
強大的圖形編輯：
    自由旋轉與縮放：物件選取後可進行 360 度旋轉，圖片與形狀支援自由縮放。
    套索工具 (Lasso)：支援選取區域內的物件，方便進行群組移動或批次刪除。
    圖層管理：內建「移至最前/最後」與「上移/下移一層」功能，精準控制物件遮蓋關係。
進階文字系統：
    支援 項目符號 (•)與 自動數字列表 (1.)。
    支援多層級縮排（使用 Tab 鍵），並能自動重新計算列表編號。
    支援文字對齊（左、中、右）與字體大小動態調整。
豐富的繪圖工具：
    螢光筆 (Highlighter)：半透明筆觸，具備自動疊色效果。
    雷射筆 (Laser Pointer)：動態漸隱軌跡，適合簡報與展示用途。
    智慧形狀：矩形、菱形、橢圓（支援圓角設定）、箭頭與直線。
專案存檔與匯出：
    支援匯出為 .json 專案檔，方便下次匯入繼續編輯。
    支援匯出為 .png 圖片。
    自動恢復：重新整理頁面後，畫布內容、縮放比例與視角位置會自動恢復。

## ⌨️ 鍵盤快速鍵 (Hotkeys)

本專案配置了高效的快速鍵系統，讓操作更加流暢：

### 工具切換
`1`：選取 (Select)
`2`：矩形 (Rectangle)
`3`：菱形 (Diamond)
`4`：橢圓 (Ellipse)
`A`：箭頭 (Arrow)
`S`：直線 (Line)
`D`：畫筆 (Pencil)
`H`：螢光筆 (Highlighter)
`T`：文字 (Text)
`L`：套索 (Lasso)
`F`：雷射筆 (Laser Pointer)
`E`：橡皮擦 (Eraser)

### 物件屬性與操作
線條粗細：`Q` (最細) / `W` (中等)。
快速選色：`R` (紅) / `G` (綠) / `B` (藍) / `Y` (黃)。
快速複製：按住 `Ctrl` / `Cmd` 並拖位物件。
軸向鎖定：畫線或移動物件時按住 `Shift` 可鎖定水平/垂直方向。
刪除物件：`Delete` 或 `Backspace`。

### 畫布操作
平移畫布：按住 `空白鍵`、`滑鼠滾輪` 或 `右鍵` 拖曳。
縮放畫布：按住 `Ctrl` / `Cmd` 並捲動滑鼠滾輪，或使用平板雙指撥弄。
復原/重做：`Ctrl+Z` / `Ctrl+Y`。

## 🚀 互動技巧

1.  貼上素材：直接從剪貼簿 `Ctrl+V` 貼上圖片或文字，系統會自動優化顯示尺寸。
2.  右鍵選單：在畫布長按（行動裝置）或點擊右鍵可呼叫選單進行貼上功能。
3.  清單縮排：在文字編輯模式下，使用 `Tab` 增加縮排，`Shift+Tab` 減少縮排，系統會自動轉換項目符號。

## 🛠️ 技術細節

前端框架：Tailwind CSS
渲染引擎：HTML5 Canvas API
本地存儲：LocalStorage API
兼容性：支援各類現代瀏覽器及行動裝置觸控操作

## 贊助這個專案
✨ 喜歡這個專案嗎？ ✨
如果這個工具為你節省了時間 ⏱️，或者對你的研究有所啟發 💡
🧋 點擊圖示請我喝杯珍奶吧 🧋

[![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(點擊珍奶圖示贊助作者)

## 📝 免責聲明

本專案為個人開發工具，旨在提供便利的數位雙生繪圖體驗。本軟體不收集任何使用者資訊，所有繪圖數據皆保留在使用者本端裝置中。
