---
title: "Modality arbitration in vision-language models"
excerpt: "How does a vision-language model decide whether to trust an image or its own language prior when the two disagree? Using a semantic image pair protocol on CLIP-LLaVA models, activation patching, and logit lens, we showed that models follow whichever input they can discern more reliably, and located where in the network that decision forms. First paper at ECCV 2026 (eXCV); full-length extension under review at ICLR 2027."
collection: research
tags: ["Mechanistic interpretability", "Vision-language models"]
subtitle: "UC Berkeley, with Dr. Vasha DuTell. Apr 2026 to present."
---


**Advisor:** [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell), UC Berkeley School of Information.

**Question.** A vision-language model has two sources of evidence for any answer: the image and its language prior. When they disagree, which one wins, and where in the network is that decided?

**Findings so far.** On CLIP-LLaVA models, trust in the image tracks how well the model can discern the queried property from it. Degrading the image shifts the answer toward the prior; sharpening it shifts the answer back. Activation patching and logit lens show the decision forming in the middle layers rather than at the input.

**Next.** Whether the behavior follows one reliability-weighted function across models, whether the decision can be read from the residual stream before an answer is generated, and whether steering the heads involved moves trust in either direction without side effects elsewhere.

**Papers:** [Vision-Language Models Trust What They Can Discern](/publication/2026-10-01-vlm-discern) (ECCV 2026, eXCV); [Believing Is Seeing](/publication/2026-09-30-believing-is-seeing) (under review, ICLR 2027).
