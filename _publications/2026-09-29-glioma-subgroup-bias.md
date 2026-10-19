---
title: "Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making: A Sociodemographic Subgroup Assessment Approach for Open-Source Glioma Molecular Subtype Classifiers"
collection: publications
category: review
permalink: /publication/2026-09-29-glioma-subgroup-bias
excerpt: "External validation of three open-source glioma molecular subtype classifiers on a 3,380-patient UCSF cohort. AUROC looks stable across subgroups, but sensitivity, specificity, PPV, and NPV vary by age in ways that change the expected clinical benefit."
date: 2026-09-29
venue: "In review"
citation: "Danthinne, E. S., Vankadaru, V., et al. Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making. In review."
---

With Elisa Danthinne, Hongbin Miao, Pierre Nedelec, Andreas Rauschecker, Ramin Morshed, Annette Molinaro, and [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil) at UCSF.

We externally validated three published, open-weight models that predict glioma molecular subtype (IDH mutation, 1p/19q codeletion, grade) from preoperative MRI on an unseen institutional cohort. To get subgroup sample sizes large enough to test anything, we used an LLM to label 9,377 pathology reports (majority vote over three runs, F1 0.96 to 0.97 against human labels), expanding the labeled cohort from 442 to 3,380 patients. All three models underperformed their published numbers, and errors concentrated by age: specificity for IDH-wildtype patients under 40 was 54%, against 80% for patients 55 and older.
