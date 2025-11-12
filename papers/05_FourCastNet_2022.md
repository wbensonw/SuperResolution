---
title_en: FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators
title_zh: FourCastNet：以自適應傅立葉算子為核心的全球高解析度資料驅動天氣模型
source: arXiv
date: 2022-02-22
link: https://arxiv.org/abs/2202.11214
topics: ["Fourier Neural Operator", "Global forecast", "ERA5", "0.25° grid"]
---

## 摘要（中英整合）
利用傅立葉神經算子達到高速、高解析度的全球短中期預報，在多變量（含風場、降水、水氣）上展現優勢，並支援快速大集合模擬。

## 英文摘要（原文要點擷取）
FourCastNet 是以 Fourier Neural Operator 為核心的全球資料驅動預報模型，在 0.25° 解析度提供短中期預測。對大尺度變量與複雜細節變量（如降水）均具競爭力，短時效甚至優於IFS；能在2秒內生成週長預報，利於大量集合提高機率預報能力。

## 問題設定與方法
- 任務：全球0.25°預報，注重高頻結構的恢復。
- 方法：頻域學習（FNO）＋高效推論，兼顧準確與速度。

## 與本研究之關聯
- 非SR，但頻域學習思路可應用於我方SR網路（例如在物理約束之外，引入頻帶損失/頻譜正則化）。

## 驗證清單
- 真實存在：是（arXiv:2202.11214）
- 與本研究相關：方法論延伸（頻域正則/損失設計）


