---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**University of California, Berkeley** — M.S. Information and Data Science (MIDS), GPA: 4.0
Expected August 2026. Relevant coursework: Applied Machine Learning, Natural Language Processing, Computer Vision.

**University of California, Riverside** — B.S. Computer Science, GPA: 4.0
June 2025.

---

## Research Experience

**Graduate Research Assistant** — UC Berkeley (Advisor: Prof. Tanya Roosta)
January 2026 – Present

- Co-authored systems-level survey on hallucination in medical LLMs, synthesizing 50+ papers on structural mechanisms, detection, mitigation, and benchmarking through a risk management lens. Published MetaArXiv March 2026.
- Developing novel detection and mitigation methods for LLMs building on survey findings, targeting submission to a top-tier ML venue.

**Graduate Research Assistant** — UC Berkeley (Advisor: Prof. Cornelia Paulik)
August 2025 – Present

- Built RAG pipeline for pediatric medical QA combining dense encoders and sparse retrieval (BM25) with cross-encoder reranking, improving accuracy by 34% and reducing hallucinations by 42% over baseline.
- Developed PyTorch classifiers for age-group segmentation (0–2, 3–5, 6–12, 13–18), achieving 94% accuracy for targeted QA.

**Machine Learning Researcher** — DASION (Research collaboration with Prof. Weiqing Gu, Harvey Mudd College)
September 2021 – Present, Claremont, CA (Remote)

- Developed multimodal depression detection using Wav2Vec 2.0 audio and MT5/RoBERTa text transformers with CTC temporal alignment and multi-instance learning, achieving F1=0.94 on DAIC-WOZ.
- Secured $2.5M in NSF Phase I and II funding for clinical ML research. Led team of 8 engineers building production ML infrastructure on AWS, achieving 99.9% uptime and deploying to 5+ institutions.
- Built interpretable CNN models using PyTorch and SHAP for clinical imaging achieving 93% diagnostic accuracy. Developed BERT-based NLP for clinical documentation reducing manual processing by 60%.

**Machine Learning Research Engineer (Contract)** — Angel Technologies
September 2023 – February 2024, Brea, CA

- Built transformer-based NLP system for automated regulatory compliance detection using fine-tuned BERT models, reducing processing time by 40% and error rates by 85%.
- Developed predictive models using time-series forecasting for customer behavior analysis, improving conversion by 30%.

---

## Publications

**Rethinking Medical LLM Hallucinations: A System-Level Survey**
Matthews, Vankadaru, Roosta, Passban. MetaArXiv, March 2026.
Survey arguing hallucination in medical LLMs is a structural property of probabilistic generation. Synthesizes detection, mitigation, and benchmark literature through a systems and risk management lens.

**Multimodal Multi-Instance Learning for Depression Detection** *(Target: NeurIPS 2026)*
First multimodal MIL framework for depression detection combining MT5/RoBERTa text with Wav2Vec 2.0 audio via CTC temporal alignment. Achieves F1>0.90 on DAIC-WOZ, surpassing text-only MIL baseline (F1=0.88). Directly addresses interviewer bias via strict prompt exclusion.

**PedRAG: Retrieval-Augmented Generation for Pediatric Medical QA** *(Target: ICML Poster 2026)*
RAG framework combining dense and sparse retrieval with age-specific classification, achieving 34% accuracy improvement and 42% hallucination reduction over baselines.

---

## Professional Experience

**Chief Technology Officer** — AGMNT
February 2024 – Present, San Ramon, CA (Hybrid, Part-time)

- Built TensorFlow recommendation engine and full-stack platform (Node.js, React, MongoDB) serving 10K+ users and 15+ brands, improving conversion rates by 28%.
- Implemented A/B testing framework processing 1M+ daily events to drive product decisions.

**Machine Learning Intern** — Ambassadore Healthcare Inc.
May 2023 – August 2023, Artesia, CA

- Engineered distributed data pipeline using Kafka and MongoDB processing 100GB+ daily clinical data with statistical modeling in Scala/Spark, achieving 75% storage optimization and sub-100ms query latency.

**Software Engineer Intern** — Royal Majesty Home Care
June 2022 – August 2022, Long Beach, CA

- Built AI scheduling system using decision trees and linear programming, reducing overtime costs by $200K annually.

---

## Technical Skills

**Languages:** Python, R, C++, SQL, JavaScript

**ML/AI:** PyTorch, TensorFlow, Hugging Face, SHAP, MLflow, Pandas, NumPy, Scikit-learn, AWS (SageMaker, Lambda, S3, EC2), Docker, PostgreSQL, MongoDB

**Certifications:** AWS Certified Machine Learning — Specialty (2025), Linear Algebra with Applications in ML (Harvey Mudd College)

---

## Grants and Funding

NSF Phase I and II Grants — $2.5M for clinical ML research (2021–2026), in collaboration with Prof. Weiqing Gu at Harvey Mudd College.

