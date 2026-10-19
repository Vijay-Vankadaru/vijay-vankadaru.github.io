---
title: "Representations of somatic mutations for cancer typing"
excerpt: "Can an interpretable feature table match a neural network that reads individual mutations? We built Bio MAF v4, a 948-feature representation of a tumor's somatic mutations, and benchmarked it against mutational signatures and a from-scratch MuAt transformer on 8,800 TCGA tumors. The feature table won: 0.738 vs 0.528 balanced accuracy."
collection: research
subtitle: "UMSOM, Tensor Lab, with Dr. Bradley A. Maron. Jun 2026 to present."
---

*UMSOM, Tensor Lab, with Dr. Bradley A. Maron. Jun 2026 to present.*

**Advisor:** [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/), University of Maryland School of Medicine. With Aaron Ge and Xingyan Liu.

**The question.** Models for cancer typing and DNA-repair-deficiency prediction differ less in their algorithms than in how they describe mutations. Does a genomics group need a custom neural network, or careful features?

**What we did.** Designed Bio MAF v4, 948 interpretable per-tumor summaries of mutation consequences, driver genes, hotspots, and allele fractions, and compared it with mutation counts, mutational signatures, and their combination using elastic net and XGBoost. Rebuilt the MuAt mutation transformer and trained it from scratch under the same compute budget as the comparison.

**What we found.** On 20 cancer types (n = 8,800), signatures plus Bio MAF v4 with XGBoost reached 0.738 balanced accuracy against 0.528 for the transformer, and the frozen model transferred to 913 PCAWG tumors. The gain depends on known cancer-gene annotations, which is itself informative about what the representation is encoding.

**Paper:** [in review](/publication/2026-09-15-somatic-mutation-representations).
