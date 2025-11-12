---
title_en: EnScale: Temporally-consistent multivariate generative downscaling via proper scoring rules
title_zh: EnScale：以合適評分規則實現時序一致的多變量生成式降尺度
source: arXiv
date: 2025-09-30
link: https://arxiv.org/abs/2509.26258
topics: ["Generative", "Proper scoring rules", "Temporal consistency", "Multivariate"]
---

## 摘要（中英整合）
提出兩步驟生成式框架：先校正GCM與coarsened RCM之偏差，再進行超分辨率生成；以Energy score等proper scoring rule訓練，兼顧多變量一致與時序一致。

## 方法概覽
- 多GCM↔RCM對應的生成學習，降低域差異。
- EnScale-t 版本強化時間一致。

## 英文摘要（原文要點擷取）
- Introduces EnScale/EnScale-t to emulate RCMs and generate high-resolution multivariate fields with temporal consistency.
- Trains with proper scoring rules (e.g., energy score, variogram score) to ensure joint distributional fidelity across variables and time.
- Achieves state-of-the-art distributional metrics versus baselines while being far more efficient than full RCM runs.
- Demonstrates generalization across GCM forcings and regions, enabling large-ensemble downscaling.

## 詳解與前沿特點
EnScale 的關鍵在「多變量×時間一致」的生成式設計，並以 proper scoring rules 直接監督「分佈」而非僅像素誤差。這使其在捕捉跨變數（如 T/Z/U/V 之間）的協方差結構與時間連貫性上更可靠，亦與我們的五大物理約束互補：地轉與熱力關聯本質上即是跨變數結構，時間一致也能降低逐時預報的非物理跳動。此外，EnScale 的兩步驟（偏差校正→SR生成）對我們的 3× 放大流程具可移植性：可先以簡化物理/統計方法做 bias-correction，再進入 CNN/擴散頭做 SR，並同時引入物理正則以穩住高頻。

## 與本研究之關聯
- 我方多通道（T/Z/U/V）可直接參考其多變量一致性評分；於SR物理正則之外，加上proper scoring監督。

## 驗證清單
- 真實存在：是（arXiv條目）
- 相關性：高度相關（多變量/時間一致/生成式）


