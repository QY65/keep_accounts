# 📊 互動式財務管理與視覺化系統 (Web-based Expense Tracker)

這是一個基於 Python 開發的輕量級、互動式網頁版記帳系統。本專案作為期中專案提交，旨在解決傳統終端機 (CLI) 記帳操作繁瑣，以及 Excel 記帳缺乏即時視覺化圖表的痛點。

![系統畫面]<img width="1397" height="751" alt="image" src="https://github.com/user-attachments/assets/317f2a01-eb61-48de-8048-cb4ab8c8621b" />

## 🔗 系統測試網址
可以直接點擊下方連結進入系統進行操作測試：
👉 **[點此進入記帳系統](https://colab.research.google.com/drive/1ITiIgxzpoFUX34kS-YGGvHs93dh0eWSK?usp=sharing)**

## ✨ 核心亮點功能
* **🖥️ 現代化網頁介面 (Gradio)：** 捨棄傳統黑底白字的終端機，提供使用者友善的 Web UI。
* **📝 直覺編輯體驗：** 支援「雙向資料綁定」，使用者可直接在網頁表格上雙擊修改歷史紀錄，系統會自動將修改內容同步至 CSV 並即時重繪圖表。
* **📈 互動式圓餅圖 (Plotly.express)：** 完美解決 Colab 雲端環境常見的中文亂碼問題，圖表具備滑鼠互動功能，並自動計算「結餘」渲染於圖表中。
* **💾 安全的資料持久化：** 所有紀錄自動儲存為 `expenses.csv` (utf-8-sig 編碼)，確保 Excel 開啟無亂碼。

## 🛠️ 技術棧 (Tech Stack)
* **Python 3.x** - 核心開發語言
* **Pandas** - 負責 DataFrame 資料清洗與 CSV 讀寫
* **Gradio** - 負責建構網頁前端介面與事件綁定 (Event Binding)
* **Plotly.express** - 負責繪製具備動態提示框的高質感圖表

## 📂 專案檔案結構
* `Untitled5.ipynb`：主程式碼 (Google Colab 筆記本檔)
* `expenses.csv`：記帳資料庫 (執行程式後自動生成)
* `README.md`：專案說明文件

## 👨‍💻 作者
* 莊鈞硯 114104117@gms.tcu.edu.tw
* 黃聿騏 114104120@gms.tcu.edu.tw
