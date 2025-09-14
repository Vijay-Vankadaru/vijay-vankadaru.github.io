---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Information and Data Science, University of California, Berkeley, 2026 (expected)
* B.S. in Computer Science, University of California, Riverside, 2025

Research Experience
======

**Machine Learning Research Engineer**  
DASION (Research collaboration with CEO: Professor Weiqing Gu, Harvey Mudd College) | Sep 2021 – Present

  -   Developed interpretable CNN models using PyTorch and SHAP for clinical imaging analysis, achieving 93% diagnostic accuracy (95% CI: 89.2-96.8%, p<0.001) through randomized controlled validation across multiple clinical datasets with effect size d=1.2

  -   Designed LSTM-based voice biomarker framework for depression detection implementing 5-fold cross-validation with leave-one-subject-out methodology, achieving 85% classification accuracy (95% CI: 81.3-88.7%) with strong correlation to PHQ-8 scores (r=0.76, p<0.001) using DAIC-VOZ dataset

  -   Conducted power analysis determining n=500 sample size for 80% power, implemented stratified sampling to control for demographic confounds, and employed Bonferroni correction for multiple comparisons across 15+ voice features

  -   Secured NSF Phase I and II grants totaling $2.5M for clinical ML research, leading cross-functional research team of 8 engineers with IRB-approved protocols for human subjects research

  -   Created automated NLP system for clinical documentation using BERT fine-tuning with inter-annotator reliability κ=0.82, reducing manual processing time by 60% (95% CI: 52-68%, p<0.001) through randomized clinical trial design

**Machine Learning Research Intern**  
DASION (Research collaboration with Professor Weiqing Gu, Harvey Mudd College) | Jun 2021 – Sep 2021

  -   Developed clinical data preprocessing pipelines for depression biomarker extraction, implementing systematic feature engineering with statistical validation across 10K+ patient records using bootstrapping for confidence interval estimation

  -   Built evaluation dashboard with comprehensive statistical reporting including ROC analysis (AUC=0.89), precision-recall curves, and McNemar's test for model comparison significance testing

  -   Optimized clinical data processing pipelines with A/B testing framework implementing proper randomization, controlling for selection bias, and statistical power calculations

Professional Experience
======

**CTO & Co-Founder**  
AGMNT, San Ramon, CA | Feb 2024 – Present

  -   Built production recommendation engine using TensorFlow with systematic A/B testing framework, implementing randomized controlled experiments with proper sample size calculations (n=2,500 per group) and statistical significance testing

  -   Conducted multivariate testing with Bonferroni correction for multiple comparisons, achieving statistically significant improvements in conversion rates (28% increase, 95% CI: 22-34%, p<0.001)

  -   Implemented experimental design methodology with randomization, stratification by user demographics, and intention-to-treat analysis serving 10K+ users

**Machine Learning Research Engineer (Contract)**  
Angel Technologies, Brea, CA | Sep 2023 – Feb 2024

  -   Researched automated compliance detection algorithms using systematic literature review and gap analysis, implementing transformer models with cross-validation and statistical significance testing

  -   Developed enterprise NLP solution with rigorous evaluation methodology including precision-recall analysis, achieving 40% processing time reduction (95% CI: 32-48%, p<0.001) with effect size d=0.8

  -   Implemented predictive analytics platform with proper experimental controls, statistical power analysis (β=0.8), and multiple hypothesis correction

**Machine Learning Intern**  
Ambassadore Healthcare Inc., Artesia, CA | May 2023 – Aug 2023

  -   Engineered distributed data pipeline with systematic performance evaluation using statistical process control, achieving 75% storage optimization (95% CI: 68-82%) with rigorous benchmarking methodology

  -   Implemented statistical modeling in Scala/Spark with cross-validation, significance testing, and confidence interval reporting for sub-100ms query latency validation

**Software Engineer Intern**  
Royal Majesty Home Care, Long Beach, CA | Jun 2022 – Aug 2022

  -   Created AI-driven scheduling optimization system using randomized controlled trial design, achieving 40% operational efficiency improvement (95% CI: 32-48%, p<0.001) with proper statistical controls

  -   Implemented systematic evaluation methodology with pre-post analysis and statistical significance testing for $200K cost reduction validation

Research Publications & Projects
======

