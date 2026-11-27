---
title: "Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination"
collection: publications
category: published
permalink: /publication/2026-07-24-readable-not-controllable/
excerpt: "Linear probes on hidden activations detect hallucination in medical LLMs (AUROC 0.77 to 0.86). Steering the same neurons does not reliably change what the model says. Detecting a state and controlling it are separate problems."
date: 2026-07-24
venue: "DAIH @ COLM '26"
status: "Published"
authors: "<b>V. Vankadaru</b>, A. Matthews, T. Roosta, P. Passban"
arxivurl: "https://arxiv.org/abs/2607.00158"
posterurl: "/files/posters/vankadaru-daih-colm26-poster.pdf"
posterimg: "/images/posters/daih-colm26.jpg"
---

With Asha Matthews, [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), and Peyman Passban. I presented this at the DAIH workshop at COLM '26 in San Francisco.

If a model's activations show that it is about to hallucinate, can that signal be used to stop it? We collected activations from open medical and general-purpose LLMs while they answered medical questions, and labeled each answer against ground truth. A linear probe on those activations detects hallucination with AUROC between 0.77 and 0.86, and the signal is spread across many neurons.

We then tried to use the signal. Steering the neurons most associated with hallucination, in either direction, does not reliably change what the model says. Reading a state from activations does not mean the behavior can be controlled through the same neurons.

All results use the model's own free-form answers, not pre-written hallucinated text.

## BibTeX

```bibtex
@inproceedings{vankadaru2026readable,
  title     = {Readable but Not Controllable: Neuron-Level Evidence for Medical LLM Hallucination},
  author    = {Vankadaru, Vijay and Matthews, Asha and Roosta, Tanya and Passban, Peyman},
  booktitle = {DAIH Workshop at COLM},
  year      = {2026},
  note      = {arXiv:2607.00158}
}
```
