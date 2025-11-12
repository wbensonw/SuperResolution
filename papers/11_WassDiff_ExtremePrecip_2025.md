---
title_en: Downscaling Extreme Precipitation with Wasserstein Regularized Diffusion
title_zh: 以Wasserstein正則化擴散模型進行極端降水降尺度
source: arXiv; IEEE TGRS (2025)
date: 2024-10-01
link: https://arxiv.org/abs/2410.00381
topics: ["Diffusion", "Wasserstein", "Precipitation extremes", "Downscaling"]
---

## 摘要（中英整合）
提出 WassDiff：於條件式擴散模型中引入 Wasserstein 分佈匹配正則，直接對齊降水分佈（含厚尾），顯著改善極端降水的強度偏差與形態再現，兼顧整體分布一致性與局地高峰。於多個資料集與區域上，相較既有降尺度/生成基線，在 CRPS、極端分位誤差與功率譜等指標取得穩健優勢。

## 方法概覽
- 兩段式擴散：條件化生成與Wasserstein正則同時優化。
- 極端統計的偏差校正內融於生成過程。

## 英文摘要（原文要點擷取）
- Propose Wasserstein-regularized conditional diffusion for precipitation downscaling to better match heavy-tailed distributions.
- Improves extremes (high quantiles) while preserving spatial structures; yields better CRPS, power spectra, and rank histograms than baselines.
- Demonstrates robust gains across regions and seasons; supports stochastic ensembles for uncertainty.
- Validates on reanalysis/observations with emphasis on tail fidelity and spatial coherence.

## 詳解與前沿特點
本作切中降水「重尾分佈」的核心痛點：典型 L1/L2 或僅憑對抗學習，常在極端降水量級出現系統性低估。WassDiff 透過在擴散過程中加入 Wasserstein 正則，直接以「機率分佈對齊」為目標，讓模型在學習低中量級統計的同時，不犧牲高分位尾端。此種分佈導向的訓練策略，與我們關注的物理一致性相輔相成：空間結構（如鋒面、對流胞）得以保真，高頻譜能量回補更自然。此外，擴散模型的樣本多樣性使得集合式預報（不確定度評估）變得實用而可信。在指標層面，作者不僅看 RMSE/CRPS，亦重視功率譜與秩直方圖，確保從尺度能量到校準度皆不偏廢；這種「多視角評估」非常值得我們在 500hPa T/Z/U/V 超分辨中借鑑。

## 與本研究之關聯
- 我方可沿用擴散生成頭，並疊加地轉/散度/渦度/非地轉風/熱力等物理約束，提升外推穩健性。

## 驗證清單
- 真實存在：是（arXiv:2410.00381；期刊版本：IEEE TGRS 2025）
- 相關性：高度相關（極端/生成式/降尺度）


