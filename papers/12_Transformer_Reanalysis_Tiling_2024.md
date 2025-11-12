---
title_en: Transformer based super-resolution downscaling for regional reanalysis: Full domain vs tiling approaches
title_zh: 區域重分析的Transformer超分辨率降尺度：全域 vs 瓦片化
source: arXiv
date: 2024-10-16
link: https://arxiv.org/abs/2410.12728
topics: ["Transformer", "CERRA", "ERA5", "Downscaling", "Tiling"]
---

## 摘要（中英整合）
比較全域與瓦片化輸入策略，在CERRA（5.5 km）為目標、ERA5為驅動之情境下，Swin Transformer優於多數基線，瓦片化在可擴展性與跨域可移植性上具優勢。

## 英文摘要（原文要點擷取）
以CERRA地表氣溫為目標，從驅動ERA5溫度進行SR降尺度；主體方法為Swin Transformer，與U-Net、DeepESD及雙三次插值比較。提出兩種策略：全域一次性輸入 vs. 將全域切成瓦片（瓦片方案加入靜態地形）。瓦片化需要空間可轉移性，平均表現略低於全域但仍優於部分基線，提供可在泛歐洲尺度與即時應用上的高效解法。

## 方法概覽
- Swin Transformer 與 U-Net/DeepESD 比較。
- 瓦片化結合地形靜態特徵，提升泛化與效率。

## 與本研究之關聯
- 我方可嘗試瓦片化訓練，加上地形/海陸/高程等輔助通道，並保留物理約束於內域（避開邊界）。

## 驗證清單
- 真實存在：是（arXiv:2410.11564）
 - 真實存在：是（arXiv:2410.12728）
- 相關性：高度相關（Transformer式SR/降尺度）


