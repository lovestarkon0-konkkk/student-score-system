# 學生成績管理系統 Lite

這是一個給 GitHub 新手使用的單頁式成績管理網站。

## 功能
- 新增學生成績
- 自動計算平均總分
- 自動判斷及格 / 未及格
- 修改、刪除成績
- 搜尋姓名、院所 / 班級、課程
- 統計總筆數、及格、未及格、平均分數
- 匯出 Excel (.xlsx)
- JSON 備份與還原

## 重要：資料存在哪裡？
目前版本使用瀏覽器 localStorage。
也就是資料存在「你目前使用的瀏覽器」中，不會自動同步到其他電腦。

因此建議：
1. 定期按「匯出 Excel」
2. 定期按「備份資料 JSON」

如果未來希望多人共用、跨電腦同步、帳號登入，可以再升級 Firebase / Supabase 雲端資料庫版本。

## GitHub Pages 上線
1. 登入 GitHub
2. 建立新的 repository，例如 `student-score-system`
3. 把 `index.html` 上傳到 repository 根目錄
4. Repository → Settings → Pages
5. Build and deployment / Source 選擇 `Deploy from a branch`
6. Branch 選 `main`，資料夾選 `/(root)`
7. Save
8. GitHub 會顯示你的網站網址

## Excel
本系統使用 SheetJS Community Edition 0.20.3 的瀏覽器版本：
https://cdn.sheetjs.com/xlsx-0.20.3/package/dist/xlsx.full.min.js
