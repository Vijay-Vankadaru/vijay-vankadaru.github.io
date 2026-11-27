---
title: "Do glioma MRI classifiers work equally well across patients?"
excerpt: "Published MRI models for glioma subtype report high overall scores and rarely report results by patient group. We tested three of them on 3,380 patients from a new hospital. Overall scores look stable across groups, but the models make more errors on younger patients."
collection: research
tags: ["Clinical ML", "Evaluation", "Neuro-oncology imaging"]
subtitle: "Machine Learning Research Fellow, M2AI Lab, UCSF. Jun 2026 to present."
links:
  - label: "Manuscript (under review)"
    url: "/publication/2026-09-29-glioma-subgroup-bias/"
posterurl: "/files/posters/danthinne-vankadaru-glioma-subgroup-poster.pdf"
posterimg: "/images/posters/glioma-subgroup.jpg"
---

I am a Machine Learning Research Fellow in the M2AI Lab at UCSF, working with [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil), Elisa Danthinne, and collaborators in neurosurgery and radiology.

Published MRI models that predict glioma molecular subtype report high overall scores, and few report results by patient group. We ran three published models on 3,380 UCSF patients they had not seen, using an LLM to read pathology reports so that each patient group had enough labels to test.

Overall scores were similar across race, sex, and insurance. The errors were concentrated by age: the models were less specific for younger patients, the group where a wrong prediction could delay surgery. An overall score did not show this.

**Paper**

- [Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making](/publication/2026-09-29-glioma-subgroup-bias/). Under review.
