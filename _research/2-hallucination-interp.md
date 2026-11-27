---
title: "Hallucination inside medical LLMs"
excerpt: "If a model's activations show that it is about to hallucinate, can that signal be used to stop it? Linear probes detect hallucination in medical LLMs (AUROC 0.77 to 0.86), but steering the same neurons does not reliably change the output. Detecting a state and controlling it are separate problems."
collection: research
tags: ["Interpretability", "Medical LLMs"]
subtitle: "UC Berkeley, with Prof. Tanya Roosta. Jan 2026 to present."
links:
  - label: "Readable but Not Controllable (DAIH @ COLM '26)"
    url: "/publication/2026-07-24-readable-not-controllable/"
  - label: "arXiv"
    url: "https://arxiv.org/abs/2607.00158"
  - label: "Survey (Intelligence-Based Medicine, to appear)"
    url: "/publication/2026-06-01-medical-llm-hallucination-survey/"
posterurl: "/files/posters/vankadaru-daih-colm26-poster.pdf"
posterimg: "/images/posters/daih-colm26.jpg"
---

With [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta) at UC Berkeley, Asha Matthews, and Peyman Passban.

We started with a survey of hallucination in medical LLMs. It argued that hallucination comes from how these models generate text, and it found little interpretability work on medical models.

The follow-up asks whether a hallucination signal inside the model can be used to stop the hallucination. Linear probes on hidden activations detect it with AUROC between 0.77 and 0.86. Steering the neurons that carry the signal does not reliably change what the model says. Reading a state and controlling it are separate problems.

**Papers**

- [Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination](/publication/2026-07-24-readable-not-controllable/). DAIH @ COLM '26.
- [Rethinking Medical LLM Hallucinations: A System-Level Survey](/publication/2026-06-01-medical-llm-hallucination-survey/). Intelligence-Based Medicine, to appear.
