# Pianoroll-Event: Bridging Spatial and Sequential Representations for Efficient Music Generation

> Anonymous submission to ICME 2026

This is the demo page for our paper submission.

---

## Abstract

Effective symbolic music representation remains a fundamental challenge in computational musicology. While grid-based representations effectively preserve pitch-time spatial correspondence, their inherent data sparsity leads to low encoding efficiency. Discrete-event representations achieve compact encoding but fail to adequately capture structural invariance and spatial locality. Graph-based methods model relational structures but remain less compatible with autoregressive sequence modeling. To address these limitations, we propose Pianoroll-Event, which bridges spatial and sequential representations by transforming pianoroll matrices into structured event sequences, achieving encoding efficiency while preserving temporal dependencies and local spatial patterns. Specifically, we design four complementary event types: Frame Events for temporal boundaries, Gap Events for sparse regions, Pattern Events for note patterns, and Musical Structure Events for musical metadata. Pianoroll-Event strikes an effective balance between sequence length and vocabulary size, improving encoding efficiency by 1.36x to 7.16x over representative discrete sequence methods. Experiments across multiple autoregressive architectures show models using our representation consistently outperform baselines in both quantitative and human evaluations.

<p align="center">
  <img src="static/images/core.png" alt="Pianoroll-Event Diagram" width="100%">
</p>

---

## Demo Features

- MIDI player with piano-roll visualizer
- Generated music samples from multiple model architectures
- Encoding efficiency comparison table

---

*This page is for anonymous review purposes only.*
