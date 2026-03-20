---
title: 'Industry Experience Is a Research Asset, Not a Gap to Apologize For'
date: 2025-11-18
permalink: /posts/2025/11/industry-experience-as-asset/
tags:
  - research
  - reflection
  - machine learning
  - healthcare AI
---

There's a version of the story I told about myself for a while that went like this: I spent years doing applied work in industry before getting serious about research. That framing treated the industry work as a detour — something to acknowledge and move past.

I don't think that's right anymore.

The thing about building ML systems in a clinical context is that you encounter failure modes that don't show up in benchmarks. A model that achieves strong held-out accuracy can still be wrong in ways that matter — systematically worse on patient subgroups, brittle to distribution shift between clinical sites, confidently incorrect in the edge cases that clinicians actually care about. You only know this if you've watched a system fail in a real setting and had to explain it to someone who trusted it.

That experience is directly relevant to research. It tells you which problems are actually hard, as opposed to which problems look hard from a benchmark perspective. It gives you a calibrated sense of what "good enough" means in practice — and therefore what improvement is genuinely worth pursuing versus what's incremental.

When I started working on the hallucination survey, I kept returning to this. The literature treats hallucination primarily as a model problem — something to be fixed through training or retrieval. But from a deployment perspective, the question is never "does this model hallucinate" (it does) — the question is "what happens when it does, and does the system around it catch it." That's a different problem, and it requires a different kind of solution.

I don't think I would have arrived at that framing from first principles. I arrived at it because I've been on the other side of the deployment, watching what breaks.

The research question I'm most interested in now — when does ML actually work, and what breaks it — is directly shaped by that experience. The years I spent building systems weren't a detour. They were where I learned what to study.
