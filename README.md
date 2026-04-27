# 老人的白板 (Old Man's Whiteboard)

一個輕量、流暢且功能強大的網頁數位白板工具。本專案深受 Excalidraw 啟發，採用原生 HTML5 Canvas 與 JavaScript 開發，並搭配 Tailwind CSS 打造現代化介面。

## 🌟 核心特色

完全離線且隱私：單一 HTML 檔案即可運行，不需後端伺服器，所有繪圖數據均儲存在瀏覽器本地快取。
強大的互動體驗：
    自由旋轉：點擊物件後可進行 360 度自由旋轉。
    快速複製：按住 `Ctrl` / `Cmd` 並拖動物件即可直接複製。
    軸向鎖定：移動物件或畫線時，按住 `Shift` 可鎖定水平或垂直方向。
    文字編輯：支援雙擊已完成的文字方塊進入修改模式。
智慧記憶功能：具備自動存檔邏輯，重新整理頁面後，畫布內容、縮放比例與視角位置皆會自動恢復。
無縫素材貼上：支援直接從剪貼簿貼上圖片或文字，並自動優化圖片顯示尺寸。
雷射筆工具：內建動態漸隱的雷射筆功能，適合簡報與展示用途。

## ⌨️ 鍵盤快速鍵 (Hotkeys)

本專案配置了極致高效的快速鍵系統，讓你能像操作專業設計軟體一樣流暢：

### 工具切換
`1`：選取工具 (Select)
`2`：矩形 (Rectangle)
`3`：菱形 (Diamond)
`4`：橢圓 (Ellipse)
`A`：箭頭 (Arrow)
`S`：直線 (Line)
`D`：畫筆 (Pencil)
`T`：文字 (Text)
`F`：雷射筆 (Laser Pointer)
`0`：橡皮擦 (Eraser)

### 物件屬性
線條粗細：`Q` (最細) / `W` (中等) / `E` (最粗)
邊框顏色：`R` (紅) / `G` (綠) / `B` (藍) / `Y` (黃)
刪除物件：選取物件後按 `Delete` 或 `Backspace`

### 畫布操作
平移畫布：按住 `空白鍵` 或 `滑鼠右鍵` 拖曳，亦可直接使用滑鼠滾輪。
縮放畫布：按住 `Cmd` (Mac) 或 `Ctrl` (Win) 並捲動滑鼠滾輪。
復原/重做：`Ctrl+Z` / `Ctrl+Y`。

## 🚀 如何使用

1.  點擊 https://eledgetw.github.io/whiteboard/ 即可操作。
2.  使用任何現代瀏覽器 (Chrome, Edge, Safari, Firefox) 皆可直接開啟。
3.  開始創作！完成後可點擊右上角的「匯出圖片」按鈕存檔。

## 🛠️ 技術細節

前端框架：Tailwind CSS (CDN)
渲染引擎：HTML5 Canvas API
圖形演算法：包含碰撞偵測 (Hit Testing)、座標空間變換 (Coordinate Transformation) 與二次貝茲曲線渲染。
本地存儲：LocalStorage API。

## 贊助這個專案
✨ 喜歡這個專案嗎？ ✨
如果這個工具為你節省了時間 ⏱️，或者對你的研究有所啟發 💡
🧋 點擊圖示請我喝杯珍奶吧 🧋

[![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(點擊珍奶圖示贊助作者)
這能讓程式碼持續穩定運行，也讓更多靈感不斷湧現！✨


## 📝 免責聲明

本專案為個人開發工具，旨在提供便利的數位雙生繪圖體驗。本軟體不收集任何使用者資訊，所有繪圖數據皆保留在使用者本端裝置中。
