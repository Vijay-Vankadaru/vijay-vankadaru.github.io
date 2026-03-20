---
title: "Rethinking Medical LLM Hallucinations: A System-Level Survey"
excerpt: "Co-authored survey arguing hallucination in medical LLMs is a structural property of probabilistic generation. Published MetaArXiv March 2026."
collection: portfolio
---

## Overview

Co-authored with Asha Matthews, Prof. Tanya Roosta, and Prof. Peyman Passban
at the UC Berkeley School of Information.

Published MetaArXiv, March 2026.
[Read the paper](https://osf.io/cw7zy/files/ngbdv)

## The Argument

Prior research has treated hallucination as an isolated model failure to be
fixed through better training, prompting, or retrieval. This survey reframes
it: hallucination is a structural property of probabilistic language generation.
The implication for healthcare is significant — the question isn't how to
eliminate hallucinations, but how to operate safely given that they are
unavoidable.

## What We Surveyed

50+ papers spanning definitions and taxonomies, benchmarks and evaluation
protocols, detection methods, mitigation strategies, and interpretability
research. Examined how these components interact in real clinical workflows
rather than in isolation.

## Key Findings

**Benchmark fragmentation** — Current benchmarks evaluate QA tasks, not the
temporal reasoning, causal inference, and evolving clinical guidelines that
real workflows require. Improvements on benchmarks don't reliably predict
end-to-end system safety.

**Detection limits** — LLM-as-judge detection methods inherit the same failure
modes they're designed to catch. Useful as a triage signal, not as a
standalone safeguard.

**Almost-right errors** — The most dangerous hallucinations in medicine are
not obviously wrong. Subtly outdated dosages, plausible but fabricated
references, reversed causal sequences — these pass surface-level checks
while introducing real harm.

**Interpretability gap** — Representation instability and shallow
memorization may underlie confident but incorrect medical reasoning.
Mitigation methods don't address these underlying mechanisms.

## Conclusion

Trustworthy medical AI requires layered defenses and honest uncertainty
management, not a search for a hallucination-free model. The paper frames
this as a systems engineering and risk management problem.

## Ongoing Work

Active follow-on research developing novel detection and mitigation methods
building on the survey's framework, with Prof. Tanya Roosta at UC Berkeley.
Target: top-tier ML venue.
