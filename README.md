# 鏡界裂痕｜威爾第二階段走位訓練器

這是一個原創視覺的單頁網頁遊戲練習版。`index.html` 內含 HTML、CSS、JavaScript；圖片等素材獨立放在 `assets/`，可直接部署到 GitHub Pages。

## 本機預覽

1. 將整個 `will-phase2-trainer` 資料夾解壓縮。
2. 直接用瀏覽器開啟 `index.html`。如果瀏覽器限制本機 SVG 圖片載入，可在該資料夾執行簡易靜態伺服器，或直接部署到 GitHub Pages。
3. 點選「開始練習」。

## 操作

- `←` / `→` 或 `A` / `D`：左右移動。
- `P` 或 `Esc`：暫停／恢復。
- `R`：重新開始目前挑戰。
- 亦可點擊地板位置讓角色移動到對應區域；手機提供左右觸控按鈕。

## 素材結構

```text
will-phase2-trainer/
├── index.html
├── README.md
└── assets/
    ├── character/  # 自訂角色（見 assets/character/README.md）
    ├── scene/      # 原創場景 SVG
    ├── spider/     # 原創蜘蛛腳 SVG
    ├── effects/    # 原創效果 SVG
    └── audio/      # 音效說明
```

## 自訂角色

把你有權使用的透明 PNG 放到 `assets/character/`，檔名需符合 `player-idle.png`、`run-1.png` 到 `run-6.png`，以及選用的 `player-hurt.png`。遊戲自動載入存在的影格；未提供時會使用內建的原創占位角色。

## GitHub Pages 部署

1. 建立一個 GitHub repository。
2. 上傳 `index.html`、`README.md` 與整個 `assets/` 資料夾，保留目錄結構。
3. 在 repository 的 **Settings → Pages**，選擇由 `main` 分支的根目錄（`/(root)`）部署。
4. 等待 GitHub Pages 完成部署後，使用顯示的網址測試角色、背景、按鍵操作與所有按鈕。

## 關於機制與素材

本作品為非官方個人練習專案，與 NEXON 或《楓之谷 M》無隸屬、合作或背書關係。畫面與蜘蛛腳圖形是為本專案繪製的原創素材；遊戲的攻擊次數、倒數等為可調式訓練參數，應依你實際想練習的版本核對調整。
