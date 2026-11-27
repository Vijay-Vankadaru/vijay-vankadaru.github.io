---
title: "Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction"
collection: publications
category: review
permalink: /publication/2026-09-15-somatic-mutation-representations/
excerpt: "How a tumor's mutations are represented matters more than the model that reads them. On 8,800 tumors, an interpretable feature table we designed outperforms a mutation transformer trained from scratch at identifying cancer type."
date: 2026-09-15
venue: ""
status: "Under review"
authors: "A. Ge, <b>V. Vankadaru</b>, X. Liu, J. Almeida, J. B. Balasubramanian, B. A. Maron"
---

With Aaron Ge, Xingyan Liu, Jonas Almeida, Jeya Balaji Balasubramanian, and [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/) at the University of Maryland School of Medicine.

Models that work on a tumor's somatic mutations differ less in their algorithm than in how the mutations are described. We compared several descriptions: mutation counts, mutational signatures, a new interpretable feature table we call Bio MAF v4, and a transformer that reads individual mutations, trained from scratch under the same compute budget.

On 8,800 tumors from TCGA, signatures plus Bio MAF v4 with a gradient-boosted model identified cancer type more accurately than the transformer, and the trained model transferred to an independent cohort. The gain depends on known cancer-gene annotations, which tells us what the representation is encoding.

## BibTeX

```bibtex
@unpublished{ge2026somatic,
  title  = {Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction},
  author = {Ge, Aaron and Vankadaru, Vijay and Liu, Xingyan and Almeida, Jonas and Balasubramanian, Jeya Balaji and Maron, Bradley A.},
  note   = {Under review},
  year   = {2026}
}
```
