# On-Manifold Adversarial Examples for Vision-Language Models

This repository collects research on adversarial examples for vision-language models (VLMs), with an emphasis on data-manifold-aware generation, generative priors, and diffusion- or other methods. It is intended as a concise reference for related papers, methods, and implementations.

## Selected Papers

| Method | Paper | Venue / Year | Core Approach | Code |
|---|---|---|---|---|
| **PSI** | [Transferable and Stealthy Adversarial Attacks on Large Vision-Language Models](https://openreview.net/forum?id=liQueBuFXi) | ICLR 2026 | Uses a diffusion prior, progressive semantic alignment, co-evolving region selection, and source-aware denoising to improve transferability and stealthiness. | / |
| **AdvDiffVLM** | [Efficient Generation of Targeted and Transferable Adversarial Examples for Vision-Language Models Via Diffusion Models](https://arxiv.org/abs/2404.10335) | IEEE TIFS, 2025 | Combines diffusion-based generation with Adaptive Ensemble Gradient Estimation (AEGE) and GradCAM-guided Mask Generation (GCMG). | [Official GitHub repository](https://github.com/gq-max/AdvDiffVLM) |
