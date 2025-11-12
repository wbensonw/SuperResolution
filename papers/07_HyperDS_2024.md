---
title_en: Observation-Guided Meteorological Field Downscaling at Station Scale: A Benchmark and a New Method
title_zh: 觀測引導的站點尺度氣象場降尺度：基準與新方法（HyperDS）
source: arXiv
date: 2024-01-22
link: https://arxiv.org/abs/2401.11960
topics: ["Downscaling", "Benchmark", "Hypernetwork", "Station-scale"]
---

## 摘要（中英整合）
提出站點尺度（station scale）的氣象降尺度基準與資料集，並提出超網路架構HyperDS，有效融合觀測訊息，支援跨尺度的連續建模與評測。

## 英文摘要（原文要點擷取）
傳統以格網高解析度作監督的CV式降尺度，難以對齊連續分佈特性，導致與站點觀測間的系統性偏差。本文將降尺度擴展到任意分佈站點尺度，建立全新基準與資料集，並受同化啟發將觀測作為多尺度先驗融入模型。提出基於超網路的 HyperDS，能有效整合不同觀測信息，進行連續尺度建模；在多個地表變數上顯著優於基線（例：風速MSE改善67%、地面氣壓19.5%）。

## 問題設定與方法
- 任務：從較粗格網場降尺度到站點尺度輸出，納入觀測引導。
- 方法：超網路（HyperNetwork）生成特定條件的子網路權重，提高在不同站點/分佈下的泛化。

## 與本研究之關聯
- 對「區域/站點泛化」與「觀測約束」有啟發，可結合我方物理約束形成「物理+觀測」雙重一致性。

## 驗證清單
- 真實存在：是（arXiv:2401.11960）
- 與本研究相關：高度相關（降尺度設定與評測基準）


