---
title: "Where a Language Switch Costs a Language Model: Word-Level Switch Cost in Natural Code-Switched Text"
collection: publications
category: preprint
permalink: /publication/2026-11-28-switch-cost/
excerpt: "We measure what a language switch costs a language model at the word where it happens, on natural code-switched text in four language pairs. In trained models the first word in the new language is more surprising than earlier words of the same utterances, the cost fades within three words, and flipping the preceding context along one direction that separates the languages lowers it by about the size of the cost."
date: 2026-11-28
venue: ""
status: "Preprint, 2026"
authors: "<b>V. Vankadaru</b>, L. Ye"
# paperurl is the short link. The short link opens pdffile.
paperurl: "/switch-cost/"
paperlabel: "PDF"
pdffile: "/files/papers/Vankadaru_Ye_switch_cost_preprint.pdf"
---

With Luan Ye at UC Berkeley.

Bilingual speakers switch languages inside a sentence, and language models read such text. We measure what a switch costs a language model at the word where it happens, on natural Spanish-English, Welsh-English, Welsh-Spanish and Hindi-English text with word-level language tags.

In trained models from two families, the first word in the new language is more surprising than earlier words of the same utterances. The cost fades within three words and is nearly absent in randomly initialized models. Flipping the preceding context along one residual-stream direction that separates the languages lowers that word's surprisal by about the size of the cost. These results locate the difficulty of mixed-language text at the switch point and tie it to one direction of the context.

## BibTeX

```bibtex
@misc{vankadaru2026switchcost,
  title        = {Where a Language Switch Costs a Language Model: Word-Level Switch Cost in Natural Code-Switched Text},
  author       = {Vankadaru, Vijay and Ye, Luan},
  year         = {2026},
  note         = {Preprint},
  howpublished = {\url{https://vijay-vankadaru.github.io/switch-cost/}}
}
```
