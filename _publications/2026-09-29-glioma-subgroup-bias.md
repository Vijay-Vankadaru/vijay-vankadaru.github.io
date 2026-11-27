---
title: "Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making: A Sociodemographic Subgroup Assessment Approach for Open-Source Glioma Molecular Subtype Classifiers"
collection: publications
category: review
permalink: /publication/2026-09-29-glioma-subgroup-bias/
excerpt: "We tested three published glioma MRI classifiers on 3,380 patients from a new hospital. Overall scores look stable across patient groups, but the models make more errors on younger patients."
date: 2026-09-29
venue: ""
status: "Under review"
authors: "E. S. Danthinne, <b>V. Vankadaru</b>, H. Miao, P. Nedelec, A. Rauschecker, R. Morshed, A. Molinaro, M. Sushil"
posterurl: "/files/posters/danthinne-vankadaru-glioma-subgroup-poster.pdf"
posterimg: "/images/posters/glioma-subgroup.jpg"
---

With Elisa Danthinne, Hongbin Miao, Pierre Nedelec, Andreas Rauschecker, Ramin Morshed, Annette Molinaro, and [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil) at UCSF.

Published MRI models that predict glioma molecular subtype report high overall scores, and few report results by patient group. We ran three published, open-weight models on 3,380 UCSF patients they had not seen. To have enough labeled patients in each group, we used an LLM to read pathology reports and checked its labels against human labels.

All three models did worse than their published results. Their overall scores were similar across race, sex, and insurance, but their errors were concentrated by age. Specificity was lower for younger patients, which is the group where a wrong prediction could delay surgery.

## BibTeX

```bibtex
@unpublished{danthinne2026agebias,
  title  = {Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making: A Sociodemographic Subgroup Assessment Approach for Open-Source Glioma Molecular Subtype Classifiers},
  author = {Danthinne, Elisa S. and Vankadaru, Vijay and Miao, Hongbin and Nedelec, Pierre and Rauschecker, Andreas and Morshed, Ramin and Molinaro, Annette and Sushil, Madhumita},
  note   = {Under review},
  year   = {2026}
}
```
