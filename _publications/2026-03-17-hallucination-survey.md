---
title: "Rethinking Medical LLM Hallucinations: A System-Level Survey"
collection: publications
category: manuscripts
permalink: /publication/2026-03-17-hallucination-survey
excerpt: 'A systems-level survey arguing that hallucination in medical LLMs is a structural property of probabilistic generation, not a fixable bug. Synthesizes 50+ papers on detection, mitigation, and benchmarking through a risk management lens.'
date: 2026-03-17
venue: 'MetaArXiv'
paperurl: 'https://osf.io/cw7zy/files/ngbdv'
citation: 'Matthews, A., Vankadaru, V., Roosta, T., & Passban, P. (2026). Rethinking Medical LLM Hallucinations: A System-Level Survey. MetaArXiv.'
---

Co-authored with Asha Matthews, Prof. Tanya Roosta, and Prof. Peyman Passban
at the UC Berkeley School of Information.

The core argument: hallucination in medical AI is not a bug you fix. It is a
structural property of how probabilistic language models generate text. Prior
research has treated hallucination as an isolated model failure to be addressed
through improved training, prompting, or retrieval. This survey reframes it as
a system-level risk management problem.

We synthesize literature spanning definitions, taxonomies, benchmarks, detection
methods, and mitigation strategies, and examine how these components interact
within real clinical workflows. The analysis shows that despite diverse models
and technical advances, improvements to individual components rarely translate
into reliable end-to-end clinical systems.

**Key findings:**
- Current benchmarks mostly evaluate QA tasks, not the temporal reasoning,
  causal inference, and evolving guidelines that real clinical workflows require.
- Detection methods (including LLM-as-judge) inherit the same failure modes
  they are designed to catch.
- The most dangerous hallucinations in medicine are not obviously wrong —
  they are almost right.

[Download paper](https://osf.io/cw7zy/files/ngbdv)
