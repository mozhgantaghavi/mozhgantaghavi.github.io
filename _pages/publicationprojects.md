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

{% include pp-style.liquid %}

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
