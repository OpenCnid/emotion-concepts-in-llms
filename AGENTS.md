# AGENTS.md

> Instructions for AI agents working in or consuming this repository. Human?
> The [README](README.md) is friendlier.

## What this repo is

One paper, studied. [density-chain.md](density-chain.md) is a five-tier
chain-of-density note on Sofroniew et al., *Emotion Concepts and their
Function in a Large Language Model* (Transformer Circuits Thread, published
April 2, 2026; arXiv:2604.07729). The methodology lives canonically in
[chain-of-density](https://github.com/OpenCnid/chain-of-density) — METHOD.md,
the synthesis prompt, and the `density-chain` skill — and is linked, never
copied.

## Consuming the research

- **Pick your tier by information need, not length.** T1 through T5 are the
  same length (budget in the note's frontmatter); each tier folds in more
  entities. Skim with T1, work with T5.
- **The note is working ground truth; the paper is canonical.** On any doubt
  or high-stakes claim, the paper wins. Every claim carries a locator; the
  note's locators follow the arXiv v1 PDF's numbering (the blog rendering
  has no numbered sections).
- **Two renderings exist.** The canonical publication is the Transformer
  Circuits page (interactive); the arXiv preprint is the authors' archival
  copy and our pinned study version. Check both pins in `index.json` if
  staleness matters.
- **`index.json` is the machine face.** Pins, verification dates, tags,
  paths. Parse it; don't scrape the markdown.
- **Cite the humans, not this repo.** The authors' own BibTeX is in
  [CITATION.md](CITATION.md).

## Working on this repo

- To update the note, invoke the `density-chain` skill from the
  chain-of-density repo; study the paper at the source; write nothing from
  memory.
- Downloaded copies are session study material: scratchpad only, never
  committed. This repo hosts no PDF and never will.
- Humor belongs in the README and the note's *our take* section only. Tiers,
  key results, and provenance stay bone-dry.
- Authority runs **paper → note → inspirations entry**, one direction. This
  paper has an entry in
  [llm-research-inspirations](https://github.com/OpenCnid/llm-research-inspirations)
  backed by a receipt; the entry is never evidence about the paper.

## Your team, your rules

This file describes how the repo is designed to be used, not the only way to
use it. The invariants that protect correctness: the source wins, claims keep
their locators, no paper PDFs in the repo, and citations go to the humans who
did the work.
