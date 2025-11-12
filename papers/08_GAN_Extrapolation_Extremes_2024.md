---
title_en: On the Extrapolation of GANs for Downscaling Precipitation Extremes in Warmer Climates
title_zh: 在更暖氣候下GAN用於降尺度極端降水的外推能力研究
source: arXiv (GRL 2024)
date: 2024-09-20
link: https://arxiv.org/abs/2409.13934
topics: ["GAN", "Precipitation extremes", "Extrapolation", "Climate change"]
---

## 摘要（中英整合）
比較GAN與CNN在更暖氣候（分佈外）之降尺度外推能力，指出生成式方法在極端降水的分佈匹配與外推表現上之挑戰與改善方向。

## 英文摘要（原文要點擷取）
評估一個確定性的CNN基線與建立在該基線上的GAN，兩者皆訓練於RCM模擬的日降水。兩者對年平均降水變化的擬合良好，但對極端（99.5百分位）更為關鍵：RCM顯示暖化每攝氏度約+5.8%的升幅；若在未來氣候上訓練，GAN能擷取97%的升幅（CNN 65%）；即便GAN只在歷史氣候上訓練也能擷取77%。結論：GAN對極端降水的降尺度具有更佳外推泛化。

## 問題設定與方法
- 任務：降尺度極端降水，並評估分佈外（暖化）外推表現。
- 方法：GAN vs. CNN的對比實驗，搭配暖化場景資料。

## 與本研究之關聯
- 我方可在ERA5子域以「暖季/暖區」做外推測試，並加入物理正則（散度/渦度/地轉/熱力/非地轉風）觀察外推穩健性。

## 驗證清單
- 真實存在：是（arXiv:2409.13934；期刊為GRL 2024）
- 與本研究相關：高度相關（外推與極端事件）


