# DTAI Dataset：牆面缺損影像資料集

🎯 DTAI 課程專題「WallGuard 牆面危害 AI 辨識系統」的訓練資料，共 3,000 張室內牆面照片，分成三類各 1,000 張。

| 資料夾 | 類別 | 張數 |
|---|---|---|
| `crack/` | 裂縫 | 1,000 |
| `efflorescence/` | 壁癌 | 1,000 |
| `concrete/` | 混凝土剝落與鋼筋外露 | 1,000 |

- **來源：** Roboflow Universe 上的公開資料集，包含 DeepCrack、CRACK500 等公開裂縫資料集；授權依各原始資料集為準。
- **用途：** 訓練 WallGuard 的影像分割模型（U-Net），標出照片中多種牆損的位置與範圍。
- **取得方式：** `dataset.zip` 以 Git LFS 儲存，clone 後執行 `git lfs pull`。
- **相關專案：** [WallGuard 專案頁](https://yunyu-web-digital-profile.vercel.app/projects/wallguard)
