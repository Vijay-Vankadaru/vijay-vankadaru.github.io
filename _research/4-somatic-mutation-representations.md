---
title: "Representing a tumor's mutations for cancer typing"
excerpt: "Does a neural network that reads individual mutations beat a well-designed feature table? On 8,800 tumors under the same compute budget, an interpretable feature table we designed identified cancer type more accurately than a mutation transformer trained from scratch."
collection: research
tags: ["Cancer genomics", "Representation learning"]
subtitle: "Machine Learning Research Fellow, The Tensor Lab, University of Maryland School of Medicine (UMSOM). Jun 2026 to present."
links:
  - label: "Manuscript (under review)"
    url: "/publication/2026-09-15-somatic-mutation-representations/"
---

I am a Machine Learning Research Fellow in The Tensor Lab at the University of Maryland School of Medicine (UMSOM). I work there with Aaron Ge, Xingyan Liu, and [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/).

Models that work on a tumor's somatic mutations differ less in their algorithm than in how the mutations are described. I designed Bio MAF v4, an interpretable table of per-tumor features, and rebuilt a mutation transformer from scratch to compare against it under the same compute budget.

On 8,800 tumors, the feature table identified cancer type more accurately than the transformer, and the result transferred to an independent cohort. The gain depends on known cancer-gene annotations, which shows what the representation encodes.

**Paper**

- [Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction](/publication/2026-09-15-somatic-mutation-representations/). Under review.
