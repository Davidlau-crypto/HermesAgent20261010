# Workbench — 單一儲存庫

集中存放所有工具與報告，透過 GitHub Actions 自動部署到 GitHub Pages。

## 內容

| 路徑 | 內容 |
|---|---|
| `index.html` | 工作台首頁（入口） |
| `todo.html` | 待辦清單應用（單一 HTML、localStorage） |
| `dashboard.html` | 銷售數據儀表板（資料來源：Dashboard_Data.xlsx，99 張發票） |

## 部署

每次 push 到 `main`，`.github/workflows/deploy.yml` 會自動發佈到 GitHub Pages。

## 備註

- 全部為靜態檔案，無後端、無建置步驟、無外部資源。
- 儀表板資料僅取自來源試算表；來源未標示幣別，畫面不假設任何貨幣單位。
