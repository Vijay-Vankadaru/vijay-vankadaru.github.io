---
title: "Multimodal Multi-Instance Learning for Depression Detection: Combining Wav2Vec 2.0 Audio and Transformer Text Features with CTC Temporal Alignment"
collection: publications
category: manuscripts
permalink: /publication/2026-target-mil-depression
excerpt: 'First multimodal MIL framework for depression detection on DAIC-WOZ. Combines MT5/RoBERTa text with Wav2Vec 2.0 audio via CTC temporal alignment. Achieves F1>0.90, surpassing prior SOTA. Directly addresses interviewer bias via strict prompt exclusion.'
date: 2026-01-01
venue: 'Target: NeurIPS 2026'
citation: 'Vankadaru, V. et al. (2026). Multimodal Multi-Instance Learning for Depression Detection. Target: NeurIPS 2026.'
---

This paper is the first to combine a Multi-Instance Learning framework with
multimodal audio-text fusion for depression detection on DAIC-WOZ. The core
contribution is treating each clinical interview as a bag of multimodal
instances: each participant response has both a text representation
(MT5-small + RoBERTa-base ensemble) and an aligned audio representation
(Wav2Vec 2.0 with CTC temporal alignment). Bag-level depression labels
supervise instance-level predictions, with interpretable alpha/beta
aggregation rules preserved at inference.

**Three pillars:**

**Performance** — Targets F1>0.90, surpassing the text-only MIL baseline
of F1=0.88 (Zhang et al., 2025).

**Methodology** — Strict exclusion of interviewer prompts directly addresses
the interviewer bias problem documented by Burdisso et al. (2024), making
results more trustworthy and generalizable.

**Reproducibility** — Full code and model release, addressing the
reproducibility crisis documented in the field's December 2025 systematic review.

*Manuscript in preparation. Target venue: NeurIPS 2026.*
