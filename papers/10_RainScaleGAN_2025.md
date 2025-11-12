---
title_en: RainScaleGAN: a Conditional Generative Adversarial Network for Rainfall Downscaling
title_zh: RainScaleGAN：用於降雨降尺度的條件式生成對抗網路
source: arXiv
date: 2025-03-17
link: https://arxiv.org/abs/2503.13316
topics: ["GAN", "Precipitation", "Downscaling", "Extreme events"]
---

## 摘要（中英整合）
提出RainScaleGAN，將0.25°降雨資料人工降為2°後再恢復，作為完美模式下的降尺度測試。結果顯示對空間結構與強度分佈具有良好恢復能力，超越經典方法。

## 英文摘要（原文要點擷取）
針對GCM水平解析度不足導致的在地降水模擬挑戰，提出條件式卷積GAN進行降尺度。於完美模式設定中，將0.25°×0.25°資料人工降至2°×2°後以RainScaleGAN恢復。模型相較文獻中領先方法表現更佳，生成之高解析度降水場在空間型態、強度統計與分佈上與真值高度一致。方法對基礎物理不設限，具擴展至風或氣溫等變量之潛力。

## 方法概覽
- Conditional GAN 架構，輸入粗解析度降雨，輸出高解析度分佈。
- 著重結構與統計分佈匹配，支援極端降雨場景。

## 與本研究之關聯
- 可作為生成式基線；我方可加入物理正則（散度/渦度/地轉）以降低不合理風場。

## 驗證清單
- 真實存在：是（arXiv:2503.13316）
- 相關性：高度相關（降雨降尺度）


