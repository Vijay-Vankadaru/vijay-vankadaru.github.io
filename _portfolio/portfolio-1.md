---
title: "Multimodal Multi-Instance Learning for Depression Detection"
excerpt: "First multimodal MIL framework combining Wav2Vec 2.0 audio with MT5/RoBERTa text via CTC temporal alignment for depression detection on DAIC-WOZ."
collection: portfolio
---

## Overview

This project develops the first multimodal Multi-Instance Learning (MIL)
framework for depression detection, treating clinical interviews as bags of
multimodal instances. Each participant response has both a text representation
(MT5-small + RoBERTa-base ensemble) and an audio representation (Wav2Vec 2.0
with CTC temporal alignment). Bag-level depression labels supervise
instance-level predictions through interpretable aggregation rules.

Work conducted at DASION in collaboration with Prof. Weiqing Gu (Harvey Mudd
College), with NSF Phase I and II funding.

## The Problem

Prior work on depression detection either uses audio alone or text alone,
or fuses them in ways that don't preserve temporal correspondence between
modalities. A second problem: most systems include interviewer prompts in
the input, contaminating results with interviewer-specific patterns that
won't generalize to new settings.

## Technical Approach

**Multimodal fusion via CTC alignment** — Wav2Vec 2.0 audio features are
temporally aligned with MT5/RoBERTa text representations using Connectionist
Temporal Classification, preserving the correspondence between spoken words
and their acoustic properties.

**Multi-Instance Learning** — Each interview is a bag; each participant
response turn is an instance. The model learns bag-level labels (depressed /
not depressed) while generating interpretable instance-level attention weights
showing which responses drove the prediction.

**Interviewer bias mitigation** — Strict exclusion of interviewer prompts
from all inputs, directly addressing the bias problem documented by Burdisso
et al. (2024).

## Results

- F1 > 0.90 on DAIC-WOZ (baseline: 0.88, Zhang et al. 2025)
- Outperforms audio-only and text-only MIL baselines
- Interpretable alpha/beta aggregation rules preserved at inference

## Target Venue

NeurIPS 2026. Full code and model release planned upon submission.
