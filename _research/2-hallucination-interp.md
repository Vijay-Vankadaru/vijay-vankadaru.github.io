---
title: "Neuron-level hallucination in medical LLMs"
excerpt: "Linear probes on hidden activations detect hallucination in medical LLMs at AUROC 0.77 to 0.86, yet steering the same neurons does not reliably change behavior. The project established this detection-control gap across four open-weight models and 36K free-generation answers. Presented at COLM 2026."
collection: research
tags: ["Mechanistic interpretability", "Medical LLMs", "Hallucination"]
subtitle: "UC Berkeley, with Prof. Tanya Roosta. Jan 2026 to present."
---


**Advisor:** [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), UC Berkeley School of Information. With Asha Matthews and Peyman Passban.

**The question.** If a model's activations carry a signal that it is about to hallucinate, can that signal be used to stop it?

**What we did.** Collected MLP and residual-stream activations from BioMistral, Meditron, Llama 3.1, and a general-purpose baseline over roughly 36K free-generation answers to six medical QA datasets, labeling each by comparison to ground truth. Trained linear probes with bootstrap confidence intervals and random-neuron baselines, then ran steering experiments on the neurons most associated with hallucination.

**What we found.** The probe works (AUROC 0.77 to 0.86) and the signal is spread across many neurons. Steering those neurons does not reliably suppress hallucination. Readable is not the same as controllable, which has consequences for any intervention that assumes a detected state can be edited at the same site.

**Paper:** [Readable but Not Controllable](/publication/2026-07-24-readable-not-controllable) (COLM 2026, DAIH), building on the [system-level survey](/publication/2026-06-01-medical-llm-hallucination-survey) that framed the project.
