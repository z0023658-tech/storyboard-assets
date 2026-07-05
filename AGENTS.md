# AGENTS.md

## Repo Purpose

本 repo 是 `storyboard-proposal-template-gas` 的 GitHub Pages 素材庫，用來提供分鏡提案頁引用的公開圖片 URL。

它是工作流支援素材 repo，不是核心工具程式，也不是大量輸出或未整理媒體檔的倉庫。

## Must-read Files

- `README.md`
- `AGENTS.md`

若任務涉及某個專案素材，先確認對應 `projects/{projectId}/` 目錄與引用路徑。

## Project-specific Boundaries

- 不任意搬移、重新命名、刪除或覆蓋既有素材，因為路徑可能已被 Google Sheet、提案頁或 demo 引用。
- 不自動壓縮、轉檔、裁切或改格式。
- 不提交未授權素材、客戶敏感素材、私人素材或含個資圖片。
- 不提交大量原始輸出、模型檔或不適合 GitHub Pages 管理的大型媒體。
- 不修改 `storyboard-proposal-template-gas`，除非使用者明確要求。

## Build / Test / Validation

- 本 repo 沒有 build 流程。
- 素材或路徑修改後，檢查：
  - 檔案仍在預期的 `projects/{projectId}/` 底下。
  - GitHub Pages URL 規則沒有被破壞。
  - 可能引用該素材的 Sheet / 提案頁需要被標記為待測。

## Directory Notes

- `.nojekyll`：讓 GitHub Pages 直接提供靜態檔案。
- `projects/`：依專案存放素材。
- `projects/toa100/`：目前 TOA100 範例素材。
- `projects/toa100/cover/`：封面圖。
- `projects/toa100/main/`：主分鏡圖片。

## Known Traps

- 路徑穩定性比整理美觀重要。
- 看似未使用的圖片，可能已被 Google Sheet 或外部 demo URL 引用。
- 替換素材前，優先新增版本或先確認引用位置。
