---
layout: page
title: "LiFT: Efficient 3D Medical Image Generation"
description: "~135× lower inference cost than comparable 3D methods. Evaluated on BraTS 2023 and SynthRAD2023. arXiv 2026."
importance: 1
category: research
---

**Role:** First author &nbsp;·&nbsp; **Venue:** arXiv, 2026 &nbsp;·&nbsp; [[Paper]](https://arxiv.org/abs/2605.19060)

---

## Summary

3D medical image synthesis is computationally expensive: existing approaches generate volumes slice-by-slice or with fully 3D models, requiring high memory and inference cost. LiFT addresses this by repurposing pre-trained 2D generators and composing their outputs into coherent 3D volumes through a lightweight trajectory-based consistency module — treating a volume as an ordered trajectory in feature space.

**Key results:**
- ~135× reduction in inference cost compared to comparable 3D diffusion baselines
- Competitive generation quality on BraTS 2023 (brain MRI) and SynthRAD2023
- Validated across unconditional generation, missing-modality MR synthesis, and MR-to-CT translation

## Why It Matters

Data scarcity is a fundamental bottleneck in medical AI. Synthetic augmentation for rare pathologies requires 3D-coherent outputs — but 3D generation has historically been prohibitively expensive. LiFT makes high-quality 3D synthesis practical, opening the door to large-scale data augmentation without 3D-native model training.

## My Role

- Developed the core method and architecture
- Implemented the full modeling and evaluation pipeline
- Ran experiments and ablations across all benchmarks
- Led manuscript writing and preparation
