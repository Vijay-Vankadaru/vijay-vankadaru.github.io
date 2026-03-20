---
title: "PedRAG: Retrieval-Augmented Generation for Pediatric Medical QA"
excerpt: "RAG pipeline for pediatric medical question-answering combining dense and sparse retrieval with age-specific classification. 34% accuracy improvement, 42% hallucination reduction over baseline."
collection: portfolio
---

## Overview

Built a RAG system for pediatric medical question-answering as Graduate
Research Assistant with Prof. Cornelia Paulik at UC Berkeley. Extends the
MedRAG benchmark to evaluate age-appropriate retrieval and answer generation
across four pediatric cohorts.

Target venue: ICML 2026 (Poster).

## Technical Approach

**Dual-retrieval architecture** — Combines dense encoders (semantic
similarity) with sparse retrieval (BM25 exact term matching) and
cross-encoder reranking. Dense retrieval catches conceptually related
content; sparse retrieval catches precise medical terminology.

**Age-group classification** — PyTorch multi-class classifier segments
queries and documents into four pediatric age groups (0–2, 3–5, 6–12,
13–18), achieving 94% accuracy. Ensures retrieval is age-appropriate —
a dosing recommendation for a 2-year-old is not the same as one for
a 15-year-old.

**Hallucination evaluation** — Evaluated against the MedRAG baseline
on both answer accuracy and hallucination rates, using the PediatricsMQA
dataset.

## Results

- 34% improvement in answer accuracy over baseline
- 42% reduction in hallucination rates over baseline
- 94% age-group classification accuracy
