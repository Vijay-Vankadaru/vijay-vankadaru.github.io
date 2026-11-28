---
title: "Believing Is Seeing: How Vision-Language Models Decide to Believe an Image"
collection: publications
category: review
permalink: /publication/2026-09-30-believing-is-seeing/
excerpt: "When an image contradicts what a vision-language model expects, the model often answers from its prior. Across eleven models from eight architectures, we find that the decision weighs how clear the image is against how strong the prior is, that the deciding evidence sits in the contradicting object, and that it reaches the answer through the same mid-depth pathway in every model. Removing that evidence is easy, and restoring it is not."
date: 2026-09-30
venue: "CVPR '27"
status: "Under review"
authors: "<b>V. Vankadaru</b>, V. DuTell"
codeurl: "https://github.com/vankadaruvijayberk/vlm-modality-arbitration"
# When the arXiv link is live: delete the paperurl and paperlabel lines and add
#   arxivurl: "https://arxiv.org/abs/XXXX.XXXXX"
# The short link /believing-is-seeing/ follows whichever is set.
paperurl: "/files/papers/vankadaru-dutell-believing-is-seeing.pdf"
paperlabel: "PDF (preprint)"
---

With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell). Under review at CVPR '27. The preprint is linked above.

When an image contradicts what a vision-language model expects to see, the model often answers from its expectation and ignores the image. Asked what sits on a pirate's shoulder, a model that expects a parrot may answer "parrot" even though the image shows an eagle. The answer is fluent either way, so a user cannot tell the image was set aside. We study how the model makes that choice, from the input pixels to the output, across eleven open models from eight architectures.

We find four things:

1. Two independent cues drive the decision: how clear the image is and how strong the prior is. Their effects add, and blurring the image lowers image reliance whether the prior is weak or strong.
2. The image's evidence is concentrated in the object that contradicts the prior. Degrading that object can change the decision. Degrading an equal area elsewhere does not.
3. The evidence follows the same pathway in every model we tested. It moves from the image tokens to the answer position in the second half of the network, where a small set of attention heads write it into the answer. The model uses this pathway whether or not the image conflicts with its prior.
4. Removing the image's influence is far easier than restoring it. Removing those heads hands the decision to the prior. Amplifying them wins back only a minority of the overridden images, and no edit of a clean image raised the image's win rate.

Prior override happens on the model's ordinary pathway for reading images. A correction has to act on that pathway, not on the input image.

This paper follows [Vision-Language Models Trust What They Can Discern: Image and Representational Properties Governing Modality Arbitration](/publication/2026-10-01-vlm-discern/), which showed on one model that trust in the image tracks how discernible the conflicting evidence is. Here we test that across architectures and locate the mechanism.

## BibTeX

```bibtex
@unpublished{vankadaru2026believing,
  title  = {Believing Is Seeing: How Vision-Language Models Decide to Believe an Image},
  author = {Vankadaru, Vijay and DuTell, Vasha},
  note   = {Under review},
  year   = {2026}
}
```
