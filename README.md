# Bootstrap 學生操作說明

1. 先解壓縮全部檔案，用 VS Code 開啟 student 資料夾。
2. 從 00-start/index.html 開始，另存副本或複製整個階段資料夾為 my-work，仍放在 student 內。
3. 雙擊 HTML 可在瀏覽器預覽。儲存後重新整理。也可使用已安裝的 Live Server。
4. 01-layout、02-components、03-complete 分別是三節完成版。
5. snippets.html 提供可複製的完整片段，assets/text-materials.md 提供文字。
6. 每個階段都以 ../assets 讀取共用素材，請保留整個 student 資料夾。
7. 若將檔案移到別處，請一併調整路徑。不要直接修改 Bootstrap vendor 檔案。
8. 表單只做本機檢查，不寄送或儲存。使用虛構資料練習。
9. 375px、768px、1280px 驗證欄數為 1、2、3。

## 修改順序

STEP 1-A 載入 CSS → STEP 1-B 網格與圖片 → STEP 2-A Card → STEP 2-B Navbar → STEP 2-C 表單 → STEP 3-A Flex → STEP 3-B Modal → STEP 3-C CSS。

## 常見問題

- 樣式不見：檢查 link 是否仍在註解內、href 相對路徑與檔案位置。
- 圖片不見：保留 assets/images，檢查大小寫與檔名。
- 選單不動：檢查 Bundle script、data-bs-target 與 id。
- 頁面過寬：檢查 img-fluid、固定寬度、row 外層 container。
- 手機模擬的寬度不同：DevTools 用 CSS pixel，測試時瀏覽器縮放維持 100%。