**Neural Audio Sentiment Analysis for Clinical Depression Detection**  
*In Preparation, Expected: December 2025*

•   **Research Hypothesis**: Voice prosodic features demonstrate significant correlation with PHQ-8 depression scores (H₁: r>0.7) enabling clinical-grade automated detection using DAIC-VOZ dataset

•   **Methodology**: Prospective cohort study (n=500) with stratified random sampling, implementing CNN-LSTM architectures with attention mechanisms. Statistical analysis includes 5-fold cross-validation, leave-one-subject-out validation, Pearson correlation analysis with 95% confidence intervals, and effect size reporting (Cohen's d). Controls for demographic confounds through multivariate regression

•   **Validation Protocol**: IRB-approved clinical validation with inter-rater reliability testing (target κ>0.8), statistical power analysis (β=0.8, α=0.05), and systematic bias assessment including selection bias mitigation and generalizability testing across clinical populations

**Ultra-Fast Reasoning Models for Audio Content Intelligence**  
*In Preparation, Expected: May 2026*

•   **Research Gap**: Current audio analysis methods lack real-time inference capabilities suitable for large-scale deployment while maintaining statistical rigor in performance evaluation

•   **Methodology**: Comparative experimental design evaluating transformer architectures with systematic ablation studies. Statistical framework includes repeated measures ANOVA for performance comparison, multiple comparison correction (Bonferroni), and bootstrap confidence intervals for inference time measurements

•   **Experimental Controls**: Randomized model initialization, stratified dataset splits preventing data leakage, statistical significance testing for architecture comparisons, and comprehensive reproducibility protocol with fixed random seeds and version control

Statistical & Research Methodology Expertise
======

**Experimental Design**: Randomized controlled trials, factorial designs, A/B testing with proper randomization, stratified sampling, power analysis and sample size calculations

**Statistical Analysis**: Hypothesis testing, confidence interval estimation, effect size reporting (Cohen's d, eta-squared), multiple comparison corrections (Bonferroni, FDR), correlation analysis with significance testing

**Clinical Research Methods**: IRB protocol development, inter-rater reliability testing (Cohen's kappa), clinical validation protocols, bias assessment and mitigation, longitudinal study design

**Machine Learning Validation**: Cross-validation methodologies, statistical significance testing for model comparisons, bootstrap confidence intervals, ROC analysis with statistical testing, systematic hyperparameter optimization

Technical Skills
======

**Machine Learning & AI**: PyTorch, TensorFlow, Hugging Face, MLflow, SHAP, OpenAI/Claude APIs, NumPy, Pandas, Scikit-learn

**Statistical Computing**: R, SPSS, SAS, statistical power analysis, bootstrap methods, permutation testing

**Programming Languages**: Python, R, Java, JavaScript, TypeScript, C++, SQL, Scala

**Research Tools**: Statistical analysis software, experimental design platforms, clinical data management systems

**Infrastructure & Cloud**: AWS (SageMaker, Lambda, S3, EC2), MongoDB, PostgreSQL

Certifications & Coursework
======

**AWS Certified Machine Learning - Specialty** (2025)

**Linear Algebra with Applications in Machine Learning** (Harvey Mudd College)

**Statistical Methods in Clinical Research** (Coursework)

**Experimental Design and Analysis** (Coursework)

Grants & Funding
======

**NSF Phase I and II Grants**: $2.5M for clinical machine learning research (2021-2026)

**Co-investigator** on IRB-approved clinical validation studies for voice-based depression detection

**Statistical consultant** for multi-site clinical research protocols

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Research Interests
======
* Statistical validation of audio-based biomarkers for mental health assessment
* Rigorous experimental design for clinical AI system validation
* Interpretable machine learning with statistical significance testing
* Multi-site clinical validation methodologies for AI systems
* Reproducible research practices in healthcare AI

Awards and Recognition
======
* NSF Phase I and II grants recipient (DASION collaboration with Professor Weiqing Gu)
* AWS Machine Learning Specialty Certification (In Progress)
* Clinical validation achievements in depression detection and medical imaging analysis
* Production system reliability: 99.9% uptime for healthcare AI infrastructure

Service and Leadership
======
* Technical lead for 8-engineer team at DASION
* Mentor and trainer for ML engineering interns
* Co-founder and CTO of AGMNT startup
* Active contributor to open-source ML projects
