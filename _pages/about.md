---
permalink: /
title: "Vijay Vankadaru"
excerpt: "ML researcher, mechanistic interpretability"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="hero">
  <div class="hero__eyebrow">Mechanistic interpretability / Clinical ML</div>
  <p class="hero__lead">I study why models say things that contradict what they already know, and I test the answers where a confident wrong answer has a cost: <em>medicine</em>.</p>
  <p class="hero__status"><b>Applying to PhD programs for Fall 2027</b><span>/</span>MS Data Science, UC Berkeley, May 2027<span>/</span>UC Berkeley, UCSF, UMSOM, DASION</p>
</div>

I am a master's student in data science at UC Berkeley working on mechanistic interpretability of language and vision-language models. The question I keep coming back to: when a model already holds the right information internally, what makes its output contradict it? I am applying to PhD programs this cycle for a Fall 2027 start.

My interpretability work runs on two threads. With [Dr. Vasha DuTell](https://www.ischool.berkeley.edu/people/vasha-dutell), I study how vision-language models arbitrate between an image and text that contradicts it, using activation patching and logit lens to find where the decision is made. With [Prof. Tanya Roosta](https://www.ischool.berkeley.edu/people/tanya-roosta), I led a neuron-level study of hallucination in medical LLMs that found a gap between reading a model's state and steering it: linear probes on hidden activations detect hallucination reliably, yet intervening on the same neurons does not suppress it.

Medicine is where I validate these methods. At the [UCSF M2AI Lab](https://profiles.ucsf.edu/madhumita.sushil), I externally validated three published glioma MRI classifiers on 3,380 patients and found age-driven errors that AUROC alone hides, after building an LLM pipeline that labeled 9,377 pathology reports to make the subgroup tests possible. At the [University of Maryland School of Medicine](https://www.medschool.umaryland.edu/profiles/maron-bradley/), I designed Bio MAF v4, a new interpretable representation of a tumor's somatic mutations, and showed in a compute-matched benchmark that it beats a mutation transformer trained from scratch for cancer typing. And at DASION, a clinical AI startup, I have built and deployed ML systems since 2021, including a multimodal depression detection model on clinical interviews now written up as a solo-author paper.

## Selected papers

<ul class="papers">
  <li><div class="venue"><b>ECCV 2026</b>eXCV · first author</div><div><span class="title"><a href="/publication/2026-10-01-vlm-discern/">Vision-Language Models Trust What They Can Discern</a></span><span class="note">Models follow whichever input they can discern more reliably. Activation patching locates where the decision forms.</span></div></li>
  <li><div class="venue"><b>COLM 2026</b>DAIH · first author</div><div><span class="title"><a href="/publication/2026-07-24-readable-not-controllable/">Readable but Not Controllable</a></span><span class="note">Probes detect hallucination in medical LLMs at AUROC 0.77 to 0.86; steering the same neurons does not suppress it.</span></div></li>
  <li><div class="venue"><b>ICLR 2027</b>under review</div><div><span class="title"><a href="/publication/2026-09-30-believing-is-seeing/">Believing Is Seeing</a></span><span class="note">Three LLaVA models, four conflict sources, real photographs, and a trust law that holds across them.</span></div></li>
  <li><div class="venue"><b>AI in Medicine</b>in press</div><div><span class="title"><a href="/publication/2026-06-01-medical-llm-hallucination-survey/">Rethinking Medical LLM Hallucinations</a></span><span class="note">A system-level survey arguing hallucination is a risk to manage, not a bug to patch.</span></div></li>
</ul>

<p class="quicklinks"><a href="/publications/">All publications</a> &nbsp;/&nbsp; <a href="/research/">Research</a> &nbsp;/&nbsp; <a href="/curriculum-vitae/">CV</a></p>

## Research interests

<ul class="interests-list">
  <li><div><b>Mechanistic interpretability</b><span>Activation patching, probing, steering, and the cases where they come apart.</span></div></li>
  <li><div><b>Hallucination and cross-modal conflict</b><span>How models weigh evidence against their priors, and whether that decision can be read before the output is written.</span></div></li>
  <li><div><b>Clinical ML that holds up</b><span>Evaluation that reflects deployment, subgroup analysis, representations that stay interpretable, detection that is not LLM-as-judge.</span></div></li>
</ul>

## News

<ul class="timeline">
<li><time>Oct 2026</time><span>Presented <em>Readable but Not Controllable</em> at the DAIH workshop, COLM 2026, San Francisco.</span></li>
<li><time>Sep 2026</time><span><em>Believing Is Seeing</em>, the full-length extension of the ECCV paper, submitted to ICLR 2027.</span></li>
<li><time>Aug 2026</time><span><em>Vision-Language Models Trust What They Can Discern</em> accepted to the eXCV workshop at ECCV 2026.</span></li>
<li><time>Jul 2026</time><span><em>Readable but Not Controllable</em> accepted at COLM 2026; preprint on <a href="https://arxiv.org/abs/2607.00158">arXiv</a>.</span></li>
<li><time>Jun 2026</time><span>Joined the UCSF M2AI Lab (Dr. Madhumita Sushil) and the Maron group at UMSOM (Dr. Bradley Maron) through The Tensor Lab.</span></li>
<li><time>2026</time><span><em>Rethinking Medical LLM Hallucinations: A System-Level Survey</em> accepted at <em>Artificial Intelligence in Medicine</em>.</span></li>
<li><time>2026</time><span>Reviewer for InterpScience (NeurIPS 2026), Actionable Interpretability (COLM 2026), and eXCV (ECCV 2026).</span></li>
<li><time>Apr 2026</time><span>Began working with Dr. Vasha DuTell on modality arbitration in vision-language models.</span></li>
<li><time>Jan 2026</time><span>Began working with Prof. Tanya Roosta on hallucination in medical LLMs.</span></li>
</ul>
