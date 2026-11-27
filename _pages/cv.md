---
layout: archive
title: "CV"
permalink: /curriculum-vitae/
author_profile: true
redirect_from:
  - /resume
  - /cv/
---

{% include base_path %}

[Download PDF](/files/Vijay_Vankadaru_CV.pdf){: .btn .btn--info}

## Education

**University of California, Berkeley**, Master of Data Science, Machine Learning emphasis. GPA 4.0. Expected May 2027.
Coursework: NLP with Deep Learning, Computer Vision, Applied Machine Learning, Causal Inference, Data Engineering, Statistics.

**University of California, Riverside**, B.S. Computer Science. Jun 2025.

## Publications

1. **V. Vankadaru**, V. DuTell. Believing Is Seeing: How Vision-Language Models Decide to Believe an Image. Under review at CVPR '27.
2. **V. Vankadaru**, V. DuTell. Vision-Language Models Trust What They Can Discern. *eXCV @ ECCV '26.*
3. **V. Vankadaru**, A. Matthews, T. Roosta, P. Passban. Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination. *DAIH @ COLM '26.* [arXiv:2607.00158](https://arxiv.org/abs/2607.00158)
4. A. Matthews, **V. Vankadaru**, T. Roosta, P. Passban. Rethinking Medical LLM Hallucinations: A System-Level Survey. *Intelligence-Based Medicine*, to appear.
5. E. S. Danthinne, **V. Vankadaru**, et al. Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making: A Sociodemographic Subgroup Assessment Approach for Open-Source Glioma Molecular Subtype Classifiers. Under review.
6. A. Ge, **V. Vankadaru**, X. Liu, et al. Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction. Under review.
7. **V. Vankadaru**. A Recipe for Multimodal Multi-Instance Depression Detection: Frozen Teachers, Schedule-Aware Training, and Audio Contribution Diagnostics. Under review, ACL Rolling Review.

## Research Experience

**Graduate Researcher, UC Berkeley**. *With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell). Apr 2026 to present.*
- I study how vision-language models choose between an image and a prior that contradicts it. The first paper showed on one model that trust in the image tracks how discernible the conflicting evidence is (first author, eXCV @ ECCV '26).
- The second paper tests this across eleven models from eight architectures and locates the shared mid-depth pathway that carries the image's evidence to the answer (first author, under review at CVPR '27).

**Graduate Researcher, UC Berkeley**. *With [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta). Jan 2026 to present.*
- I led a neuron-level study of hallucination in medical LLMs. Linear probes on hidden activations detect hallucination (AUROC 0.77 to 0.86), but steering the same neurons does not reliably change the output (first author, DAIH @ COLM '26).
- Co-wrote a survey of hallucination in medical LLMs (*Intelligence-Based Medicine*, to appear).

**Machine Learning Research Fellow, M2AI Lab, UCSF**. *With [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil). Jun 2026 to present.*
- Tested three published glioma MRI classifiers on 3,380 patients from a new hospital. Overall scores look stable across patient groups, but the models make more errors on younger patients.
- Built an LLM pipeline that reads pathology reports, so that every patient group had enough labels to test.

**Machine Learning Research Fellow, The Tensor Lab, University of Maryland School of Medicine (UMSOM)**. *Jun 2026 to present.*
- Designed Bio MAF v4, an interpretable representation of a tumor's somatic mutations. On 8,800 tumors it identified cancer type more accurately than a mutation transformer trained from scratch under the same compute budget.
- I work there with Aaron Ge, Xingyan Liu, and [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/).

## Industry Experience

**Machine Learning Engineer, DASION**. *Sep 2023 to present.*
- Built a depression detection model that uses clinical interview audio and transcripts, and reports how much each modality contributed. Written up as a solo-author paper, under review.
- Deployed models as AWS inference endpoints for partner institutions.

**Machine Learning Engineering Intern, DASION**. *Sep 2021 to Sep 2023.*
- Trained imaging classifiers for lung and cardiac scans and a BERT model for clinical documentation.

## Service

- Reviewer, InterpScience @ NeurIPS '26
- Reviewer, Actionable Interpretability @ COLM '26
- Reviewer, eXCV @ ECCV '26

## Training

BlueDot Impact, Technical AI Safety course, 2026.

## Skills

Python, PyTorch, TransformerLens, Hugging Face, scikit-learn, XGBoost, SQL, C++, R, AWS, Docker, Linux, LaTeX
