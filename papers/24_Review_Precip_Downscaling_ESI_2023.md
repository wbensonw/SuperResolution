---
title_en: On the modern deep learning approaches for precipitation downscaling
title_zh: 當代深度學習降水降尺度方法綜述
source: Earth Science Informatics
date: 2023-xx-xx
link: https://link.springer.com/article/10.1007/s12145-023-00970-4
topics: ["Review", "Precipitation downscaling", "Methods & metrics"]
---

## 摘要（中英整合）
綜述降水降尺度領域的深度學習方法（CNN/GAN/擴散/Transformer）與評估指標，提供資料集、偏差與極端事件挑戰的全面性整理。

## 英文摘要（原文要點擷取）
- Reviews modern deep learning approaches for precipitation downscaling (CNNs, GANs, diffusion, Transformers).
- Summarizes datasets, evaluation metrics (RMSE/CRPS/spectrum/rank histograms), and challenges in extremes and bias.
- Discusses uncertainty quantification and spatio-temporal consistency for reliable climate applications.

## 詳解與前沿特點
這篇綜述對「極端/厚尾」、「跨尺度結構」、「時序一致」與「不確定度」四大主題均有系統化整理。對我們的 500hPa 變數 SR 而言，雖研究場域不同（降水 vs. 動力場），但在方法與評估層面高度共通：分佈/功率譜/秩直方圖的加入能避免只追逐 RMSE 的過平滑；在極端部分，建議採用高分位誤差與 CRPS 分解指標；在時序一致性上，強調多時段一致的訓練與驗證拆分。文章亦指出生成式方法（GAN/擴散）在恢復高頻與不確定度表徵方面的優勢，但需注意「過銳化」與校準度失衡，我們可以用五項物理約束配合 proper scoring rules 共同緩解。

## 與本研究之關聯
- 可用作Introduction素材與評估指標/資料分割策略參考。

## 驗證清單
- 真實存在：是（ESI 2023）
- 相關性：中高（總覽視角）


