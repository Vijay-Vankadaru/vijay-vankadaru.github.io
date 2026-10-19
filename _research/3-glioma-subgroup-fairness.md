---
title: "Subgroup fairness of glioma MRI classifiers"
excerpt: "Published glioma subtype classifiers report AUROC above 0.9 and almost never report who they fail for. We deployed three open-weight MRI models (3D CNN, ViT with ClinicalBERT, CNN with radiomics) on an IRB-approved cohort of 3,380 UCSF patients, built an LLM pipeline that labeled 9,377 pathology reports at F1 0.96 to 0.97 so every subgroup had enough samples to test, and found that errors concentrate by age in a way that would delay urgent surgery for younger patients."
collection: research
tags: ["Clinical ML", "Fairness", "Neuro-oncology imaging"]
subtitle: "UCSF M2AI Lab, with Dr. Madhumita Sushil. Jun 2026 to present."
---


**Advisor:** [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil), UCSF. With Elisa Danthinne and collaborators in neurosurgery and radiology.

**The question.** Published MRI models for glioma subtype report AUROC above 0.9, but almost none report performance by patient subgroup. Does that performance hold for the patients a hospital actually sees?

**What we did.** Deployed three open-weight models (a multi-task 3D CNN, a ViT with a ClinicalBERT branch, and a CNN plus radiomics model) on an unseen UCSF cohort, reproducing each model's published preprocessing. Ground-truth labels for 9,377 pathology reports came from an LLM extraction pipeline validated against human labels, which grew the cohort from 442 to 3,380 patients and gave every subgroup enough samples to test. Subgroup comparisons use bootstrap confidence intervals, permutation tests, and Benjamini-Hochberg correction.

**What we found.** All three models underperform their published numbers. AUROC is stable across race, sex, and insurance, but specificity for IDH-wildtype patients under 40 drops to 54% against 80% for patients 55 and older, the kind of false reassurance that delays urgent surgery.

**Paper:** [in review](/publication/2026-09-29-glioma-subgroup-bias).
