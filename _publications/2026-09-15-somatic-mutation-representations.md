---
title: "Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction"
collection: publications
category: review
permalink: /publication/2026-09-15-somatic-mutation-representations
excerpt: "Can a feature table match a neural network that reads individual mutations? We introduce Bio MAF v4, a 948-feature interpretable representation of a tumor's somatic mutations, and benchmark it against mutational signatures and a from-scratch MuAt transformer on 8,800 TCGA tumors."
date: 2026-09-15
venue: "In review"
citation: "Ge, A., Vankadaru, V., Liu, X., Almeida, J., Balasubramanian, J. B., &amp; Maron, B. A. Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction. In review."
---

With Aaron Ge, Xingyan Liu, Jonas Almeida, Jeya Balaji Balasubramanian, and [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/) at the University of Maryland School of Medicine.

Machine learning on somatic mutations differs less in the algorithm than in how the mutations are described: a count, a pattern of sequence contexts, gene-level annotations, or individual mutations read by a neural network. We compared four representations with elastic net and XGBoost against a MuAt-compatible transformer trained from scratch under a fixed compute budget. On 20 cancer types, mutational patterns plus Bio MAF v4 with XGBoost reached 0.738 balanced accuracy against 0.528 for the transformer, and the frozen model transferred to 913 PCAWG tumors.
