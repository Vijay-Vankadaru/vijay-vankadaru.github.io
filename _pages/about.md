---
permalink: /
title: "Vijay Vankadaru"
excerpt: "ML researcher, mechanistic interpretability"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a master's student in data science at UC Berkeley, where I work on mechanistic interpretability of language and vision-language models. The question I keep coming back to: when a model already holds the right information internally, what makes its output contradict it? I will be applying to PhD programs in Fall 2026 for a Fall 2027 start.

My current work splits into two threads. With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell), I study how vision-language models arbitrate between an image and text that contradicts it, using activation patching and logit lens to find where the decision is made. The first paper, [Vision-Language Models Trust What They Can Discern](/publications/), appears at ECCV 2026 (eXCV), and a full-length extension is under review at ICLR 2027. With [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), I led a neuron-level study of hallucination in medical LLMs that found a gap between reading a model's state and steering it: linear probes on hidden activations detect hallucination reliably, yet intervening on the same neurons does not suppress it. That paper, [Readable but Not Controllable](/publications/), was presented at COLM 2026.

Clinical settings are where I validate these methods, not a separate interest. I have built ML systems at DASION, a clinical AI startup, since 2021, and I collaborate with [Dr. Madhumita Sushil](https://profiles.ucsf.edu/madhumita.sushil) at UCSF on subgroup fairness of MRI classifiers and with [Dr. Bradley Maron](https://www.medschool.umaryland.edu/profiles/maron-bradley/) at the University of Maryland School of Medicine on representations of somatic mutations for cancer typing. Medicine makes the cost of a confident wrong answer concrete, which is why detection and control of model failures is the problem I want to spend a PhD on.

## Research interests

- Mechanistic interpretability: activation patching, probing, steering, and where they come apart
- Hallucination and cross-modal conflict: how models weigh evidence against their priors, and whether that decision can be read before the output is written
- Evaluation that reflects deployment: free-generation benchmarks, subgroup analysis, and detection methods that are not LLM-as-judge

## News

- **Oct 2026** Presented *Readable but Not Controllable* at the DAIH workshop, COLM 2026, San Francisco.
- **Sep 2026** *Believing Is Seeing*, the full-length extension of the ECCV paper, submitted to ICLR 2027.
- **Aug 2026** *Vision-Language Models Trust What They Can Discern* accepted to the eXCV workshop at ECCV 2026.
- **Jul 2026** *Readable but Not Controllable* accepted at COLM 2026; preprint on [arXiv](https://arxiv.org/abs/2607.00158).
- **Jun 2026** Started research collaborations with the UCSF M2AI Lab (Dr. Madhumita Sushil) and UMSOM (Dr. Bradley Maron) through The Tensor Lab.
- **2026** *Rethinking Medical LLM Hallucinations: A System-Level Survey* accepted at *Artificial Intelligence in Medicine*.
- **2026** Reviewer for InterpScience (NeurIPS 2026), Actionable Interpretability (COLM 2026), and eXCV (ECCV 2026).
- **Apr 2026** Began working with Dr. Vasha DuTell on modality arbitration in vision-language models.
- **Jan 2026** Began working with Prof. Tanya Roosta on hallucination in medical LLMs.
