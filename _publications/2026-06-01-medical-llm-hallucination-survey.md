---
title: "Rethinking Medical LLM Hallucinations: A System-Level Survey"
collection: publications
category: published
permalink: /publication/2026-06-01-medical-llm-hallucination-survey
excerpt: "Hallucination in medical LLMs is a structural property of probabilistic generation, not a bug to be patched. We survey definitions, benchmarks, detection, and mitigation, and argue that progress depends on treating it as a system-level risk management problem."
date: 2026-06-01
venue: "Artificial Intelligence in Medicine (in press)"
paperurl: "https://osf.io/cw7zy/files/ngbdv"
citation: "Matthews, A., Vankadaru, V., Roosta, T., &amp; Passban, P. (2026). Rethinking Medical LLM Hallucinations: A System-Level Survey. <i>Artificial Intelligence in Medicine</i>, in press."
---

With Asha Matthews, [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), and Peyman Passban.

Most prior work treats hallucination as an isolated model failure to be fixed through training, prompting, or retrieval. This survey reframes it: hallucination is a structural property of how probabilistic language models generate text, and in medicine the dangerous errors are the ones that are almost right. We synthesize work on definitions, taxonomies, benchmarks, detection methods, and mitigation strategies, and look at how those pieces interact inside real clinical workflows. Improvements to individual components rarely translate into reliable end-to-end systems.

The survey also named a gap that became the next project: almost no interpretability work had been done on medical LLMs specifically. *Readable but Not Controllable* is the empirical follow-up.
