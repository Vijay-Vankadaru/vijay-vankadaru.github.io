---
title: "Vision-Language Models Trust What They Can Discern"
collection: publications
category: published
permalink: /publication/2026-10-01-vlm-discern/
excerpt: "When an image and the text prompt disagree, CLIP-LLaVA models follow the input they can discern more reliably. Activation patching and logit lens locate where that decision is made."
date: 2026-10-01
venue: "eXCV Workshop, ECCV 2026"
status: "Published"
authors: "<b>V. Vankadaru</b>, V. DuTell"
openreviewurl: "https://openreview.net/pdf?id=FbgTPGKH6x"
citation: "Vankadaru, V., &amp; DuTell, V. (2026). Vision-Language Models Trust What They Can Discern. <i>eXCV Workshop, ECCV 2026</i>."
---

With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell).

A vision-language model that is shown an image and asked a question has two sources of evidence: what it can see, and what its language prior expects. This paper asks what happens when the two conflict. Using a semantic image pair protocol, we construct cases where the image and the text disagree on a property such as color, count, or material, then measure which side wins and why.

The short answer is that these models are neither blindly text-driven nor blindly image-driven. They follow whichever input they can discern more reliably. Degrading the image shifts trust to the prior; sharpening it shifts trust back. Activation patching and logit lens show where in the network the arbitration happens and how it builds up across layers.

A full-length extension, *Believing Is Seeing*, covers three CLIP-LLaVA models, four conflict sources, and an evaluation on real photographs, and is under review at ICLR 2027.
