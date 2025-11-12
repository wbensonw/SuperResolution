---
title_en: Wind Power Assessment based on Super-Resolution and Downscaling -- A Comparison of Deep Learning Methods
title_zh: 以超分辨與降尺度為基礎的風電評估：深度學習方法比較
source: arXiv
date: 2024-07-11
link: https://arxiv.org/abs/2407.08259
topics: ["Wind power", "ERA5", "Downscaling", "Super-resolution", "Evaluation"]
---

## 摘要（中英整合）
系統比較多種深度學習降尺度/超分辨方法（含生成式）對風速場與風能評估之影響；指出分布一致性（尤其高分位/尾端）與時空結構保真對風電指標（如容量因子）影響顯著，並提供跨資料集的實證評估。

## 英文摘要（原文要點擷取）
- Benchmarks multiple DL downscaling/SR approaches for wind power assessment from coarse reanalysis (e.g., ERA5).
- Evaluates not only RMSE but also distributional metrics and downstream energy metrics (capacity factor, site ranking).
- Highlights trade-offs between sharpness and calibration; stresses importance of tail fidelity for extremes.

## 與本研究之關聯
- 可用於驗證我方 U/V 風場 SR 品質：除 RMSE/ACC 外，加入風功率曲線與場址排序等下游指標；並檢查散度/渦度與地轉關聯是否受 SR 影響。

## 驗證清單
- 真實存在：是（arXiv:2407.08259）
- 相關性：高（風場應用驗證）


