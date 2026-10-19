---
title: "Subgroup fairness of glioma MRI classifiers"
excerpt: "External validation of three open-source glioma molecular subtype classifiers on a 3,380-patient UCSF cohort. AUROC looks stable across subgroups, but sensitivity and specificity move with age in ways that matter clinically. LLM labeling of 9,377 pathology reports made the subgroup tests possible."
collection: research
subtitle: "UCSF M2AI Lab, with Dr. Madhumita Sushil. Jun 2026 to present."
---

*UCSF M2AI Lab, with Dr. Madhumita Sushil. Jun 2026 to present.*

**Advisor:** [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil), UCSF. With Elisa Danthinne and collaborators in neurosurgery and radiology.

**The question.** Published MRI models for glioma subtype report AUROC above 0.9, but almost none report performance by patient subgroup. Does that performance hold for the patients a hospital actually sees?

**What we did.** Deployed three open-weight models (a multi-task 3D CNN, a ViT with a ClinicalBERT branch, and a CNN plus radiomics model) on an unseen UCSF cohort, reproducing each model's published preprocessing. Ground-truth labels for 9,377 pathology reports came from an LLM extraction pipeline validated against human labels, which grew the cohort from 442 to 3,380 patients and gave every subgroup enough samples to test. Subgroup comparisons use bootstrap confidence intervals, permutation tests, and Benjamini-Hochberg correction.

**What we found.** All three models underperform their published numbers. AUROC is stable across race, sex, and insurance, but specificity for IDH-wildtype patients under 40 drops to 54% against 80% for patients 55 and older, the kind of false reassurance that delays urgent surgery.

**Paper:** [in review](/publication/2026-09-29-glioma-subgroup-bias).
