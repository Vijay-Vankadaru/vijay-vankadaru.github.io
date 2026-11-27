---
title: "How vision-language models decide to believe an image"
excerpt: "When an image contradicts what a vision-language model expects, which one does it follow, and where in the network is that decided? Across eleven models from eight architectures, the deciding evidence sits in the object that contradicts the prior and reaches the answer through the same mid-depth pathway in every model. Removing that evidence is far easier than restoring it."
collection: research
tags: ["Interpretability", "Vision-language models"]
subtitle: "UC Berkeley, with Dr. Vasha DuTell. Apr 2026 to present."
links:
  - label: "Believing Is Seeing (CVPR '27, under review)"
    url: "/publication/2026-09-30-believing-is-seeing/"
  - label: "Trust What They Can Discern (eXCV @ ECCV '26)"
    url: "/publication/2026-10-01-vlm-discern/"
  - label: "OpenReview"
    url: "https://openreview.net/pdf?id=FbgTPGKH6x"
posterurl: "/files/posters/vankadaru-excv-eccv26-poster.pdf"
posterimg: "/images/posters/excv-eccv26.jpg"
---

With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell) at UC Berkeley.

A vision-language model has two sources for an answer: the image, and what it expects to see. When they disagree, the model often answers from its expectation, and the answer reads just as fluently, so a user cannot tell the image was set aside. I study what the model weighs in that choice and where in the network the choice is made.

The first paper showed on one model that trust in the image tracks how discernible the conflicting evidence is. The second tests this across eleven models from eight architectures. The deciding evidence sits in the object that contradicts the prior, and it reaches the answer through the same mid-depth pathway in every model, where a few attention heads write it in. Removing that evidence is far easier than restoring it, so a correction has to act on that pathway and not on the input image.

**Papers**

- [Believing Is Seeing: How Vision-Language Models Decide to Believe an Image](/publication/2026-09-30-believing-is-seeing/). Under review at CVPR '27.
- [Vision-Language Models Trust What They Can Discern](/publication/2026-10-01-vlm-discern/). eXCV @ ECCV '26.
