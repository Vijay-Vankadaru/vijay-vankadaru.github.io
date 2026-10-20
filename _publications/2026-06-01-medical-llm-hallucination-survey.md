---
title: "Rethinking Medical LLM Hallucinations: A System-Level Survey"
collection: publications
category: published
permalink: /publication/2026-06-01-medical-llm-hallucination-survey/
excerpt: "A survey of hallucination in medical LLMs covering definitions, benchmarks, detection, and mitigation. It argues that hallucination is a structural property of probabilistic generation and should be treated as a system-level risk management problem."
date: 2026-06-01
venue: "Artificial Intelligence in Medicine"
status: "In press"
authors: "A. Matthews, <b>V. Vankadaru</b>, T. Roosta, P. Passban"
paperurl: "https://osf.io/cw7zy/files/ngbdv"
citation: "Matthews, A., Vankadaru, V., Roosta, T., &amp; Passban, P. (2026). Rethinking Medical LLM Hallucinations: A System-Level Survey. <i>Artificial Intelligence in Medicine</i>, in press."
---

With Asha Matthews, [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), and Peyman Passban.

Most prior work treats hallucination as an isolated model failure to be fixed through training, prompting, or retrieval. This survey treats hallucination as a structural property of how probabilistic language models generate text. In medicine, the errors that matter most are the ones that are nearly correct, because they pass surface checks. We synthesize work on definitions, taxonomies, benchmarks, detection methods, and mitigation strategies, and look at how those pieces interact inside real clinical workflows. Improvements to individual components rarely translate into reliable end-to-end systems.

The survey also named a gap that became the next project: almost no interpretability work had been done on medical LLMs specifically. *Readable but Not Controllable* is the empirical follow-up.
