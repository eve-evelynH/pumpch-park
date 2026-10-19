# 健打公園 PUMPCH PARK 

## 本地預覽

開啟 `index.html`；本版 CSS (`style.css`) 與 JS (`script.js`) 均為獨立檔案。請保持 `assets/` 資料夾結構不變。

## Phase 1 變更

- Dashboard 今日已健打改成無背景白字；移除右上角重複提示。
- 未擊倒怪物僅顯示名稱。
- 圖鑑內容可捲動且頁尾按鈕不遮擋。
- 回到公園維持第二層底部按鈕；第三層返回上一頁。
- Loading 單次 1 秒。
- 修正底圖縮放、下拉選單箭頭內距、Locked 文字陰影、部分按鈕顏色、名字置中。
- 保留既有 localStorage 儲存鍵 `pumpchPark.v1`，不重置使用者資料。

## GitHub Pages

將 `index.html`、`style.css`、`script.js` 及 `assets/` 上傳到同一 repository 的根目錄，Settings → Pages → Deploy from a branch → main / (root)。之後覆蓋同名檔案並 Commit，原網址會維持不變。

## 圖片說明

圖片路徑以程式中的 `assets/...` 為準。請將自己的 PNG/JPG 放到同路徑同檔名，或修改 CSS / JS 對應路徑，不需要修改 Figma 原始圖層命名。大圖片可在保持品質下進行 WebP/尺寸壓縮以加速載入。


## Color fix (2026-10-19)
- Setup background and loading background `#40416D`.
- Setup input label and character prompt `#FFFFFF`; input placeholder `請輸入使用者名稱`.
- Setup note `#B1B1B1`.
- Book header shows only `角色圖鑑` or `怪物圖鑑` and the applicable arrow; no date heading.
- All CSS and JavaScript remain in separate files. Existing localStorage data key is unchanged.
