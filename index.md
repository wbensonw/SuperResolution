  ---
  layout: default
  ---
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>氣象超分辨率/降尺度 前沿論文索引</title>
  <style>
    :root { --bg:#0f172a; --fg:#e2e8f0; --muted:#94a3b8; --card:#111827; --accent:#60a5fa; }
    html,body{margin:0;padding:0;background:var(--bg);color:var(--fg);font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue","Noto Sans TC","PingFang TC","Microsoft JhengHei",sans-serif;line-height:1.6;}
    .container{max-width:980px;margin:0 auto;padding:28px;}
    h1{font-size:28px;margin:0 0 8px;}
    p.lead{color:var(--muted);margin-top:0}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:16px;margin-top:20px}
    .card{background:var(--card);border:1px solid #1f2937;border-radius:12px;padding:16px}
    .card h3{margin:0 0 6px;font-size:18px}
    .card a{color:var(--accent);text-decoration:none}
    .card .meta{color:var(--muted);font-size:12px;margin-top:6px}
    .footer{margin-top:32px;color:var(--muted);font-size:12px}
    .tag{display:inline-block;padding:2px 8px;border-radius:999px;background:#0b1220;color:#9cc1ff;border:1px solid #1f2b45;margin-right:6px;font-size:11px}
  </style>
</head>
<body>
  <div class="container">
    <h1>氣象超分辨率/降尺度 前沿研究索引</h1>
    <p class="lead">包含多通道CNN、生成式方法（GAN/擴散）、Transformer/Fourier操作、以及物理一致性與外推性評估等主題。所有Markdown檔案位於 <code>papers/</code> 目錄。</p>
    <div class="grid">
      <div class="card">
        <h3><a href="papers/01_DeepSD_2017.md">01. DeepSD (2017)</a></h3>
        <div class="meta">單影像SR × 統計降尺度｜arXiv</div>
        <div class="meta"><span class="tag">CNN</span><span class="tag">Downscaling</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/02_Leinonen_GAN_SR_2020.md">02. Stochastic SR with GAN (2020/2021)</a></h3>
        <div class="meta">隨機超分辨率（時間一致）｜IEEE TGRS</div>
        <div class="meta"><span class="tag">GAN</span><span class="tag">Temporal</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/03_SRDA_4D_2022.md">03. 4D-SRDA (2022)</a></h3>
        <div class="meta">時空SR × 同化 × 域泛化｜arXiv</div>
        <div class="meta"><span class="tag">Assimilation</span><span class="tag">Generalization</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/04_Pangu_Weather_2022.md">04. Pangu-Weather (2022)</a></h3>
        <div class="meta">3D Transformer × 0.25°全球預報｜arXiv</div>
        <div class="meta"><span class="tag">Transformer</span><span class="tag">ERA5</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/05_FourCastNet_2022.md">05. FourCastNet (2022)</a></h3>
        <div class="meta">傅立葉神經算子 × 高速預報｜arXiv</div>
        <div class="meta"><span class="tag">FNO</span><span class="tag">Frequency</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/06_ClimaX_2023.md">06. ClimaX (2023)</a></h3>
        <div class="meta">基礎模型 × 多任務/多資料｜ICML</div>
        <div class="meta"><span class="tag">Transformer</span><span class="tag">Pretraining</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/07_HyperDS_2024.md">07. HyperDS (2024)</a></h3>
        <div class="meta">觀測引導 × 站點尺度降尺度｜arXiv</div>
        <div class="meta"><span class="tag">HyperNetwork</span><span class="tag">Benchmark</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/08_GAN_Extrapolation_Extremes_2024.md">08. GAN外推極端降水 (2024)</a></h3>
        <div class="meta">GAN外推能力 × GRL｜arXiv</div>
        <div class="meta"><span class="tag">GAN</span><span class="tag">Extremes</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/09_Stochastic_Downscaling_Precip_2022.md">09. 生成式隨機降水降尺度 (2022)</a></h3>
        <div class="meta">JAMES｜arXiv</div>
        <div class="meta"><span class="tag">Precipitation</span><span class="tag">Generative</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/10_RainScaleGAN_2025.md">10. RainScaleGAN (2025)</a></h3>
        <div class="meta">條件GAN｜arXiv</div>
        <div class="meta"><span class="tag">GAN</span><span class="tag">Extreme rain</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/11_WassDiff_ExtremePrecip_2025.md">11. WassDiff極端降水 (2025)</a></h3>
        <div class="meta">Wasserstein正則化擴散｜arXiv</div>
        <div class="meta"><span class="tag">Diffusion</span><span class="tag">Extremes</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/12_Transformer_Reanalysis_Tiling_2024.md">12. Transformer區域重分析SR (2024)</a></h3>
        <div class="meta">全域vs瓦片｜arXiv</div>
        <div class="meta"><span class="tag">Swin</span><span class="tag">CERRA</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/13_EnScale_2025.md">13. EnScale生成式降尺度 (2025)</a></h3>
        <div class="meta">Proper scoring｜arXiv</div>
        <div class="meta"><span class="tag">Generative</span><span class="tag">Temporal</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/14_WindPower_SR_Downscaling_2024.md">14. 風電評估與SR (2024)</a></h3>
        <div class="meta">SR/降尺度比較｜arXiv</div>
        <div class="meta"><span class="tag">Wind</span><span class="tag">Diffusion</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/15_ViFOR_ViSIR_2025.md">15. ViFOR/ViSIR (2025)</a></h3>
        <div class="meta">Consistency Model 降尺度｜arXiv</div>
        <div class="meta"><span class="tag">Generative</span><span class="tag">Zero-shot</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/16_cBottle_2025.md">16. cBottle (2025)</a></h3>
        <div class="meta">LDM 擬合公里級 RCM｜arXiv/GMD</div>
        <div class="meta"><span class="tag">Diffusion</span><span class="tag">RCM</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/17_SISR_1km_Climate_2025.md">17. SISR到1km (2025)</a></h3>
        <div class="meta">Neural Operator 零樣本降尺度｜arXiv/EDS</div>
        <div class="meta"><span class="tag">Neural Operator</span><span class="tag">Generalization</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/18_RainShift_2025.md">18. RainShift (2025)</a></h3>
        <div class="meta">擴散集合變異控制｜arXiv</div>
        <div class="meta"><span class="tag">Diffusion</span><span class="tag">Uncertainty</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/19_Fukami_JFM_2019.md">19. 湍流SR（JFM 2019）</a></h3>
        <div class="meta">經典流體SR｜JFM</div>
        <div class="meta"><span class="tag">Turbulence</span><span class="tag">SR</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/20_SingleSnapshot_Turbulence_SR_2024.md">20. 單快照湍流SR (2024)</a></h3>
        <div class="meta">資料受限情境｜JFM</div>
        <div class="meta"><span class="tag">Turbulence</span><span class="tag">Single-shot</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/21_BuckinghamPi_Turbulent_Scaling_2024.md">21. Π變數尺度化 (2024)</a></h3>
        <div class="meta">物理引導尺度化｜JFM</div>
        <div class="meta"><span class="tag">Scaling</span><span class="tag">Physics</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/22_Radar_SR_JTECH_2020.md">22. 雷達超分辨 (2020)</a></h3>
        <div class="meta">深度學習雷達SR｜JTECH</div>
        <div class="meta"><span class="tag">Radar</span><span class="tag">SR</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/23_GraphCast_Science_2023.md">23. GraphCast (2023)</a></h3>
        <div class="meta">Science｜GNN預報</div>
        <div class="meta"><span class="tag">GNN</span><span class="tag">Forecast</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/24_Review_Precip_Downscaling_ESI_2023.md">24. 降水降尺度綜述 (2023)</a></h3>
        <div class="meta">ESI｜Springer</div>
        <div class="meta"><span class="tag">Review</span><span class="tag">Precip</span></div>
      </div>
      <div class="card">
        <h3><a href="papers/25_Ocean_Wind_SR_RemoteSensing_2021.md">25. 海表風速SR (2024)</a></h3>
        <div class="meta">JMSE（MDPI）</div>
        <div class="meta"><span class="tag">Wind</span><span class="tag">GAN</span></div>
      </div>
    </div>
    <div class="footer">
      已補齊25篇。若有新作發表，將持續更新摘要、方法細節與與本研究之對應分析。
    </div>
  </div>
</body>
</html>


