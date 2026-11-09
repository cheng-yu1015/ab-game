# 幾 A 幾 B 四版本（數位科技概論第一節課作業）
- index.html：上傳 GitHub 的主頁，四個分頁都能直接玩
- my-v1、my-v2：單檔版本（作業繳交）
- my-v3、my-v4：Code.gs、Index.html、appsscript.json（貼進各自的 Google Apps Script 專案）
- 各資料夾「驗收紀錄.txt」：自動化測試結果已填；真實 Google 環境項目請自己測完勾選

## 重要：Code.gs 有更新，要重新部署一次
my-v3、my-v4 的 Code.gs 多了「允許被嵌入網頁」的一行，GitHub 頁面才能直接顯示雲端版遊戲。
做法（兩個專案都要）：把新的 Code.gs 貼進 GAS 取代舊的 → 存檔 →
部署 → 管理部署 → 編輯（鉛筆）→ 版本選「新版本」→ 部署。網址不變，資料不會消失。
