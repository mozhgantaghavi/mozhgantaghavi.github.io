---
layout: page
title: Publications and Projects
permalink: /publications and projects/
#description: This is my research output
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---

<style>
  .pp { --pp-accent: var(--global-theme-color); }
  .pp-lead { font-size: 1.08rem; line-height: 1.75; max-width: 52rem; margin-bottom: 2rem; color: var(--global-text-color); }
  .pp-stats { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 14px; margin-bottom: 2.6rem; }
  .pp-stat { background: var(--global-card-bg-color); border: 1px solid var(--global-divider-color); border-radius: 14px; padding: 16px 18px; text-align: center; box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05); }
  .pp-stat b { display: block; font-size: 2rem; line-height: 1.1; color: var(--pp-accent); }
  .pp-stat span { font-size: 0.82rem; letter-spacing: 0.04em; text-transform: uppercase; color: var(--global-text-color-light); }
  .pp-section { display: flex; align-items: center; gap: 12px; margin: 2.8rem 0 1.2rem; }
  .pp-section h2 { margin: 0; font-size: 1.45rem; font-weight: 600; }
  .pp-section::after { content: ""; flex: 1; height: 1px; background: var(--global-divider-color); }
  .pp-section i { color: var(--pp-accent); font-size: 1.3rem; }
  .pp-card { position: relative; background: var(--global-card-bg-color); border: 1px solid var(--global-divider-color); border-left: 5px solid var(--pp-accent); border-radius: 14px; padding: 18px 22px; margin-bottom: 16px; box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05); transition: transform 0.18s ease, box-shadow 0.18s ease; }
  .pp-card:hover { transform: translateY(-2px); box-shadow: 0 8px 22px rgba(0, 0, 0, 0.12); }
  .pp-card h3 { font-size: 1.12rem; font-weight: 600; line-height: 1.45; margin: 0 0 6px; }
  .pp-card p { margin: 0 0 6px; line-height: 1.65; }
  .pp-meta { font-size: 0.92rem; color: var(--global-text-color-light); }
  .pp-year { display: inline-block; font-size: 0.78rem; font-weight: 600; letter-spacing: 0.05em; padding: 2px 11px; border-radius: 999px; background: var(--pp-accent); color: var(--global-hover-text-color); margin-bottom: 8px; }
  .pp-tags { display: flex; flex-wrap: wrap; gap: 6px; margin: 10px 0 4px; }
  .pp-tag { font-size: 0.76rem; padding: 2px 10px; border-radius: 999px; border: 1px solid var(--pp-accent); color: var(--pp-accent); }
  .pp-links { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 12px; }
  .pp-btn { display: inline-flex; align-items: center; gap: 7px; padding: 6px 16px; border-radius: 999px; border: 1px solid var(--pp-accent); color: var(--pp-accent) !important; font-size: 0.88rem; text-decoration: none !important; transition: background 0.15s ease, color 0.15s ease; }
  .pp-btn:hover { background: var(--pp-accent); color: var(--global-hover-text-color) !important; }
  .pp-url { font-size: 0.8rem; color: var(--global-text-color-light); margin-top: 8px; word-break: break-all; }
  .pp-feature { border-left-width: 5px; background: linear-gradient(135deg, var(--global-card-bg-color), var(--global-card-bg-color)); }
  .pp-badge { float: right; font-size: 0.72rem; font-weight: 600; letter-spacing: 0.06em; text-transform: uppercase; color: var(--pp-accent); border: 1px solid var(--pp-accent); border-radius: 6px; padding: 1px 8px; margin-left: 10px; }
  @media (max-width: 576px) { .pp-card { padding: 16px; } .pp-badge { float: none; display: inline-block; margin: 0 0 8px; } }
</style>

<div class="pp">

<p class="pp-lead">My work sits between theory and computation. I study variational problems and the mathematical models behind them, and I build numerical tools, from spectral methods to simulation codes, that turn those ideas into something we can compute and test. Below you can find my published papers, the talks I have given, and the computational projects I have developed so far.</p>

<div class="pp-stats">
  <div class="pp-stat"><b>2</b><span>Journal papers</span></div>
  <div class="pp-stat"><b>2</b><span>Conference talks</span></div>
  <div class="pp-stat"><b>3</b><span>Projects</span></div>
</div>

<div class="pp-section"><i class="fa-solid fa-book-open"></i><h2>Peer-Reviewed Publications</h2></div>

