# Pianoroll-Event: A Novel Score Representation for Symbolic Music

> **ICASSP 2026**
>
> Lekai Qian\*, [Haoyu Gu](https://haoyu-gu.github.io/)\*, Dehan Li\*, Boyu Cao†, [Qi Liu](https://drliuqi.github.io/)†
>
> School of Future Technology, South China University of Technology
>
> \*Equal contribution. †Corresponding authors.

This is the demo page for our paper.

---

## Abstract

Symbolic music representation is a fundamental challenge in computational musicology. While grid-based representations effectively preserve pitch-time spatial correspondence, their inherent data sparsity leads to low encoding efficiency. Discrete-event representations achieve compact encoding but fail to adequately capture structural invariance and spatial locality. To address these complementary limitations, we propose Pianoroll-Event, a novel encoding scheme that describes pianoroll representations through events, combining structural properties with encoding efficiency while maintaining temporal dependencies and local spatial patterns. Specifically, we design four complementary event types: Frame Events for temporal boundaries, Gap Events for sparse regions, Pattern Events for note patterns, and Musical Structure Events for musical metadata. Pianoroll-Event strikes an effective balance between sequence length and vocabulary size, improving encoding efficiency by 1.36x to 7.16x over representative discrete sequence methods. Experiments across multiple autoregressive architectures show models using our representation consistently outperform baselines in both quantitative and human evaluations.

<p align="center">
  <img src="static/images/core.png" alt="Pianoroll-Event Diagram" width="100%">
</p>

---

## Demo Features

- MIDI player with piano-roll visualizer
- Generated music samples from multiple model architectures
- Encoding efficiency comparison table

---

## Acknowledgments

This work was supported in part by the National Natural Science Foundation of China under Grant 62202174, in part by the GJYC program of Guangzhou under Grant 2024D01J0081, in part by the ZJ program of Guangdong under Grant 2023QN10X455, and in part by the Fundamental Research Funds for the Central Universities under Grant 2025ZYGXZR053.
