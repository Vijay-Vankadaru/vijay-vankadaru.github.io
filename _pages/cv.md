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

Work and Research Experience
======
* Sep 2021 - Present: Founding Machine Learning Engineer & Researcher
  * DASION (Healthcare AI Startup)
  * Focus: Multimodal AI systems for clinical applications, voice-based depression detection
  * Collaborating with Professor Weiqing Gu (Harvey Mudd College) on NSF-funded research
  * Developed computer vision models for medical imaging achieving 93% diagnostic accuracy with clinical validation studies
  * Built voice analysis ML pipeline for depression detection achieving 85% classification accuracy with clinical evaluation
  * Architected serverless cloud infrastructure supporting real-time clinical inference

* Feb 2024 - Present: CTO & Co-Founder
  * AGMNT (Recommendation Engine Startup)
  * Focus: Multimodal recommendation systems and user behavior analysis
  * Built production recommendation engine using collaborative filtering algorithms, improving conversion rates by 28%
  * Designed full-stack application with A/B testing framework for user behavior analysis

* Sep 2023 - Feb 2024: Machine Learning Engineer (Contract)
  * Angel Technologies
  * Focus: NLP solutions for regulatory compliance and predictive analytics
  * Developed enterprise NLP solution using transformer-based models, reducing processing time by 40% and errors by 85%

* May 2023 - Aug 2023: Machine Learning Intern
  * Ambassadore Healthcare Inc.
  * Focus: Distributed data processing and statistical modeling
  * Engineered data pipeline processing 100GB+ daily data with 75% storage optimization and statistical inference methods

* Jun 2022 - Aug 2022: Software Engineer Intern
  * Royal Majesty Home Care
  * Focus: AI-driven optimization algorithms and real-time systems
  * Created scheduling optimization system using linear programming algorithms, improving operational efficiency by 40%

Technical Skills
======
* Machine Learning & AI: TensorFlow, PyTorch, Hugging Face, multimodal fusion, computer vision, NLP, audio processing, model interpretability (SHAP, MLflow)
* Programming: Python, Java, JavaScript, TypeScript, C++, SQL, Scala
* Cloud & Infrastructure: AWS (Lambda, SageMaker, S3, EC2), GCP, Docker, Kubernetes, Apache Spark, Kafka
* Databases: MongoDB, PostgreSQL
* Web Development: React, Node.js, Express.js, Django, Flask

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
* Multimodal AI systems for healthcare applications
* Voice-based clinical assessment and depression detection
* Interpretable machine learning for clinical decision support
* Real-time audio processing and sentiment analysis
* Cross-modal knowledge transfer and efficient neural architectures

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
