# Awesome LLM Story Generation

A curated list of story/novel/script generation research in the LLM era (2022-present), organized by method with strict link verification.

- Total entries: **129**
- Categories: **10**
- Last verified: **2026-02-27**
- Language: [English](./README.md) | [中文](./README_zh.md)

## Contents

- [Category Overview](#category-overview)
- [Papers and Projects](#papers-and-projects)
- [Planning / Decomposition for Story Generation](#planning)
- [Agent Collaboration for Story Writing](#agent-collaboration)
- [Sandbox / World Simulation Narrative Generation](#sandbox-world-simulation)
- [Multimodal Story Generation (Text-Image/Video/Comic/Audio)](#multimodal-story-generation)
- [Memory & Long-Context Coherence](#memory-long-context)
- [Consistency / Controllability / Constraint Following](#consistency-controllability)
- [Refinement / Self-Critique / Iterative Editing](#refinement-self-critique)
- [Evaluation / Benchmarks / Metrics](#evaluation-benchmarks)
- [Datasets / Surveys / Resources](#datasets-surveys)
- [Open-source Projects (No Paper Required)](#open-source-projects)
- [Maintenance Notes](#maintenance-notes)
- [Citation](#citation)

## Category Overview

| Category | Entries |
| --- | ---: |
| Planning / Decomposition for Story Generation | 15 |
| Agent Collaboration for Story Writing | 4 |
| Sandbox / World Simulation Narrative Generation | 9 |
| Multimodal Story Generation (Text-Image/Video/Comic/Audio) | 6 |
| Memory & Long-Context Coherence | 9 |
| Consistency / Controllability / Constraint Following | 18 |
| Refinement / Self-Critique / Iterative Editing | 12 |
| Evaluation / Benchmarks / Metrics | 24 |
| Datasets / Surveys / Resources | 22 |
| Open-source Projects (No Paper Required) | 10 |

## Papers and Projects

Note: the `Code` column is removed; repository/demo links are consolidated in `Project`.

<a id="planning"></a>
### Planning / Decomposition for Story Generation

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| DPWriter: Reinforcement Learning with Diverse Planning Branching for Creative Writing | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.09609) | - | - | planning, narrative-structure |
| Codified Foreshadowing-Payoff Text Generation | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.07033) | - | - | planning, narrative-structure |
| SceneDecorator: Towards Scene-Oriented Story Generation with Scene Planning and Scene Consistency | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.22994) | - | - | planning, narrative-structure |
| Long Story Generation via Knowledge Graph and Literary Theory | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.03137) | - | - | planning, narrative-structure |
| STORYTELLER: An Enhanced Plot-Planning Framework for Coherent and Cohesive Story Generation | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.02347) | - | - | planning, narrative-structure |
| Can LLMs Generate Good Stories? Insights and Challenges from a Narrative Planning Perspective | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.10161) | - | - | planning, narrative-structure |
| Learning to Reason for Long-Form Story Generation | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.22828) | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | planning, narrative-structure |
| Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement | NAACL 2025 (North American Chapter of ACL) | 2024-12 | [arXiv](https://arxiv.org/abs/2412.13575) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | planning, narrative-structure |
| Ex3: Automatic Novel Writing by Extracting, Excelsior and Expanding | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.08506) | - | ![citation](https://img.shields.io/badge/citation-2-0A66C2) | planning, narrative-structure |
| Navigating the Path of Writing: Outline-guided Text Generation with Large Language Models | NAACL 2025 (North American Chapter of ACL) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.13919) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | planning, narrative-structure |
| Creating Suspenseful Stories: Iterative Planning with Large Language Models | EACL 2024 (Conference of the European Chapter of ACL) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.17119) | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | planning, narrative-structure |
| Improving Pacing in Long-Form Story Planning | EMNLP Findings 2023 (Findings of EMNLP) | 2023-11 | [arXiv](https://arxiv.org/abs/2311.04459) | - | ![citation](https://img.shields.io/badge/citation-19-0A66C2) | planning, narrative-structure |
| End-to-End Story Plot Generator | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08796) | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | planning, narrative-structure |
| The Next Chapter: A Study of Large Language Models in Storytelling | ArXiv 2023 (arXiv preprint) | 2023-01 | [arXiv](https://arxiv.org/abs/2301.09790) | - | - | planning, narrative-structure |
| DOC: Improving Long Story Coherence With Detailed Outline Control | ArXiv 2022 (arXiv preprint) | 2022-12 | [arXiv](https://arxiv.org/abs/2212.10077) | - | - | planning, narrative-structure |

<a id="agent-collaboration"></a>
### Agent Collaboration for Story Writing

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| A Cognitive Writing Perspective for Constrained Long-Form Text Generation | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.12568) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | multi-agent, collaboration |
| Agents' Room: Narrative Generation through Multi-step Collaboration | ICLR 2025 (International Conference on Learning Representations) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.02603) | - | ![citation](https://img.shields.io/badge/citation-16-0A66C2) | multi-agent, collaboration |
| HoLLMwood: Unleashing the Creativity of Large Language Models in Screenwriting via Role Playing | EMNLP Findings 2024 (Findings of EMNLP) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.11683) | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | multi-agent, collaboration |
| AutoAgents: A Framework for Automatic Agent Generation | IJCAI 2024 (International Joint Conference on Artificial Intelligence) | 2023-09 | [arXiv](https://arxiv.org/abs/2309.17288) | - | ![citation](https://img.shields.io/badge/citation-129-0A66C2) | multi-agent, collaboration |

<a id="sandbox-world-simulation"></a>
### Sandbox / World Simulation Narrative Generation

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| StoryBox: Collaborative Multi-Agent Simulation for Hybrid Bottom-Up Long-Form Story Generation Using Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.11618) | [Project](https://storyboxproject.github.io) | - | sandbox, simulation |
| OPEN-THEATRE: An Open-Source Toolkit for LLM-based Interactive Drama | ArXiv 2025 (arXiv preprint) | 2025-09 | [arXiv](https://arxiv.org/abs/2509.16713) | - | - | sandbox, interactive |
| HAMLET: Hyperadaptive Agent-based Modeling for Live Embodied Theatrics | ArXiv 2025 (arXiv preprint) | 2025-07 | [arXiv](https://arxiv.org/abs/2507.15518) | - | - | sandbox, simulation |
| STORY2GAME: Generating (Almost) Everything in an Interactive Fiction Game | ArXiv 2025 (arXiv preprint) | 2025-05 | [arXiv](https://arxiv.org/abs/2505.03547) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | sandbox, interactive |
| BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation | ArXiv 2025 (arXiv preprint) | 2025-04 | [arXiv](https://arxiv.org/abs/2504.14538) | [Project](https://bookworld2025.github.io) | - | sandbox, interactive |
| Towards Enhanced Immersion and Agency for LLM-based Interactive Drama | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.17878) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | sandbox, interactive |
| IBSEN: Director-Actor Agent Collaboration for Controllable and Interactive Drama Script Generation | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01093) | - | ![citation](https://img.shields.io/badge/citation-16-0A66C2) | sandbox, interactive |
| StoryVerse: Towards Co-authoring Dynamic Plot with LLM-based Character Simulation via Narrative Planning | FDG 2024 (Foundations of Digital Games) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.13042) | - | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | sandbox, simulation |
| Generative Agents: Interactive Simulacra of Human Behavior | ArXiv 2023 (arXiv preprint) | 2023-04 | [arXiv](https://arxiv.org/abs/2304.03442) | [Project](https://github.com/joonspk-research/generative_agents) | - | sandbox, interactive |

<a id="multimodal-story-generation"></a>
### Multimodal Story Generation (Text-Image/Video/Comic/Audio)

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| Re:Verse -- Can Your VLM Read a Manga? | ICCV AISTORY Workshop 2025 (ICCV AISTORY Workshop) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.08508) | - | - | multimodal, visual-story |
| Lay2Story: Extending Diffusion Transformers for Layout-Togglable Story Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.08949) | - | - | multimodal, visual-story |
| R^2: A LLM BASED NOVEL-TO-SCREENPLAY GENERATION FRAMEWORK WITH CAUSAL PLOT GRAPHS | ICLR 2025 (International Conference on Learning Representations) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.15655) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | multimodal, screenplay |
| LongWriter-V: Enabling Ultra-Long and High-Fidelity Generation in Vision-Language Models | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.14834) | - | - | multimodal, visual-story |
| SEED-Story: Multimodal Long Story Generation with Large Language Model | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.08683) | - | - | multimodal, visual-story |
| Make-A-Story: Visual Memory Conditioned Consistent Story Generation | CVPR 2023 (Conference on Computer Vision and Pattern Recognition) | 2022-11 | [arXiv](https://arxiv.org/abs/2211.13319) | - | - | multimodal, visual-story |

<a id="memory-long-context"></a>
### Memory & Long-Context Coherence

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| Shifting Long-Context LLMs Research from Input to Output | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.04723) | - | - | long-context, coherence |
| Language Models can Self-Lengthen to Generate Long Texts | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.23933) | - | - | long-context, coherence |
| LongGenBench: Benchmarking Long-Form Generation in Long-Context LLMs | ArXiv 2024 (arXiv preprint) | 2024-09 | [Published](https://openreview.net/forum?id=3A71qNKWAS) | - | - | long-context, coherence |
| LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs | ArXiv 2024 (arXiv preprint) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.07055) | - | - | long-context, coherence |
| LongLaMP: A Benchmark for Personalized Long-form Text Generation | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.11016) | - | - | long-context, coherence |
| CHIRON: Rich Character Representations in Long-Form Narratives | EMNLP Findings 2024 (Findings of EMNLP) | 2024-06 | [Published](https://aclanthology.org/2024.findings-emnlp.499/) | - | - | long-context, coherence |
| With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation | COLM 2024 (Conference on Language Modeling) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.11504) | - | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | long-context, coherence |
| LongAlign: A Recipe for Long Context Alignment of Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.18058) | - | - | long-context, coherence |
| RecurrentGPT: Interactive Generation of (Arbitrarily) Long Text | ArXiv 2023 (arXiv preprint) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.13304) | [Project](https://github.com/aiwaves-cn/RecurrentGPT) | ![citation](https://img.shields.io/badge/citation-64-0A66C2) | long-context, interactive |

<a id="consistency-controllability"></a>
### Consistency / Controllability / Constraint Following

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| TaleFrame: An Interactive Story Generation System with Fine-Grained Control and Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-12 | [arXiv](https://arxiv.org/abs/2512.02402) | - | - | controllability, interactive |
| SCORE: Story Coherence and Retrieval Enhancement for AI Narratives | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.23512) | - | ![citation](https://img.shields.io/badge/citation-17-0A66C2) | controllability, retrieval |
| Whose story is it? Personalizing story generation by inferring author styles | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.13028) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| Pastiche Novel Generation Creating: Fan Fiction You Love in Your Favorite Author's Style | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.15616) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| CS4: Measuring the Creativity of Large Language Models Automatically by Controlling the Number of Story-Writing Constraints | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.04197) | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | controllability, consistency |
| Crafting Narrative Closures: Zero-Shot Learning with SSM Mamba for Short Story Ending Generation | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.10848) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| MirrorStories: Reflecting Diversity through Personalized Narrative Generation with Large Language Models | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.13935) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| FACTTRACK: Time-Aware World State Tracking in Story Outlines | NAACL 2025 (North American Chapter of ACL) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.16347) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| Suri: Multi-constraint Instruction Following for Long-form Text Generation | ArXiv 2024 (arXiv preprint) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.19371) | - | - | controllability, consistency |
| MoPS: Modular Story Premise Synthesis for Open-Ended Automatic Story Generation | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.05690) | [Project](https://github.com/GAIR-NLP/MoPS) | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| Measuring Psychological Depth in Language Models | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.12680) | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | controllability, consistency |
| Guiding and Diversifying LLM-Based Story Generation via Answer Set Programming | ACL Workshop 2025 (ACL Workshop) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.00554) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| Multigenre AI-powered Story Composition | ArXiv 2024 (arXiv preprint) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.06685) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| Returning to the Start: Generating Narratives with Related Endpoints | NAACL 2024 (North American Chapter of ACL) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.00829) | [Project](https://github.com/adbrei/RENarGen) | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| NarrativeGenie: Generating Narrative Beats and Dynamic Storytelling with Large Language Models | AIIDE 2024 (Conference on Artificial Intelligence and Interactive Digital Entertainment) | 2024-01 | [Published](https://ojs.aaai.org/index.php/AIIDE/article/view/31868) | - | - | controllability, consistency |
| CAT-LLM: Prompting Large Language Models with Text Style Definition for Chinese Article-style Transfer | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.05707) | - | ![citation](https://img.shields.io/badge/citation-13-0A66C2) | controllability, consistency |
| Learning to Generate Text in Arbitrary Writing Styles | ArXiv 2023 (arXiv preprint) | 2023-12 | [arXiv](https://arxiv.org/abs/2312.17242) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| RLCD: Reinforcement Learning from Contrast Distillation for Language Model Alignment | ICLR 2024 (International Conference on Learning Representations) | 2023-07 | [arXiv](https://arxiv.org/abs/2307.12950) | - | ![citation](https://img.shields.io/badge/citation-24-0A66C2) | controllability, consistency |

<a id="refinement-self-critique"></a>
### Refinement / Self-Critique / Iterative Editing

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| LLM Review: Enhancing Creative Writing via Blind Peer Review Feedback | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.08003) | - | - | refinement, revision |
| All Stories Are One Story: Emotional Arc Guided Procedural Game Level Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.02132) | - | - | refinement, revision |
| SuperWriter: Reflection-Driven Long-Form Generation with Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.04180) | - | - | refinement, revision |
| Finding Flawed Fictions: Evaluating Complex Reasoning in Language Models via Plot Hole Detection | ArXiv 2025 (arXiv preprint) | 2025-04 | [arXiv](https://arxiv.org/abs/2504.11900) | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | refinement, revision |
| MLD-EA: Check and Complete Narrative Coherence by Introducing Emotions and Actions | ArXiv 2024 (arXiv preprint) | 2024-12 | [arXiv](https://arxiv.org/abs/2412.02897) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | refinement, revision |
| Collective Critics for Creative Story Generation | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.02428) | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | refinement, revision |
| SWAG: Storytelling With Action Guidance | EMNLP Findings 2024 (Findings of EMNLP) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.03483) | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | refinement, revision |
| GROVE: A Retrieval-augmented Complex Story Generation Framework with A Forest of Evidence | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.05388) | - | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | refinement, retrieval |
| EIPE-text: Evaluation-Guided Iterative Plan Extraction for Long-Form Narrative Text Generation | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08185) | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | refinement, revision |
| Branch-Solve-Merge Improves Large Language Model Evaluation and Generation | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.15123) | - | - | refinement, revision |
| Re3: Generating Longer Stories With Recursive Reprompting and Revision | ArXiv 2022 (arXiv preprint) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.06774) | - | - | refinement, revision |
| Model Criticism for Long-Form Text Generation | ArXiv 2022 (arXiv preprint) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.08444) | - | - | refinement, revision |

