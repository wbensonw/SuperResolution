---
title_en: A Generative Deep Learning Approach to Stochastic Downscaling of Precipitation Forecasts
title_zh: 生成式深度學習的降水預報隨機降尺度方法
source: arXiv (JAMES 2022)
date: 2022-07-28
link: https://arxiv.org/abs/2204.02028
topics: ["Precipitation", "Stochastic downscaling", "Generative", "Benchmarks"]
---

## 摘要（中英整合）
提出生成式深度學習框架以進行降水預報的隨機降尺度，旨在更好刻畫降水場的不確定性與空間細節，並與多種基線方法比較。

## 英文摘要（原文要點擷取）
降水預報仍存在準確度與可靠性問題，關鍵過程常低於全球模式解析尺度。本文將GAN/VAE-GAN用於「從較低解析度的預報場生成高解析度降水地圖」，一方面補足解析度與結構，另一方面面對非可忽略的預報誤差。結果顯示，相較先進的點位後處理方法，生成式方法能匹配其統計特性，同時產生高解析度且空間連貫的降水圖，並在像素/CRPS/功率譜/秩直方圖等指標上具競爭力，包含強降雨情境。

## 問題設定與方法
- 任務：將低解析度降水預報轉為高解析度，保留不確定性特質。
- 方法：生成式模型（非單一點估計），兼顧分佈與細節。

## 與本研究之關聯
- 可為我方提供「機率化SR」評估基準（分位數、分佈距離），與物理正則聯動。

## 驗證清單
- 真實存在：是（arXiv:2204.02028；期刊為JAMES 2022）
- 與本研究相關：高度相關（降水SR與隨機性）


