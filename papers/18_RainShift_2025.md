---
title_en: Controlling Ensemble Variance in Diffusion Models: An Application for Reanalyses Downscaling
title_zh: 控制擴散模型的集合變異：用於再分析資料的降尺度應用
source: arXiv
date: 2025-01-21
link: https://arxiv.org/abs/2501.14822
topics: ["Diffusion", "Ensemble control", "Downscaling", "Uncertainty"]
---

## 摘要（中英整合）
提出以調整擴散步數/路徑的方式來控制擴散模型之集合變異，並將方法應用於再分析資料的降尺度；兼顧不確定度量化與分佈一致性。

## 英文摘要（原文要點擷取）
- Shows that ensemble variance in DDIM can be controlled via number of diffusion steps.
- Provides theoretical link between steps and variance; demonstrates benefits in reanalysis downscaling.
- Improves calibration/CRPS without sacrificing spatial structures.

## 與本研究之關聯
- 可直接用於我們的集合式 SR：透過步數/溫度調控生成多樣性，並配合五項物理正則與功率譜/秩直方圖評估，兼顧銳利度與校準度。

## 驗證清單
- 真實存在：是（arXiv:2501.14822）
- 相關性：高（擴散生成×不確定度控制×降尺度）

---
title_en: RainShift: A Benchmark for Precipitation Downscaling Across Geographies
title_zh: RainShift：跨地理區域的降水降尺度基準
source: arXiv
date: 2025-07-07
link: https://arxiv.org/abs/2507.04123
topics: ["Benchmark", "Geographic shifts", "GAN/Diffusion comparison", "Generalization"]
---

## 摘要（中英整合）
建立跨地理分佈轉移的降水降尺度資料集與評測，對GAN/擴散等方法作跨域泛化評估，指出僅擴大資料域仍不足以克服地域差異。

## 與本研究之關聯
- 我方可在ERA5子域做跨區域拆分，量化外推落差；並納入配準/對齊策略與物理正則減少域差距。

## 驗證清單
- 真實存在：是（arXiv條目）
- 相關性：高（跨域泛化基準）