<a id="evaluation-benchmarks"></a>
### Evaluation / Benchmarks / Metrics

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| Evaluation Framework for AI Creativity: A Case Study Based on Story Generation | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.03698) | - | - | benchmark, evaluation |
| Evaluating LLM Story Generation through Large-scale Network Analysis of Social Structures | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.18932) | - | - | benchmark, evaluation |
| EvolvR: Self-Evolving Pairwise Reasoning for Story Evaluation to Enhance Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.06046) | - | - | benchmark, evaluation |
| LitBench: A Benchmark and Dataset for Reliable Evaluation of Creative Writing | ArXiv 2025 (arXiv preprint) | 2025-07 | [arXiv](https://arxiv.org/abs/2507.00769) | - | - | benchmark, dataset |
| WritingBench: A Comprehensive Benchmark for Generative Writing | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.05244) | - | - | benchmark, evaluation |
| CoKe: Customizable Fine-Grained Story Evaluation via Chain-of-Keyword Rationalization | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.17136) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | benchmark, evaluation |
| LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.19103) | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| Echoes in AI: Quantifying Lack of Plot Diversity in LLM Outputs | ArXiv 2025 (arXiv preprint) | 2025-01 | [arXiv](https://arxiv.org/abs/2501.00273) | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | benchmark, evaluation |
| Evaluating Creative Short Story Generation in Humans and Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-11 | [arXiv](https://arxiv.org/abs/2411.02316) | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | benchmark, evaluation |
| Small Language Models can Outperform Humans in Short Creative Writing: A Study Comparing SLMs with Humans and LLMs | COLING 2025 (International Conference on Computational Linguistics) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.11547) | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | benchmark, evaluation |
| HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.16191) | - | - | benchmark, evaluation |
| STORYSUMM: Evaluating Faithfulness in Story Summarization | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.06501) | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| Pron vs Prompt: Can Large Language Models already Challenge a World-Class Fiction Author at Creative Text Writing? | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01119) | - | ![citation](https://img.shields.io/badge/citation-17-0A66C2) | benchmark, evaluation |
| Are Large Language Models Capable of Generating Human-Level Narratives? | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.13248) | - | ![citation](https://img.shields.io/badge/citation-33-0A66C2) | benchmark, evaluation |
| Do Language Models Enjoy Their Own Stories? Prompting Large Language Models for Automatic Story Evaluation | TACL 2024 (Transactions of the Association for Computational Linguistics) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.13769) | - | ![citation](https://img.shields.io/badge/citation-18-0A66C2) | benchmark, evaluation |
| Reading Subtext: Evaluating Large Language Models on Short Story Summarization with Writers | TACL 2024 (Transactions of the Association for Computational Linguistics) | 2024-03 | [arXiv](https://arxiv.org/abs/2403.01061) | - | ![citation](https://img.shields.io/badge/citation-15-0A66C2) | benchmark, evaluation |
| Learning Personalized Alignment for Evaluating Open-ended Text Generation | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.03304) | - | ![citation](https://img.shields.io/badge/citation-11-0A66C2) | benchmark, evaluation |
| A Confederacy of Models: a Comprehensive Evaluation of LLMs on Creative Writing | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08433) | - | ![citation](https://img.shields.io/badge/citation-83-0A66C2) | benchmark, evaluation |
| Art or Artifice? Large Language Models and the False Promise of Creativity | CHI 2023 (Conference on Human Factors in Computing Systems) | 2023-09 | [arXiv](https://arxiv.org/abs/2309.14556) | - | ![citation](https://img.shields.io/badge/citation-136-0A66C2) | benchmark, evaluation |
| HAUSER: Towards Holistic and Automatic Evaluation of Simile Generation | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-06 | [arXiv](https://arxiv.org/abs/2306.07554) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | benchmark, evaluation |
| Can Large Language Models Be an Alternative to Human Evaluations? | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.01937) | - | ![citation](https://img.shields.io/badge/citation-634-0A66C2) | benchmark, evaluation |
| DeltaScore: Evaluating Story Generation with Differentiating Perturbations | EMNLP Findings 2023 (Findings of EMNLP) | 2023-03 | [arXiv](https://arxiv.org/abs/2303.08991) | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| StoryER: Automatic Story Evaluation via Ranking, Rating and Reasoning | EMNLP 2022 (Conference on Empirical Methods in Natural Language Processing) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.08459) | - | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | benchmark, evaluation |
| Of Human Criteria and Automatic Metrics: A Benchmark of the Evaluation of Story Generation | COLING 2022 (International Conference on Computational Linguistics) | 2022-08 | [arXiv](https://arxiv.org/abs/2208.11646) | - | ![citation](https://img.shields.io/badge/citation-55-0A66C2) | benchmark, evaluation |

<a id="datasets-surveys"></a>
### Datasets / Surveys / Resources

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| Narrative Theory-Driven LLM Methods for Automatic Story Generation and Understanding: A Survey | ArXiv 2026 (arXiv preprint) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.15851) | - | - | dataset, survey |
| MUSE: A Multi-agent Framework for Unconstrained Story Envisioning via Closed-Loop Cognitive Orchestration | ArXiv 2026 (arXiv preprint) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.03028) | - | - | dataset, resource |
| StoryWriter: A Multi-Agent Framework for Long Story Generation | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.16445) | - | - | dataset, resource |
| Reasoning-Enhanced Self-Training for Long-Form Personalized Text Generation | ArXiv 2025 (arXiv preprint) | 2025-01 | [arXiv](https://arxiv.org/abs/2501.04167) | [Project](https://github.com/Alex-Gurung/ReasoningNCP) | - | dataset, resource |
| Multi-Agent Based Character Simulation for Story Writing | IN2Writing 2025 (IN2Writing Workshop) | 2025-01 | [Published](https://aclanthology.org/2025.in2writing-1.9/) | - | - | dataset, resource |
| BookWorm: A Dataset for Character Description and Analysis | EMNLP Findings 2024 (Findings of EMNLP) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.10372) | - | ![citation](https://img.shields.io/badge/citation-2-0A66C2) | dataset, dataset |
| What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation | ArXiv 2024 (arXiv preprint) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.14622) | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | dataset, survey |
| The GPT-WritingPrompts Dataset: A Comparative Analysis of Character Portrayal in Short Stories | EMNLP Workshop 2025 (EMNLP Workshop) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.16767) | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | dataset, dataset |
| CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis | NAACL Findings 2025 (Findings of NAACL) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.12665) | - | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | dataset, resource |
| The Value, Benefits, and Concerns of Generative AI-Powered Assistance in Writing | CHI 2024 (Conference on Human Factors in Computing Systems) | 2024-03 | [arXiv](https://arxiv.org/abs/2403.12004) | - | ![citation](https://img.shields.io/badge/citation-59-0A66C2) | dataset, resource |
| Large Language Models Fall Short: Understanding Complex Relationships in Detective Narratives | ACL Findings 2024 (Findings of ACL) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.11051) | - | ![citation](https://img.shields.io/badge/citation-13-0A66C2) | dataset, resource |
| CMDAG: A Chinese Metaphor Dataset with Annotated Grounds as CoT for Boosting Metaphor Generation | LREC-COLING 2024 (LREC-COLING) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.13145) | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | dataset, dataset |
| Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.14207) | - | - | dataset, resource |
| Weaver: Foundation Models for Creative Writing | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.17268) | - | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | dataset, resource |
| Reflections & Resonance: Two-Agent Partnership for Advancing LLM-based Story Annotation | LREC-COLING 2024 (LREC-COLING) | 2024-01 | [Published](https://aclanthology.org/2024.lrec-main.1206/) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | dataset, resource |
| CLAUSE-ATLAS: A Corpus of Narrative Information to Scale up Computational Literary Analysis | LREC-COLING 2024 (LREC-COLING) | 2024-01 | [Published](https://aclanthology.org/2024.lrec-main.292/) | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | dataset, resource |
| STONYBOOK: A System and Resource for Large-Scale Analysis of Novels | ArXiv 2023 (arXiv preprint) | 2023-11 | [arXiv](https://arxiv.org/abs/2311.03614) | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | dataset, resource |
| Are NLP Models Good at Tracing Thoughts: An Overview of Narrative Understanding | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.18783) | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | dataset, resource |
| StoryWars: A Dataset and Instruction Tuning Baselines for Collaborative Story Understanding and Generation | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.08152) | - | ![citation](https://img.shields.io/badge/citation-8-0A66C2) | dataset, dataset |
| Open-world Story Generation with Structured Knowledge Enhancement: A Comprehensive Survey | Neurocomputing 2023 (Neurocomputing (Journal)) | 2022-12 | [arXiv](https://arxiv.org/abs/2212.04634) | - | - | dataset, survey |
| Co-Writing Screenplays and Theatre Scripts with Language Models: An Evaluation by Industry Professionals | ArXiv 2022 (arXiv preprint) | 2022-09 | [arXiv](https://arxiv.org/abs/2209.14958) | [Project](https://github.com/google-deepmind/dramatron) | - | dataset, screenplay |
| A corpus for understanding and generating moral stories | NAACL 2022 (North American Chapter of ACL) | 2022-04 | [arXiv](https://arxiv.org/abs/2204.09438) | - | ![citation](https://img.shields.io/badge/citation-10-0A66C2) | dataset, resource |

<a id="open-source-projects"></a>
### Open-source Projects (No Paper Required)

| Title | Venue | Date | Paper | Project | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- |
| FireRed-OpenStoryline | GitHub 2026 (Open-source repository) | 2026-01 | - | [Project](https://github.com/FireRedTeam/FireRed-OpenStoryline) | - | tooling, open-source |
| ReasoningNCP (Official Repository) | GitHub 2025 (Open-source repository) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.22828) | [Project](https://github.com/Alex-Gurung/ReasoningNCP) | - | tooling, open-source |
| SEED-Story (Official Repository) | GitHub 2024 (Open-source repository) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.08683) | [Project](https://github.com/TencentARC/SEED-Story) | - | tooling, open-source |
| IBSEN (Official Repository) | GitHub 2024 (Open-source repository) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01093) | [Project](https://github.com/OpenDFM/ibsen) | - | tooling, open-source |
| RENarGen (Official Repository) | GitHub 2024 (Open-source repository) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.00829) | [Project](https://github.com/adbrei/RENarGen) | - | tooling, open-source |
| fictionx-story-gen | GitHub 2024 (Open-source repository) | 2024-01 | - | [Project](https://github.com/WyseOS/fictionx-story-gen) | - | tooling, open-source |
| SillyTavern | GitHub 2023 (Open-source repository) | 2023-01 | - | [Project](https://github.com/SillyTavern/SillyTavern) | - | tooling, open-source |
| GOAT-Storytelling-Agent | GitHub 2023 (Open-source repository) | 2023-01 | - | [Project](https://github.com/GOAT-AI-lab/GOAT-Storytelling-Agent) | - | tooling, open-source |
| Dramatron (Official Repository) | GitHub 2022 (Open-source repository) | 2022-09 | [arXiv](https://arxiv.org/abs/2209.14958) | [Project](https://github.com/google-deepmind/dramatron) | - | tooling, screenplay |
| TavernAI | GitHub 2022 (Open-source repository) | 2022-01 | - | [Project](https://github.com/TavernAI/TavernAI) | - | tooling, open-source |

## Maintenance Notes

- Check duplicate titles before adding new entries.
- Update README.md and README_zh.md together.
- Use YYYY-MM for Date.
- Keep Paper as one primary link (Published preferred, otherwise arXiv; use `-` if unavailable).

## Citation

If this repository helps your research or project, please cite:

```bibtex
@misc{lijunjie2026awesomellmstorygeneration,
  title        = {Awesome LLM Story Generation},
  author       = {Lijunjie},
  year         = {2026},
  howpublished = {\url{https://github.com/lijunjie/awesome-llm-story-generation}},
  note         = {GitHub repository, accessed 2026-02-27}
}
```

If you later change your GitHub account or repository name, update `author` and `howpublished` accordingly.
