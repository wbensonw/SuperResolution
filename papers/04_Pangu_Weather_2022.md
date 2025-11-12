---
title_en: Pangu-Weather: A 3D High-Resolution Model for Fast and Accurate Global Weather Forecast
title_zh: 盤古天氣：三維高解析度、快速且準確的全球天氣預報模型
source: arXiv
date: 2022-11-03
link: https://arxiv.org/abs/2211.02556
topics: ["Global forecast", "Transformer (3DEST)", "ERA5", "0.25° grid"]
---

## 摘要（中英整合）
以3D Earth-Specific Transformer（3DEST）與分層時序聚合為核心，在0.25°網格與多變量（含T、Z、U、V等）上達到週內優勢，速度遠快於NWP，示範AI可與傳統數值預報競逐。

## 英文摘要（原文要點擷取）
下載43年ERA5逐時全球資料，訓練約2.56億參數的深度網路；以0.25°解析度提供預報。首次在所有變量與1小時至1週的時段上，以緯向加權RMSE與ACC超越最先進的數值天氣預報IFS。兩個關鍵策略：3DEST以立方資料表徵壓層/高度；階層式時間聚合減緩長序列累積誤差。支持極端天氣（颱風）與大集合。

## 問題設定與方法
- 任務：全球天氣預報，0.25°解析度，使用ERA5等資料長期訓練。
- 方法：3D Transformer表徵高度/壓層維度；時序聚合以減少累積誤差。

## 與本研究之關聯
- 雖非SR，但在多變量表徵、三維結構與長序列穩定性上具啟發。
- 可借鑒其多變量共同學習策略融入我方SR（T/Z/U/V）通道設計與長序列評估。

## 驗證清單
- 真實存在：是（arXiv:2211.02556）
- 與本研究相關：作為方法論延伸與未來方向參考