<div class="pp-card">
  <span class="pp-year">2024</span>
  <h3>A Fourier–Legendre spectral method for approximating the minimizers of σ₂,ₚ-energy</h3>
  <p class="pp-meta"><b>M. Taghavi</b>, M. S. Shahrokhi-Dehkordi</p>
  <p class="pp-meta"><em>Quarterly of Applied Mathematics</em>, 82(3), 563–582</p>
</div>

<div class="pp-card">
  <span class="pp-year">2023</span>
  <h3>The existence of multiple topologically distinct solutions to σ₂,ₚ-energy</h3>
  <p class="pp-meta"><b>M. Taghavi</b>, M. S. Shahrokhi-Dehkordi</p>
  <p class="pp-meta"><em>Topological Methods in Nonlinear Analysis</em>, 1(1), 1–21</p>
</div>

<div class="pp-section"><i class="fa-solid fa-microphone-lines"></i><h2>Conference Presentations</h2></div>

<div class="pp-card">
  <span class="pp-year">2021</span>
  <h3>Existence of σ₂,ₚ-energy functional and polyconvexity</h3>
  <p class="pp-meta">M. S. Shahrokhi-Dehkordi, <b>M. Taghavi</b></p>
  <p class="pp-meta">51st Annual Iranian Mathematics Conference · Oral presentation</p>
</div>

<div class="pp-card">
  <span class="pp-year">2014</span>
  <h3>Collocation Haar wavelets method for solving Helmholtz equations</h3>
  <p class="pp-meta">S. Sedighi, <b>M. Taghavi</b>, E. Shivanian</p>
  <p class="pp-meta">45th Annual Iranian Mathematics Conference · Poster</p>
</div>

<div class="pp-section"><i class="fa-solid fa-flask"></i><h2>Projects</h2></div>

<div class="pp-card pp-feature">
  <span class="pp-badge">Latest</span>
  <span class="pp-year">2026</span>
  <h3>TumorPINN Lab: Estimating Tumour-Growth Parameters with Spectral Solvers, CNNs and Physics-Informed Neural Networks</h3>
  <p>In this project I look at how a tumour spreads and grows, using the Fisher–KPP reaction–diffusion model. From noisy measurements of tumour density, the goal is to recover the two quantities that drive the model: how fast cells diffuse and how fast they proliferate. I compare four ways of doing this on the same data: a convolutional network, a classical spectral least-squares fit, a PINN, and a PINN started from the network's estimate. The same idea is then applied to real growth curves from public mouse-tumour datasets, with thousands of PINNs trained together in GPU batches. Everything is collected in an interactive dashboard.</p>
  <div class="pp-tags">
    <span class="pp-tag">PINN</span><span class="pp-tag">CNN</span><span class="pp-tag">Legendre spectral method</span><span class="pp-tag">Fisher–KPP</span><span class="pp-tag">Inverse problems</span><span class="pp-tag">PyTorch</span>
  </div>
  <div class="pp-links">
    <a class="pp-btn" href="https://github.com/mozhgantaghavi/tumor-growth-pinn" target="_blank" rel="noopener"><i class="fa-brands fa-github"></i> GitHub repository</a>
    <a class="pp-btn" href="https://mozhgantaghavi.github.io/tumor-growth-pinn/" target="_blank" rel="noopener"><i class="fa-solid fa-chart-line"></i> Interactive dashboard</a>
  </div>
  <div class="pp-url">Repository: https://github.com/mozhgantaghavi/tumor-growth-pinn<br>Dashboard: https://mozhgantaghavi.github.io/tumor-growth-pinn/</div>
</div>

<div class="pp-card">
  <span class="pp-year">2025</span>
  <h3>A Numerical Method for a Zero-Dimensional Lumped-Parameter Blood Flow Model</h3>
  <p>Here I model blood flow with vessel compartments connected to Windkessel terminal models, which gives a system of ODEs for pressure, flow and volume. I solve it with the forward Euler method and calibrate the parameters against synthetic data using optimization.</p>
  <div class="pp-tags"><span class="pp-tag">Blood flow</span><span class="pp-tag">Windkessel</span><span class="pp-tag">ODEs</span><span class="pp-tag">Parameter estimation</span></div>
</div>

<div class="pp-card">
  <span class="pp-year">2013</span>
  <h3>Discontinuous Finite Element Method for a Delay Differential Equation</h3>
  <p>An early numerical project, where I applied a discontinuous finite element approach to a delay differential equation.</p>
  <div class="pp-tags"><span class="pp-tag">Finite elements</span><span class="pp-tag">Delay equations</span></div>
</div>

</div>
