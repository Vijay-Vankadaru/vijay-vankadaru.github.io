---
permalink: /
title: "Vijay Vankadaru"
excerpt: "ML researcher, mechanistic interpretability"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="lead">I study why models say things that contradict what they already know, and I test the answers where a confident wrong answer has a cost: medicine.</p>

<div class="stats">
  <div class="stat"><b>3</b><span>peer-reviewed papers, two as first author (ECCV 2026, COLM 2026)</span></div>
  <div class="stat"><b>4</b><span>manuscripts under review, including ICLR 2027</span></div>
  <div class="stat"><b>4</b><span>research groups: UC Berkeley, UCSF, UMSOM, DASION</span></div>
</div>

I am a master's student in data science at UC Berkeley working on mechanistic interpretability of language and vision-language models. The question I keep coming back to: when a model already holds the right information internally, what makes its output contradict it? I will be applying to PhD programs in Fall 2026 for a Fall 2027 start.

My interpretability work runs on two threads. With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell), I study how vision-language models arbitrate between an image and text that contradicts it, using activation patching and logit lens to find where the decision is made. The first paper, [Vision-Language Models Trust What They Can Discern](/publication/2026-10-01-vlm-discern), appears at ECCV 2026 (eXCV), and the full-length extension, [Believing Is Seeing](/publication/2026-09-30-believing-is-seeing), is under review at ICLR 2027. With [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), I led a neuron-level study of hallucination in medical LLMs that found a gap between reading a model's state and steering it: linear probes on hidden activations detect hallucination reliably, yet intervening on the same neurons does not suppress it. That paper, [Readable but Not Controllable](/publication/2026-07-24-readable-not-controllable), was presented at COLM 2026.

Medicine is where I validate these methods. At the [UCSF M2AI Lab](https://profiles.ucsf.edu/madhumita.sushil), I externally validated three published glioma MRI classifiers on 3,380 patients and found age-driven errors that AUROC alone hides, after building an LLM pipeline that labeled 9,377 pathology reports to make the subgroup tests possible. At the [University of Maryland School of Medicine](https://www.medschool.umaryland.edu/profiles/maron-bradley/), I designed Bio MAF v4, a new interpretable representation of a tumor's somatic mutations, and showed in a compute-matched benchmark that it beats a mutation transformer trained from scratch for cancer typing. And at DASION, a clinical AI startup, I have built and deployed ML systems since 2021, including a multimodal depression detection model on clinical interviews now written up as a solo-author paper.

## Research interests

- Mechanistic interpretability: activation patching, probing, steering, and the cases where they come apart
- Hallucination and cross-modal conflict: how models weigh evidence against their priors, and whether that decision can be read before the output is written
- Clinical ML that holds up: evaluation that reflects deployment, subgroup analysis, representations that stay interpretable, and detection methods that are not LLM-as-judge

## News
{: .news-head}

<ul class="news">
<li><b>Oct 2026</b> Presented <em>Readable but Not Controllable</em> at the DAIH workshop, COLM 2026, San Francisco.</li>
<li><b>Sep 2026</b> <em>Believing Is Seeing</em>, the full-length extension of the ECCV paper, submitted to ICLR 2027.</li>
<li><b>Aug 2026</b> <em>Vision-Language Models Trust What They Can Discern</em> accepted to the eXCV workshop at ECCV 2026.</li>
<li><b>Jul 2026</b> <em>Readable but Not Controllable</em> accepted at COLM 2026; preprint on <a href="https://arxiv.org/abs/2607.00158">arXiv</a>.</li>
<li><b>Jun 2026</b> Joined the UCSF M2AI Lab (Dr. Madhumita Sushil) and the Maron group at UMSOM (Dr. Bradley Maron) through The Tensor Lab.</li>
<li><b>2026</b> <em>Rethinking Medical LLM Hallucinations: A System-Level Survey</em> accepted at <em>Artificial Intelligence in Medicine</em>.</li>
<li><b>2026</b> Reviewer for InterpScience (NeurIPS 2026), Actionable Interpretability (COLM 2026), and eXCV (ECCV 2026).</li>
<li><b>Apr 2026</b> Began working with Dr. Vasha DuTell on modality arbitration in vision-language models.</li>
<li><b>Jan 2026</b> Began working with Prof. Tanya Roosta on hallucination in medical LLMs.</li>
</ul>
