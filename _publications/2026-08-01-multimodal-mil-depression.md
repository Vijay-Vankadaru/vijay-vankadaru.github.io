---
title: "A Recipe for Multimodal Multi-Instance Depression Detection: Frozen Teachers, Schedule-Aware Training, and Audio Contribution Diagnostics"
collection: publications
category: review
permalink: /publication/2026-08-01-multimodal-mil-depression/
excerpt: "A frozen-teacher multimodal multi-instance model for depression detection on DAIC-WOZ (DepRoBERTa text, emotion-finetuned wav2vec2 audio, gated-attention pooling), plus the audio occlusion delta, a diagnostic for whether the audio branch is contributing at all."
date: 2026-08-01
venue: "ACL Rolling Review"
status: "Under review"
authors: "<b>V. Vankadaru</b>"
citation: "Vankadaru, V. A Recipe for Multimodal Multi-Instance Depression Detection: Frozen Teachers, Schedule-Aware Training, and Audio Contribution Diagnostics. Under review."
---

Solo-author paper from work at DASION.

Published DAIC-WOZ results are hard to reproduce: preprocessing is under-specified, seeds are missing, repositories are dead, and several reported numbers depend on bias the models should not be exploiting. This paper builds a modern multimodal multi-instance pipeline on top of frozen domain-finetuned encoders, reaches F1 0.87 as an honest bias-aware ceiling, and introduces the audio occlusion delta, a diagnostic that exposes modality collapse that accuracy alone cannot see.
