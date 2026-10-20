---
title: "Subgroup fairness of glioma MRI classifiers"
excerpt: "External validation of three published glioma subtype classifiers (3D CNN, ViT with ClinicalBERT, CNN with radiomics) on an IRB-approved cohort of 3,380 UCSF patients. An LLM pipeline labeled 9,377 pathology reports at F1 0.96 to 0.97, giving every subgroup enough samples to test. Errors concentrate by age: specificity for IDH-wildtype patients under 40 is 54%, against 80% at 55 and older."
collection: research
tags: ["Clinical ML", "Fairness", "Neuro-oncology imaging"]
subtitle: "UCSF M2AI Lab, with Dr. Madhumita Sushil. Jun 2026 to present."
---


**Advisor:** [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil), UCSF. With Elisa Danthinne and collaborators in neurosurgery and radiology.

**Question.** Published MRI models for glioma subtype report AUROC above 0.9, and almost none report performance by patient subgroup. Does the performance hold across the patient population of a single institution?

**Method.** Deployed three open-weight models (a multi-task 3D CNN, a ViT with a ClinicalBERT branch, and a CNN plus radiomics model) on an unseen UCSF cohort, reproducing each model's published preprocessing. Ground-truth labels for 9,377 pathology reports came from an LLM extraction pipeline validated against human labels, which grew the cohort from 442 to 3,380 patients and gave every subgroup enough samples to test. Subgroup comparisons use bootstrap confidence intervals, permutation tests, and Benjamini-Hochberg correction.

**Findings.** All three models underperform their published numbers. AUROC is stable across race, sex, and insurance, but specificity for IDH-wildtype patients under 40 is 54% against 80% for patients 55 and older. A false IDH-mutant prediction in that group would delay surgery.

**Paper:** [in review](/publication/2026-09-29-glioma-subgroup-bias).
