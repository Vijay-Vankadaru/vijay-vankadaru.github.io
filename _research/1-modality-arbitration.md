---
title: "Modality arbitration in vision-language models"
excerpt: "How does a vision-language model decide whether to trust an image or its own language prior when the two disagree? Using a semantic image pair protocol on CLIP-LLaVA models, activation patching, and logit lens, we showed that models follow whichever input they can discern more reliably, and located where in the network that decision forms. First paper at ECCV 2026 (eXCV); full-length extension under review at ICLR 2027."
collection: research
tags: ["Mechanistic interpretability", "Vision-language models"]
subtitle: "UC Berkeley, with Dr. Vasha DuTell. Apr 2026 to present."
---


**Advisor:** [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell), UC Berkeley School of Information.

**The question.** Every model that combines a learned prior with an input has to decide how much to trust the input. In vision-language models that decision is measurable, it has a mechanism, and it fails in both directions: the model overrides a clear image with its prior, or it follows a corrupted image it should have discounted.

**What we have found so far.** On CLIP-LLaVA models, trust in the image tracks how well the model can discern the queried property from it. Degrade the image and the prior wins; sharpen it and the image wins. Activation patching and logit lens show the arbitration building up through the middle layers rather than being settled at the input.

**Where it is going.** The follow-on program tests whether that behavior follows a single reliability-weighted law across models, whether the decision can be read from the residual stream before an answer is generated, and whether steering the heads involved can move trust in either direction without breaking the model elsewhere.

**Papers:** [Vision-Language Models Trust What They Can Discern](/publication/2026-10-01-vlm-discern) (ECCV 2026, eXCV); [Believing Is Seeing](/publication/2026-09-30-believing-is-seeing) (under review, ICLR 2027).
