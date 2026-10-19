---
title: "Clinical ML at DASION"
excerpt: "Four years of building and shipping clinical ML at an NSF-funded startup: a multimodal depression detection model on interview audio and transcripts (F1 0.87 on DAIC-WOZ), imaging classifiers for lung and cardiac scans, and BERT-based clinical documentation tools, deployed on AWS to partner institutions."
collection: research
tags: ["Clinical ML", "Multimodal", "Deployment"]
subtitle: "Machine Learning Engineer since Jun 2025; ML Engineering Intern Sep 2021 to Jun 2025."
---


DASION is a clinical AI startup founded with Prof. Weiqing Gu (Harvey Mudd) and supported by NSF SBIR Phase I and II awards. I joined in 2021 as an intern and have been a Machine Learning Engineer since June 2025.

**Depression detection.** A multimodal multi-instance model over clinical interview audio and transcripts: frozen DepRoBERTa and emotion-finetuned wav2vec2 encoders, gated-attention pooling over interview chunks, and an occlusion diagnostic that reports how much each modality contributed. F1 0.87 on DAIC-WOZ. Written up as a [solo-author paper](/publication/2026-08-01-multimodal-mil-depression) now under review.

**Imaging and documentation.** ResNet50 transfer-learning classifiers with SHAP explanations for lung and cardiac imaging (93% diagnostic accuracy on small clinical datasets), and BERT fine-tuned for clinical documentation classification that cut manual processing time by 60%.

**Deployment.** Models are served as AWS inference endpoints (SageMaker, Lambda, S3) in Docker to five-plus partner institutions.
