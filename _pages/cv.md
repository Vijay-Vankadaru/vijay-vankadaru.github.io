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

**University of California, Riverside**, Bachelor of Science in Computer Science. Jun 2025.

## Publications

1. **V. Vankadaru**, V. DuTell. Vision-Language Models Trust What They Can Discern: Image and Representational Properties Governing Modality Arbitration. *eXCV @ ECCV '26 (Proceedings Track; Springer, in press).* [Paper](https://openreview.net/pdf?id=FbgTPGKH6x), [poster](/files/posters/vankadaru-excv-eccv26-poster.pdf).
2. **V. Vankadaru**, A. Matthews, T. Roosta, P. Passban. Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination. *DAIH @ COLM '26.* [arXiv:2607.00158](https://arxiv.org/abs/2607.00158), [poster](/files/posters/vankadaru-daih-colm26-poster.pdf).
3. **V. Vankadaru**, V. DuTell. Believing Is Seeing: How Vision-Language Models Decide to Believe an Image. Under review at CVPR '27. [PDF](/believing-is-seeing/).
4. E. S. Danthinne, **V. Vankadaru**, et al. Potential for Age-Based Bias in AI-Informed Neurosurgical Decision-Making: A Sociodemographic Subgroup Assessment Approach for Open-Source Glioma Molecular Subtype Classifiers. Under review. [Poster](/files/posters/danthinne-vankadaru-glioma-subgroup-poster.pdf).
5. A. Ge, **V. Vankadaru**, X. Liu, et al. Benchmarking Somatic Mutation Representations for Cancer Typing and HRD Prediction. Under review.
6. A. Matthews, **V. Vankadaru**, T. Roosta, P. Passban. Rethinking Medical LLM Hallucinations: A System-Level Survey. *Intelligence-Based Medicine*, accepted.

## Research Experience

**Graduate Researcher, UC Berkeley**. *Advisor: [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell). Apr 2026 to present.*
- Studied when a vision-language model believes an image over what it expects to see. It trusts the image only when it can clearly discern the contradicting object, and that choice can be read inside the model before it answers. First author, eXCV @ ECCV '26.
- Extended this to eleven open models across eight architectures and to GPT, Claude and Gemini. All eleven make the choice through the same internal pathway, and it is far easier to make a model ignore an image than believe it. First author, under review at CVPR '27.

**Graduate Researcher, UC Berkeley**. *Advisor: [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta). Jan 2026 to present.*
- Led a neuron-level study of hallucination in four medical LLMs. Linear probes detect it at AUROC 0.77 to 0.86, but the signal is spread across hundreds of neurons and steering it does no better than random neurons in 16 settings. First author, DAIH @ COLM '26.
- Wrote the interpretability and system-level sections of a survey on medical LLM hallucination. Accepted at *Intelligence-Based Medicine*.

**Graduate Researcher, UC Berkeley**. *Advisor: [Dr. Cornelia Paulik](https://corneliailin.github.io). Sep 2025 to Jan 2026.*
- Built the retrieval corpus for a pediatric medical question-answering system and contributed to its model evaluations and literature review.

**Machine Learning Research Fellow, M2AI Lab, UCSF**. *Advisor: [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil). Jun 2026 to present.*
- Externally validated three open-source MRI classifiers (3D CNN, ViT with ClinicalBERT, CNN with radiomics) on a 3,380-patient cohort and showed that errors AUROC hides are driven by age: specificity 54% for patients under 40 vs 80% for 55 and older.
- Scaled ground-truth labels from 442 to 3,380 patients with an LLM extraction pipeline over 9,377 pathology reports (F1 0.96 to 0.97).

**Machine Learning Research Fellow, The Tensor Lab, University of Maryland School of Medicine (UMSOM)**. *With [Dr. Bradley A. Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/). Jun 2026 to present.*
- Designed Bio MAF v4, a 948-feature interpretable representation of a tumor's somatic mutations, and benchmarked it against mutational signatures and a from-scratch MuAt transformer on 8,800 TCGA tumors across 20 cancer types and 913 held-out PCAWG tumors.
- Its features with XGBoost beat the transformer on cancer typing (0.74 vs 0.53 balanced accuracy) and HRD status (AUROC 0.91 vs 0.75).

## Industry Experience

**Machine Learning Engineer, DASION** (clinical AI startup, NSF SBIR Phase I and II). *Claremont, CA. Sep 2023 to present.*
- Built a multimodal depression detection model on clinical interview audio and transcripts in PyTorch (wav2vec2 and RoBERTa encoders, gated-attention multi-instance pooling), reaching F1 0.87 on DAIC-WOZ with occlusion diagnostics for per-modality attribution.
- Fine-tuned BERT for clinical documentation classification and deployed models as AWS inference endpoints serving 5+ institutions.

**Machine Learning Engineering Intern, DASION**. *Claremont, CA. Jun 2021 to Sep 2023.*
- Trained ResNet50 transfer-learning classifiers in PyTorch for lung and cardiac imaging (93% diagnostic accuracy, k-fold CV, SHAP).
- Built a bidirectional LSTM with attention over MFCC and prosodic features for voice-based depression screening (85% accuracy).

## Honors

- Merit Scholarship and Professional Development Award, UC Berkeley
- First place, Rose Hack. Most Innovative, Cutie Hack.
- Travel grants: UC Berkeley (ECCV '26), DAIH @ COLM '26
- Presenter, DAIH @ COLM '26. Lead fellow presenter, The Tensor Lab.

## Service

- Reviewer, InterpScience @ NeurIPS '26
- Reviewer, Actionable Interpretability @ COLM '26
- Reviewer, eXCV @ ECCV '26

## Training

BlueDot AI Safety course.

## Skills

Python, PyTorch, TransformerLens, Hugging Face, scikit-learn, XGBoost, SQL, C++, R, AWS, Docker, Linux, LaTeX
