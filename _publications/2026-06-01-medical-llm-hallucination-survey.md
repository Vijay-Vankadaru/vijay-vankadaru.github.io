---
title: "Rethinking Medical LLM Hallucinations: A System-Level Survey"
collection: publications
category: published
permalink: /publication/2026-06-01-medical-llm-hallucination-survey/
excerpt: "A survey of hallucination in medical LLMs: definitions, benchmarks, detection, and mitigation. We argue that hallucination comes from how these models generate text and has to be managed at the level of the whole system."
date: 2026-06-01
venue: "Intelligence-Based Medicine"
status: "Accepted"
authors: "A. Matthews, <b>V. Vankadaru</b>, T. Roosta, P. Passban"
paperurl: "https://osf.io/cw7zy/files/ngbdv"
paperlabel: "Preprint"
---

With Asha Matthews, [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), and Peyman Passban. Accepted at *Intelligence-Based Medicine*.

Most prior work treats hallucination as a model failure to be fixed through training, prompting, or retrieval. We treat it as a property of how language models generate text. In medicine, the errors that matter most are the ones that are nearly correct, because they pass surface checks.

We review definitions, benchmarks, detection methods, and mitigation strategies, and look at how they interact inside clinical workflows. Improving one component rarely gives a reliable system end to end.

The survey also pointed to a gap: little interpretability work had been done on medical LLMs. [Readable but Not Controllable](/publication/2026-07-24-readable-not-controllable/) is our follow-up.

## BibTeX

```bibtex
@article{matthews2026rethinking,
  title   = {Rethinking Medical LLM Hallucinations: A System-Level Survey},
  author  = {Matthews, Asha and Vankadaru, Vijay and Roosta, Tanya and Passban, Peyman},
  journal = {Intelligence-Based Medicine},
  year    = {2026},
  note    = {Accepted}
}
```
