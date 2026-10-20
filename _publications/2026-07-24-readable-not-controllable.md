---
title: "Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination"
collection: publications
category: published
permalink: /publication/2026-07-24-readable-not-controllable/
excerpt: "Linear probes on hidden activations detect hallucination in medical LLMs at AUROC 0.77 to 0.86. Steering the neurons most associated with hallucination does not reliably change behavior. Detection and control are separate properties."
date: 2026-07-24
venue: "DAIH Workshop, COLM 2026"
status: "Published"
authors: "<b>V. Vankadaru</b>, A. Matthews, T. Roosta, P. Passban"
arxivurl: "https://arxiv.org/abs/2607.00158"
citation: "Vankadaru, V., Matthews, A., Roosta, T., &amp; Passban, P. (2026). Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination. <i>DAIH Workshop, COLM 2026</i>. arXiv:2607.00158."
---

With Asha Matthews, [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), and Peyman Passban. Presented at the DAIH workshop at COLM 2026 in San Francisco.

We collected activations from four open-weight models (BioMistral, Meditron, Llama 3.1, and a general-purpose baseline) over roughly 36K free-generation answers to six medical QA datasets, labeling each answer by comparison to ground truth. A simple, well-conditioned linear probe on MLP activations detects hallucination with AUROC between 0.77 and 0.86, and the signal is spread across many neurons rather than concentrated in a few.

The second half of the paper tests whether that signal can be used. Steering the neurons most associated with hallucination, in either direction, does not reliably change what the model says. Reading a state from activations does not imply controlling the behavior through the same neurons. This detection-control decoupling is the paper's central finding.

A methodological note that shaped the project: an earlier version of the pipeline scored pre-written hallucinated answers rather than the model's own generations, which inflated AUROC to 0.86 from an honest 0.67. All reported numbers use free generation only.
