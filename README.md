# storyboard-assets

這個 repo 是 `storyboard-proposal-template-gas` 的 GitHub Pages 素材庫，用來存放分鏡提案頁會引用的圖片素材。

它不是核心程式專案，而是工作流支援素材。圖片 URL 會被 Google Sheet 或分鏡提案頁讀取，因此路徑穩定性比整理美觀更重要。

## 專案定位

- 保存分鏡提案頁需要公開讀取的圖片素材。
- 透過 GitHub Pages 提供穩定圖片 URL。
- 主要搭配 `02_工作流\storyboard-proposal-template-gas` 使用。
- 不作為授權不明素材、臨時輸出、大量原始圖或私人素材的倉庫。

## 目前結構

| 路徑 | 用途 |
| --- | --- |
| `.nojekyll` | 讓 GitHub Pages 直接提供靜態檔案。 |
| `projects/` | 依專案存放素材。 |
| `projects/toa100/` | 目前 TOA100 範例素材。 |
| `projects/toa100/cover/` | 封面圖。 |
| `projects/toa100/main/` | 主分鏡圖片。 |

## 使用規則

- 不要任意搬移、重新命名或刪除既有圖片。
- 圖片路徑可能已被 Google Sheet、提案頁或外部 demo 引用。
- 新素材應放入對應 `projects/{projectId}/` 底下。
- 檔名應保持簡短、可排序、可穩定引用。
- 若需要替換素材，優先新增版本或先確認引用位置。

## 安全與授權

- 不提交未授權圖片、客戶敏感素材或私人素材。
- 不提交含有個資、合約、報價或未公開品牌資訊的圖片。
- 不提交 API key、token、密碼或環境變數。
- 大型素材或大量輸出應先評估是否適合 GitHub 管理。

## 下一步

- 補目前 GitHub Pages URL。
- 盤點每個 `projectId` 對應的 Sheet / 提案頁。
- 檢查圖片容量與授權狀態。
- 建立新增素材前的最小檢查清單。
