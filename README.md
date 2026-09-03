# 統計學（一）教學網站：B 方案

所有教材直接放在 `materials`，不需要建立 Week01、Week02 子資料夾。

## 日後新增教材只做兩件事
1. 把檔案放進 `materials`
2. 打開根目錄的 `materials.json`，在對應週次填「完整檔名＋副檔名」

例如：
```json
"01": {
  "main": "Week01.pptx",
  "supplement1": "Week01_補充練習.pdf",
  "supplement2": "第一週資料.xlsx"
}
```

- 主要教材已預設為 `Week01.pptx`、`Week02.pptx`……。
- 補充教材檔名沒有規定，PDF、DOCX、XLSX、CSV 等皆可。
- 空白 `""` 會在網站顯示「尚無檔案」。
- 網站不是看到檔名含 Week01 就自動辨識；以 `materials.json` 的設定為準。
- PPT/PPTX 按鈕會另開分頁，以 Microsoft Office Web Viewer 線上播放。
- Office Web Viewer 需等網站部署在公開 HTTPS（例如 GitHub Pages）後才能正常讀取投影片。
