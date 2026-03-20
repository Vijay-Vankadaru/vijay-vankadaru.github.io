---
title: 'Hallucination is Structural, Not Accidental'
date: 2026-03-05
permalink: /posts/2026/03/hallucination-is-structural/
tags:
  - LLMs
  - hallucination
  - medical AI
  - research
---

The standard framing of LLM hallucination is as a bug. Train better. Prompt better. Retrieve better. The bug will eventually go away.

Working on our survey on hallucination in medical LLMs changed how I think about this. The more carefully you look at the literature, the more it becomes clear that hallucination isn't an engineering failure waiting to be fixed — it's a structural property of how autoregressive language models work.

Here's the core issue: these models are trained to predict the most likely next token given context. Not to ensure factual correctness. Not to model uncertainty. Just to predict likely continuations. A model that has learned the statistical structure of medical text will generate fluent, coherent, medically-plausible text. Whether that text is *true* is a separate question — one the training objective doesn't directly address.

Theoretical work has started to formalize this. You can show that under standard assumptions, no language model can guarantee zero hallucination. This isn't a statement about capability limits or insufficient data. It's a statement about what the objective function is actually optimizing.

In healthcare, this matters in a specific way. The dangerous hallucinations in medicine are rarely obvious. They're not "the patient has four kidneys." They're: subtly outdated drug dosages, plausible but nonexistent clinical trial citations, disease progression sequences that are almost right but causally reversed. These pass surface-level plausibility checks. They look like good answers. They're the ones that hurt patients.

The implication is that the question "how do we eliminate hallucination" is probably the wrong question. The right question is "how do we build systems that remain safe in the presence of unavoidable hallucination." That's a systems engineering problem, not a model training problem. It requires layered detection, uncertainty quantification, human-in-the-loop escalation paths, and honest acknowledgment that the model will sometimes be wrong in ways you can't fully anticipate.

The field is slowly moving in this direction. Detection methods, RAG pipelines, runtime verification systems like CHECK — these are all partial answers to the right question. What's still missing is end-to-end evaluation that reflects actual clinical risk rather than benchmark accuracy, and deployment frameworks that treat hallucination as a lifecycle problem rather than a pre-deployment checkbox.

That's what we tried to map out in the survey. More work coming.
