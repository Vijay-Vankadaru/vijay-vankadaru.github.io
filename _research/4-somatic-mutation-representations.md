---
title: "Representations of somatic mutations for cancer typing"
excerpt: "A compute-matched comparison of mutation representations for cancer typing. We designed Bio MAF v4, 948 interpretable per-tumor features of mutation consequence, driver genes, hotspots, and allele fraction, rebuilt the MuAt mutation transformer from scratch, and benchmarked both on 8,800 TCGA tumors. The feature table outperformed the transformer for cancer typing (0.738 vs 0.528 balanced accuracy) and HRD prediction (AUROC 0.91 vs 0.75), and transferred to 913 PCAWG tumors."
collection: research
tags: ["Cancer genomics", "Representation learning", "Benchmarking"]
subtitle: "UMSOM, Tensor Lab, with Dr. Bradley A. Maron. Jun 2026 to present."
---


**Advisor:** [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/), University of Maryland School of Medicine. With Aaron Ge and Xingyan Liu.

**Question.** Models for cancer typing and DNA-repair-deficiency prediction differ less in their algorithms than in how they represent mutations. Does a neural network that reads individual mutations beat a well-designed feature table under the same compute budget?

**Method.** Designed Bio MAF v4, 948 interpretable per-tumor summaries of mutation consequences, driver genes, hotspots, and allele fractions, and compared it with mutation counts, mutational signatures, and their combination using elastic net and XGBoost. Rebuilt the MuAt mutation transformer and trained it from scratch under the same compute budget as the comparison.

**Findings.** On 20 cancer types (n = 8,800), signatures plus Bio MAF v4 with XGBoost reached 0.738 balanced accuracy against 0.528 for the transformer, and the frozen model transferred to 913 PCAWG tumors. The gain depends on known cancer-gene annotations, which is itself informative about what the representation is encoding.

**Paper:** [in review](/publication/2026-09-15-somatic-mutation-representations).
