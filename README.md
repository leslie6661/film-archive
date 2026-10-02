# 底片檔案室 · Roll & Memo

個人底片記憶檔案館。首頁為完整單檔 `index.html`，包含七款暗盒素材與紀念標籤工坊。

## 發布到 GitHub Pages

1. 將此資料夾的 index.html、.nojekyll 和 README.md 放到儲存庫 main 分支根目錄。
2. 在儲存庫 Settings → Pages，選擇 Deploy from a branch。
3. 選擇 main 與 /(root)，按 Save。
4. 以 Pages 設定頁顯示的網址開啟網站。

## 後續更新

修改 index.html 並提交到 main，GitHub Pages 會重新發布；網址保持不變。也可以在原對話中提供儲存庫網址與修改需求，請助手更新同一份首頁。

每次發布先檢查新增膠卷、照片上傳、札記、自訂標籤與匯出。修改前備份資料，避免更動 IndexedDB 名稱及儲存結構；若必須變更，需設計資料遷移。

## 資料儲存

照片、膠卷與札記存在各個瀏覽器的 IndexedDB，不會上傳到 GitHub，也不會自動跨裝置同步。首次從本機 HTML 改用線上網址時，舊資料不會自動搬移。清除瀏覽器網站資料可能使記錄遺失。

目前素材庫的 JSON 匯出僅包含暗盒素材，並非完整照片與札記備份。
