# Curation Policy

## Scope

- Time window: 2022-present.
- Core scope only: story/novel/script generation with LLMs, long-form coherence, controllability, planning, multi-agent narrative generation, multimodal narrative generation, evaluation, and datasets/resources.
- Out of scope: generic LLM papers without direct narrative generation relevance.

## Required Schema

Each row must use:

`Title | Venue | Date | Paper | Project | Citations | Tags`

Rules:

- `Date` format: `YYYY-MM`.
- `Paper` format: one primary link only (`Published` preferred, otherwise `arXiv`; use `-` if unavailable).
- `Project`: project pages, repository links, or demos; use `-` if unavailable.
- `Citations`: badge style `citation-N` when available; otherwise use `-`.
- `Tags`: concise topic tags.

## Category Taxonomy (Fixed Order)

1. Planning / Decomposition for Story Generation
2. Agent Collaboration for Story Writing
3. Sandbox / World Simulation Narrative Generation
4. Multimodal Story Generation (Text-Image/Video/Comic/Audio)
5. Memory & Long-Context Coherence
6. Consistency / Controllability / Constraint Following
7. Refinement / Self-Critique / Iterative Editing
8. Evaluation / Benchmarks / Metrics
9. Datasets / Surveys / Resources
10. Open-source Projects (No Paper Required)

## Sorting and Mirror Rules

- Sort rows inside each category by `Date` descending.
- `README.md` and `README_zh.md` must keep the same category order and row order.
- Entry titles should stay in original language (usually English) in both files.
