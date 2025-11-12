---
title_en: Stochastic Super-Resolution for Downscaling Time-Evolving Atmospheric Fields with a GAN
title_zh: 使用GAN之隨機超分辨率：時間演變大氣場的降尺度
source: arXiv (IEEE TGRS 2021)
date: 2020-05-20
link: https://arxiv.org/abs/2005.10374
topics: ["GAN", "Atmospheric fields", "Downscaling", "Precipitation"]
---

## 英文題目
Stochastic Super-Resolution for Downscaling Time-Evolving Atmospheric Fields with a Generative Adversarial Network

## 中文題目
使用GAN之隨機超分辨率：時間演變大氣場的降尺度

## 出處與日期
- 出處：arXiv（後發表於IEEE TGRS 2021）
- 日期：2020-05-20
- 連結：https://arxiv.org/abs/2005.10374

## Citation（引用）
- Authors: Jussi Leinonen, Daniele Nerini, Alexis Berne
- Journal ref: IEEE Transactions on Geoscience and Remote Sensing, 59 (9), 7211–7223, 2021

## BibTeX
```bibtex
@article{Leinonen2021StochasticSR,
  title={Stochastic Super-Resolution for Downscaling Time-Evolving Atmospheric Fields with a Generative Adversarial Network},
  author={Leinonen, Jussi and Nerini, Daniele and Berne, Alexis},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={59},
  number={9},
  pages={7211--7223},
  year={2021}
}
```

## 摘要（中英整合）
提出以GAN為核心的隨機超分辨率方法，從低解析度大氣場重建時間一致的高解析度序列，兼顧統計分佈與時變結構。

## 英文摘要（原文要點擷取）
使用條件GAN執行大氣科學中的「降尺度（超分辨）」問題：給定低解析度序列，生成時間演化的一組高解析度序列，形成可取樣的集合。以瑞士雷達降水及GOES-16雲光學厚度資料驗證，GAN可產生真實且具時間一致性的SR序列；以秩統計分析顯示輸出變異性接近正確。全卷積生成器可適用大於訓練尺寸的輸入，且能生成遠長於訓練長度的時間序列；並附原始碼。

## 問題設定與資料
- 任務：將隨時間演變的低解析度大氣場序列，轉為高解析度且時間一致的場。
- 需求：兼顧統計特性（分佈、極端值）與時序一致性（連續性、不抖動）。

## 方法概覽（模型/架構）
- 以GAN為基礎的生成式超分辨框架，能對同一輸入產生具多樣性的SR結果（隨機性）。
- 在訓練中同時考量空間紋理與時間連續性。

## 損失與約束（概述）
- 對抗損失 + 重建/感知類損失，以平衡「真實感」與「準確度」。
- 著重時間一致性設計，但未顯式加入動力學物理守恆。

## 評估與結果要點
- 展示在回復細節與極端現象的能力，並維持序列的時間一致表現。
- 證明生成式方法對「一對多」之SR問題的適切性。

## 限制與風險
- 物理一致性未被強制：可能產生視覺合理但物理偏差之場。
- 生成式方法需控制模式崩潰與偏差。

## 詳解與前沿特點
- 以生成式建模處理「非唯一映射」的SR問題（多樣性、機率一致性）。
- 證明GAN可在氣象領域保留時序一致與極端事件特徵。

## 與本研究之關聯
- 我方模型可納入隨機/生成式頭部，與物理約束共同提升泛化與物理合理性。 

## 可直接借鑑的實驗建議
- 在我方固定CNN骨架上，加上一個「生成式頭」並以分佈性指標評估（分位數、極端指標）。
- 與我方之地轉/散度/渦度/非地轉風/熱力相關性聯合訓練，觀察物理一致性改善幅度。

## 驗證清單
- 真實存在：是（arXiv與IEEE TGRS）
- 與本研究相關：高度相關（時間一致的生成式SR降尺度）


