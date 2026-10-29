---
layout: single
title: Creative Problem Solving in Science
permalink: /science/
---

We focus on **theoretical sciences** (math, theoretical CS, physics, etc.) where progress centers on definitions, conjectures, reductions, constructions, heuristics, and proof strategies. These are the fields AI is changing first, so they are where we study how people and models solve problems *together*: whether the human stays engaged, and whether the exploration stays diverse.

**What we collect (beta)**

- **Task briefs** (problem framing, priors, constraints)
- **Interaction transcripts** (curated “episodes” with turns, branches, rationales)
- **Milestones** (new lemmas, promising directions, dead-ends)
- **Outcome labels** (novelty, utility, correctness proxy, “breakthrough points”)

**Why this matters**

- **Evaluation:** we score the *collaboration*, not only the final answer: the human's share of the outcome, the moves along the way, and exploration moves if any.
- **Training:** collaborative sessions become training data for models that brainstorm *with* people instead of only answering them.

**Roadmap**

- **Released:** [AGC-Bench](https://huggingface.co/agcbench-2026), a meta-benchmark for measuring creativity in LLMs — 67 benchmarks across six domains, 83 models scored, an open-weight judge, and a public leaderboard.
- **Released:** the [CrowdMath dataset](https://arxiv.org/abs/2606.06526): 164 research discussions from ten years of the MIT PRIMES CrowdMath program, each traced from an open problem to a finished proof, with every post labeled by experts for its role - progress, proof, error, etc.
- **Now:** the brainstorm arena, in closed beta, where we pilot better ways for humans to interact with models. Mathematicians work with frontier models on open problems while we vary how the models take part: in different roles, several at once, or speaking up unprompted. [Join the Beta →]({{ site.baseurl }}/join/)
- **Next:** a public arena and co-creativity benchmark, scoring sessions for the human's share of the outcome and the diversity of exploration; and post-training of open-weight models on collaborative sessions, as a proof of concept for the labs.
