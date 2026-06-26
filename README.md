# Awesome LLM Story Generation

A curated list of story/novel/script generation research in the LLM era (2022-present), organized by method with strict link verification.

- Total entries: **278**
- Categories: **10**
- Last verified: **2026-06-25**
- Language: [English](./README.md) | [中文](./README_zh.md)

## Contents

- [Category Overview](#category-overview)
- [Papers and Projects](#papers-and-projects)
  - Story Generation Methods
    - [Planning / Decomposition for Story Generation](#planning)
    - [Agent Collaboration for Story Writing](#agent-collaboration)
    - [Sandbox / World Simulation Narrative Generation](#sandbox-world-simulation)
    - [Multimodal Story Generation (Text-Image/Video/Comic/Audio)](#multimodal-story-generation)
  - Quality, Control, and Iteration
    - [Memory & Long-Context Coherence](#memory-long-context)
    - [Consistency / Controllability / Constraint Following](#consistency-controllability)
    - [Refinement / Self-Critique / Iterative Editing](#refinement-self-critique)
  - Evaluation and Resources
    - [Evaluation / Benchmarks / Metrics](#evaluation-benchmarks)
    - [Datasets / Surveys / Resources](#datasets-surveys)
    - [Open-source Projects (No Paper Required)](#open-source-projects)
- [Maintenance Notes](#maintenance-notes)
- [Citation](#citation)

## Category Overview

| Category | Entries |
| --- | ---: |
| Planning / Decomposition for Story Generation | 21 |
| Agent Collaboration for Story Writing | 6 |
| Sandbox / World Simulation Narrative Generation | 17 |
| Multimodal Story Generation (Text-Image/Video/Comic/Audio) | 59 |
| Memory & Long-Context Coherence | 20 |
| Consistency / Controllability / Constraint Following | 24 |
| Refinement / Self-Critique / Iterative Editing | 15 |
| Evaluation / Benchmarks / Metrics | 74 |
| Datasets / Surveys / Resources | 32 |
| Open-source Projects (No Paper Required) | 10 |

## Papers and Projects

Note: `Project` stores project/demo links; `Code` stores verified GitHub repositories.

<a id="planning"></a>
### Planning / Decomposition for Story Generation

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GraphStory: Collaborative Story Writing through Event-Based Narrative Editing | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.16102) | - | - | - | planning, narrative-structure |
| [Auferet](https://auferet.com) | AI game master that remembers your world: persistent memory for characters, places, and lore you upload; solo or multiplayer, 5e & Pathfinder 2e | — | — | — | — | — | — |
| Fabula: Building a Narrative Storytelling Sidekick with the Writers' Community | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.14411) | - | - | - | planning, co-creation |
| Towards Human-Level Book-Writing Capability | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.17064) | - | - | - | planning, narrative-structure |
| Planning Beyond Text: Graph-based Reasoning for Complex Narrative Generation | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.21253) | - | - | - | planning, narrative-structure |
| Narrix: Remixing Narrative Strategies from Examples for Story Writing | CHI 2026 (Conference on Human Factors in Computing Systems) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.07643) | - | - | - | planning, narrative-structure |
| BiT-MCTS: A Theme-based Bidirectional MCTS Approach to Chinese Fiction Generation | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.14410) | - | - | - | planning, narrative-structure |
| DPWriter: Reinforcement Learning with Diverse Planning Branching for Creative Writing | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.09609) | - | - | - | planning, narrative-structure |
| Codified Foreshadowing-Payoff Text Generation | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.07033) | - | - | - | planning, narrative-structure |
| SceneDecorator: Towards Scene-Oriented Story Generation with Scene Planning and Scene Consistency | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.22994) | - | - | - | planning, narrative-structure |
| Long Story Generation via Knowledge Graph and Literary Theory | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.03137) | - | - | - | planning, narrative-structure |
| STORYTELLER: An Enhanced Plot-Planning Framework for Coherent and Cohesive Story Generation | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.02347) | - | - | - | planning, narrative-structure |
| Can LLMs Generate Good Stories? Insights and Challenges from a Narrative Planning Perspective | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.10161) | - | - | - | planning, narrative-structure |
| Learning to Reason for Long-Form Story Generation | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.22828) | - | [Code](https://github.com/Alex-Gurung/ReasoningNCP) | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | planning, narrative-structure |
| Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement | NAACL 2025 (North American Chapter of ACL) | 2024-12 | [arXiv](https://arxiv.org/abs/2412.13575) | - | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | planning, narrative-structure |
| Ex3: Automatic Novel Writing by Extracting, Excelsior and Expanding | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.08506) | - | - | ![citation](https://img.shields.io/badge/citation-2-0A66C2) | planning, narrative-structure |
| Navigating the Path of Writing: Outline-guided Text Generation with Large Language Models | NAACL 2025 (North American Chapter of ACL) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.13919) | - | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | planning, narrative-structure |
| Creating Suspenseful Stories: Iterative Planning with Large Language Models | EACL 2024 (Conference of the European Chapter of ACL) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.17119) | - | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | planning, narrative-structure |
| Improving Pacing in Long-Form Story Planning | EMNLP Findings 2023 (Findings of EMNLP) | 2023-11 | [arXiv](https://arxiv.org/abs/2311.04459) | - | - | ![citation](https://img.shields.io/badge/citation-19-0A66C2) | planning, narrative-structure |
| End-to-End Story Plot Generator | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08796) | - | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | planning, narrative-structure |
| The Next Chapter: A Study of Large Language Models in Storytelling | ArXiv 2023 (arXiv preprint) | 2023-01 | [arXiv](https://arxiv.org/abs/2301.09790) | - | - | - | planning, narrative-structure |
| DOC: Improving Long Story Coherence With Detailed Outline Control | ArXiv 2022 (arXiv preprint) | 2022-12 | [arXiv](https://arxiv.org/abs/2212.10077) | - | - | - | planning, narrative-structure |

<a id="agent-collaboration"></a>
### Agent Collaboration for Story Writing

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Improving Collaborative Storytelling with a Multi-Agent Framework Based on Large Language Models | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.29625) | - | - | - | multi-agent, collaboration |
| Collaborative Multi-Agent Scripts Generation for Enhancing Imperfect-Information Reasoning in Murder Mystery Games | ACL Findings 2026 (Findings of ACL) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.11741) | - | - | - | multi-agent, collaboration |
| A Cognitive Writing Perspective for Constrained Long-Form Text Generation | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.12568) | - | [Code](https://github.com/KaiyangWan/CogWriter) | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | multi-agent, collaboration |
| Agents' Room: Narrative Generation through Multi-step Collaboration | ICLR 2025 (International Conference on Learning Representations) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.02603) | - | - | ![citation](https://img.shields.io/badge/citation-16-0A66C2) | multi-agent, collaboration |
| HoLLMwood: Unleashing the Creativity of Large Language Models in Screenwriting via Role Playing | EMNLP Findings 2024 (Findings of EMNLP) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.11683) | - | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | multi-agent, collaboration |
| AutoAgents: A Framework for Automatic Agent Generation | IJCAI 2024 (International Joint Conference on Artificial Intelligence) | 2023-09 | [arXiv](https://arxiv.org/abs/2309.17288) | - | [Code](https://github.com/Link-AGI/AutoAgents) | ![citation](https://img.shields.io/badge/citation-129-0A66C2) | multi-agent, collaboration |

<a id="sandbox-world-simulation"></a>
### Sandbox / World Simulation Narrative Generation

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Orchestrated Reality: From Role-Play to Living, Playable Game Worlds -- LLM-Driven World Simulation as a Parameterized-Action POMDP | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.16014) | - | - | - | sandbox, simulation |
| IVIE: A Neuro-symbolic Approach to Incremental and Validated Generation of Interactive Fiction Worlds | ICCC 2026 (International Conference on Computational Creativity) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.13348) | - | - | - | sandbox, interactive |
| BotDirector: Robot Storytelling Across the Symmetrical Reality with Multi-modal Interactions | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.03223) | - | - | - | sandbox, interactive |
| World-State Transformations for Neuro-symbolic Interactive Storytelling | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.24719) | - | - | - | sandbox, interactive |
| Material for Thought: Generative AI as an Active Creative Medium | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.19832) | - | - | - | sandbox, co-creation |
| A Generative AI Driven Interactive Narrative Serious Game for Stress Relief and Its Randomized Controlled Pilot Study | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.11562) | - | - | - | sandbox, interactive |
| A Reflective Storytelling Agent for Older Adults: Integrating Argumentation Schemes and Argument Mining in LLM-Based Personalised Narratives | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.10531) | - | - | - | sandbox, interactive |
| EvoSpark: Endogenous Interactive Agent Societies for Unified Long-Horizon Narrative Evolution | ACL 2026 (Annual Meeting of the Association for Computational Linguistics) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.12776) | - | - | - | sandbox, simulation |
| StoryBox: Collaborative Multi-Agent Simulation for Hybrid Bottom-Up Long-Form Story Generation Using Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.11618) | [Project](https://storyboxproject.github.io) | - | - | sandbox, simulation |
| OPEN-THEATRE: An Open-Source Toolkit for LLM-based Interactive Drama | ArXiv 2025 (arXiv preprint) | 2025-09 | [arXiv](https://arxiv.org/abs/2509.16713) | - | - | - | sandbox, interactive |
| HAMLET: Hyperadaptive Agent-based Modeling for Live Embodied Theatrics | ArXiv 2025 (arXiv preprint) | 2025-07 | [arXiv](https://arxiv.org/abs/2507.15518) | - | - | - | sandbox, simulation |
| STORY2GAME: Generating (Almost) Everything in an Interactive Fiction Game | ArXiv 2025 (arXiv preprint) | 2025-05 | [arXiv](https://arxiv.org/abs/2505.03547) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | sandbox, interactive |
| BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation | ArXiv 2025 (arXiv preprint) | 2025-04 | [arXiv](https://arxiv.org/abs/2504.14538) | [Project](https://bookworld2025.github.io) | - | - | sandbox, interactive |
| Towards Enhanced Immersion and Agency for LLM-based Interactive Drama | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.17878) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | sandbox, interactive |
| IBSEN: Director-Actor Agent Collaboration for Controllable and Interactive Drama Script Generation | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01093) | - | [Code](https://github.com/OpenDFM/ibsen) | ![citation](https://img.shields.io/badge/citation-16-0A66C2) | sandbox, interactive |
| StoryVerse: Towards Co-authoring Dynamic Plot with LLM-based Character Simulation via Narrative Planning | FDG 2024 (Foundations of Digital Games) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.13042) | - | - | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | sandbox, simulation |
| Generative Agents: Interactive Simulacra of Human Behavior | ArXiv 2023 (arXiv preprint) | 2023-04 | [arXiv](https://arxiv.org/abs/2304.03442) | [Project](https://github.com/joonspk-research/generative_agents) | [Code](https://github.com/joonspk-research/generative_agents) | - | sandbox, interactive |

<a id="multimodal-story-generation"></a>
### Multimodal Story Generation (Text-Image/Video/Comic/Audio)

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FreeStory: Training-Free Character Consistency for Free-Form Visual Storytelling | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.25079) | - | - | - | multimodal, visual-story |
| DramaDirector: Geometry-Guided Short Drama Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.24107) | - | [Code](https://github.com/iLearn-Lab/DramaDirector) | - | multimodal, video-story |
| DataMagic: Transforming Tabular Data into Data Insight Video | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.20388) | [Project](https://datamagic-home.github.io/) | - | - | multimodal, data-story |
| LooseControlVideo: Directorial Video Control using Spatial Blocking | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.19495) | [Project](https://shariqfarooq123.github.io/LooseControlVideo/) | - | - | multimodal, video-story |
| Reference-Driven Multi-Speaker Audio Scene Generation from In-the-Wild Priors | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.19325) | [Project](https://finmickey.github.io/scena/) | - | - | multimodal, audio-story |
| UniTemp: Unlocking Video Generation in Any Temporal Order via Bidirectional Distillation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.18702) | [Project](https://lzhangbj.github.io/projects/unitemp/) | [Code](https://github.com/lzhangbj/UniTemp) | - | multimodal, video-story |
| Bridging Creative Intent and Visual Quality: Creator-Driven Recurrent Video Generation with Agentic Feedback Loops | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.18591) | - | - | - | multimodal, video-story |
| PermaVid: Consistent Video Generation Across Edits via Disentangled Context Memory | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.16449) | [Project](https://ys-imtech.github.io/projects/PermaVid/) | - | - | multimodal, video-story |
| Closed-Loop Triplet Synergistic Generation for Long-Form Video | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.16184) | - | - | - | multimodal, video-story |
| Memento: Reconstruct to Remember for Consistent Long Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.14667) | [Project](https://ernie-research.github.io/Memento/) | [Code](https://github.com/ernie-research/Memento) | - | multimodal, video-story |
| CineOrchestra: Unified Entity-Centric Conditioning for Cinematic Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.13768) | - | - | - | multimodal, video-story |
| InterleaveThinker: Reinforcing Agentic Interleaved Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.13679) | [Project](https://zhengdian1.github.io/InterleaveThinker-proj/) | [Code](https://github.com/zhengdian1/InterleaveThinker) | - | multimodal, visual-story |
| OmniDirector: General Multi-Shot Camera Cloning without Cross-Paired Data | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.13432) | [Project](https://ymlinfeng.github.io/OmniDirector.github.io/) | - | - | multimodal, video-story |
| TetherCache: Stabilizing Autoregressive Long-Form Video Generation with Gated Recall and Trusted Alignment | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.13035) | - | - | - | multimodal, video-story |
| Helping Figures Tell their Story! Paper-Grounded Video Generation Explaining Complex Scientific Figures | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.12576) | [Project](https://minard.vercel.app/) | - | - | multimodal, visual-story |
| Data Journalist Agent: Transforming Data into Verifiable Multimodal Stories | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.11176) | [Project](https://data2story.github.io) | [Code](https://github.com/QinghongLin/data2story-skill) | - | multimodal, data-story |
| MilliVid: Hierarchical Latents for Long-Range Consistency in Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.09056) | [Project](https://davidcharatan.com/millivid/) | - | - | multimodal, video-story |
| ViMax: Agentic Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.07649) | - | - | - | multimodal, video-story |
| Audio-Oscar: A Multi-Agent System for Complex Audio Scene Generation, Orchestration, and Refinement | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.07397) | [Project](https://audiooscar.github.io/) | [Code](https://github.com/ziye26/Audio-Oscar) | - | multimodal, audio-story |
| LongLive-RAG: A General Retrieval-Augmented Framework for Long Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.02553) | - | [Code](https://github.com/qixinhu11/LongLive-RAG) | - | multimodal, video-story |
| Retrieve What's Missing: Coverage-Maximizing Retrieval for Consistent Long Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.02479) | - | - | - | multimodal, video-story |
| JenBridge: Adaptive Long-Form Video Soundtracking across Scene Transitions | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.01703) | - | - | - | multimodal, audio-video |
| Crayotter: Traceable Multi-Agent Workflows for Long-Form Video Editing | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2606.07636) | - | [Code](https://github.com/idwts/Crayotter) | - | multimodal, video-story |
| DecMem: Towards Minute-Long Consistent World Generation with Decoupled Memory | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.31336) | [Project](https://jeffreyyzh.github.io/DecMem-Page/) | - | - | multimodal, video-story |
| SlotMemory: Object-Centric KV Memory for Streaming Long-Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.31033) | [Project](https://tj12323.github.io/SlotMemory/) | - | - | multimodal, video-story |
| MangaFlow: An End-to-End Agentic Framework for Controllable Story to Manga Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.28173) | - | - | - | multimodal, visual-story |
| SmartDirector: Keyframe-Conditioned Cinematic Video Generation with Narrative Pacing Control | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.27891) | - | - | - | multimodal, video-story |
| BEAT: Rhythm-Elastic Alignment for Agentic Music-guided Movie Trailer Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.27067) | - | - | - | multimodal, video-story |
| ReCA: Multi-Shot Long Video Extrapolation via Recursive Context Allocation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.26525) | [Project](https://reca.vmv.re) | - | - | multimodal, video-story |
| EM-Vid: Training-Free Entity-Centric Memory for Efficient and Consistent Multi-Shot Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.23610) | - | - | - | multimodal, video-story |
| DrawVideo: Generating Long Video from Storyboard Keyframe Sketches | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.23508) | - | - | - | multimodal, video-story |
| S2ED: From Story to Executable Descriptions for Consistency-Aware Story Illustration | ICME 2026 (IEEE International Conference on Multimedia and Expo) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.22448) | - | - | - | multimodal, visual-story |
| One Sentence, One Drama: Personalized Short-Form Drama Generation via Multi-Agent Systems | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.22144) | - | - | - | multimodal, screenplay |
| AttriStory: Fine-grained Attribute Realization for Visual Storytelling with Diffusion Models | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.20777) | [Project](https://manogna-s.github.io/attristory/) | - | - | multimodal, visual-story |
| TombWriter: Scaffolding Story Archeology through Beat-Level Interaction in Human-AI Co-Writing | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.19681) | - | - | - | multimodal, co-creation |
| Advancing Narrative Long Video Generation via Training-Free Identity-Aware Memory | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.18733) | - | - | - | multimodal, video-story |
| Soap2Soap: Long Cinematic Video Remaking via Multi-Agent Collaboration | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.17423) | - | - | - | multimodal, video-story |
| CausalCine: Real-Time Autoregressive Generation for Multi-Shot Video Narratives | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.12496) | [Project](https://yihao-meng.github.io/CausalCine/) | - | - | multimodal, video-story |
| RealDiffusion: Physics-informed Attention for Multi-character Storybook Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.11927) | - | [Code](https://github.com/ShmilyQi-CN/RealDiffusion) | - | multimodal, visual-story |
| AuDirector: A Self-Reflective Closed-Loop Framework for Immersive Audio Storytelling | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.11866) | [Project](https://anonymous-itsh.github.io/) | - | - | multimodal, audio-story |
| Co-Director: Agentic Generative Video Storytelling | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.24842) | - | - | - | multimodal, video-story |
| CineAGI: Character-Consistent Movie Creation through LLM-Orchestrated Multi-Modal Generation and Cross-Scene Integration | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.23579) | - | - | - | multimodal, video-story |
| CANVAS: Continuity-Aware Narratives via Visual Agentic Storyboarding | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.13452) | - | - | - | multimodal, visual-story |
| OmniScript: Towards Audio-Visual Script Generation for Long-Form Cinematic Video | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.11102) | - | - | - | multimodal, screenplay |
| Camera Artist: A Multi-Agent Framework for Cinematic Language Storytelling Video Generation | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.09195) | - | - | - | multimodal, video-story |
| StoryBlender: Inter-Shot Consistent and Editable 3D Storyboard with Spatial-temporal Dynamics | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.03315) | - | - | - | multimodal, visual-story |
| LogiStory: A Logic-Aware Framework for Multi-Image Story Visualization | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.28082) | - | - | - | multimodal, visual-story |
| Customized Visual Storytelling with Unified Multimodal LLMs | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.27690) | - | - | - | multimodal, visual-story |
| Directing the Narrative: A Finetuning Method for Controlling Coherence and Style in Story Generation | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.17295) | - | - | - | multimodal, visual-story |
| EmoStory: Emotion-Aware Story Generation | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.10349) | - | - | - | multimodal, visual-story |
| PlayWrite: A Multimodal System for AI Supported Narrative Co-Authoring Through Play in XR | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.02366) | - | - | - | multimodal, co-creation |
| StoryComposerAI: A Multimodal Story Co-Creation Tool for Amateur Writers | CHI EA 2026 (Extended Abstracts of the 2026 CHI Conference on Human Factors in Computing Systems) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.21486) | - | - | - | multimodal, co-creation |
| The Script is All You Need: An Agentic Framework for Long-Horizon Dialogue-to-Cinematic Video Generation | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.17737) | - | - | - | multimodal, screenplay |
| Re:Verse -- Can Your VLM Read a Manga? | ICCV AISTORY Workshop 2025 (ICCV AISTORY Workshop) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.08508) | - | - | - | multimodal, visual-story |
| Lay2Story: Extending Diffusion Transformers for Layout-Togglable Story Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.08949) | - | - | - | multimodal, visual-story |
| R^2: A LLM BASED NOVEL-TO-SCREENPLAY GENERATION FRAMEWORK WITH CAUSAL PLOT GRAPHS | ICLR 2025 (International Conference on Learning Representations) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.15655) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | multimodal, screenplay |
| LongWriter-V: Enabling Ultra-Long and High-Fidelity Generation in Vision-Language Models | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.14834) | - | [Code](https://github.com/THU-KEG/LongWriter-V) | - | multimodal, visual-story |
| SEED-Story: Multimodal Long Story Generation with Large Language Model | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.08683) | - | [Code](https://github.com/TencentARC/SEED-Story) | - | multimodal, visual-story |
| Make-A-Story: Visual Memory Conditioned Consistent Story Generation | CVPR 2023 (Conference on Computer Vision and Pattern Recognition) | 2022-11 | [arXiv](https://arxiv.org/abs/2211.13319) | - | - | - | multimodal, visual-story |

<a id="memory-long-context"></a>
### Memory & Long-Context Coherence

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Staying In Character: Perspective-Bounded Memory For Book-Based Role-Playing Agents | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.25632) | - | - | - | long-context, role-playing |
| Not All Claims Are Equally Risky: FACTOR for Adaptive Verification in Factual Long-Form Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.22474) | - | - | - | long-context, factuality |
| Storyline Trees: Hierarchical Representations for Long-Form Narratives | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.20900) | - | - | - | long-context, narrative-representation |
| IS-CoT: Breaking the Long-form Generation Collapse via Interleaved Structural Thinking | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.09709) | - | - | - | long-context, generation |
| Narrative Knowledge Weaver: Narrative-Centric Retrieval-Augmented Reasoning for Long-Form Text Understanding | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.05724) | - | - | - | long-context, narrative-understanding |
| POLARIS: Guiding Small Models to Write Long Stories | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.04095) | - | - | - | long-context, generation |
| Building Reliable Long-Form Generation via Hallucination Rejection Sampling | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.03628) | - | [Code](https://github.com/TreeLLi/hallucination-rejection-sampling) | - | long-context, coherence |
| Tournament-GRPO: Group-Wise Tournament Rewards for Reinforcement Learning in Open-Ended Long-Form Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.26958) | - | - | - | long-context, generation |
| On Stable Long-Form Generation: Benchmarking and Mitigating Length Volatility | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.01357) | - | - | - | long-context, coherence |
| Think Before you Write: QA-Guided Reasoning for Character Descriptions in Books | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.11435) | - | - | - | long-context, coherence |
| Skeleton-based Coherence Modeling in Narratives | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.02451) | - | - | - | long-context, coherence |
| Shifting Long-Context LLMs Research from Input to Output | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.04723) | - | - | - | long-context, coherence |
| Language Models can Self-Lengthen to Generate Long Texts | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.23933) | - | [Code](https://github.com/QwenLM/Self-Lengthen) | - | long-context, coherence |
| LongGenBench: Benchmarking Long-Form Generation in Long-Context LLMs | ArXiv 2024 (arXiv preprint) | 2024-09 | [Published](https://openreview.net/forum?id=3A71qNKWAS) | - | - | - | long-context, coherence |
| LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs | ArXiv 2024 (arXiv preprint) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.07055) | - | [Code](https://github.com/THUDM/LongWriter) | - | long-context, coherence |
| LongLaMP: A Benchmark for Personalized Long-form Text Generation | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.11016) | - | - | - | long-context, coherence |
| CHIRON: Rich Character Representations in Long-Form Narratives | EMNLP Findings 2024 (Findings of EMNLP) | 2024-06 | [Published](https://aclanthology.org/2024.findings-emnlp.499/) | - | - | - | long-context, coherence |
| With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation | COLM 2024 (Conference on Language Modeling) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.11504) | - | - | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | long-context, coherence |
| LongAlign: A Recipe for Long Context Alignment of Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.18058) | - | [Code](https://github.com/THUDM/LongAlign) | - | long-context, coherence |
| RecurrentGPT: Interactive Generation of (Arbitrarily) Long Text | ArXiv 2023 (arXiv preprint) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.13304) | [Project](https://github.com/aiwaves-cn/RecurrentGPT) | [Code](https://github.com/aiwaves-cn/RecurrentGPT) | ![citation](https://img.shields.io/badge/citation-64-0A66C2) | long-context, interactive |

<a id="consistency-controllability"></a>
### Consistency / Controllability / Constraint Following

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Steering Emotional Dynamics for Art Therapy: Controllable Narrative Script Generation through Hierarchically Guided LLM Agents | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.16481) | - | - | - | controllability, screenplay |
| Constrained Semantic Decompression in LLMs through Persian Proverb-Conditioned Story Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.12599) | - | - | - | controllability, story-generation |
| Children's English Reading Story Generation via Supervised Fine-Tuning of Compact LLMs with Controllable Difficulty and Safety | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.13709) | - | - | - | controllability, consistency |
| UniCreative: Unifying Long-form Logic and Short-form Sparkle via Reference-Free Reinforcement Learning | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.05517) | - | - | - | controllability, consistency |
| Noise Steering for Controlled Text Generation: Improving Diversity and Reading-Level Fidelity in Arabic Educational Story Generation | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.03380) | - | - | - | controllability, consistency |
| Preconditioned Test-Time Adaptation for Out-of-Distribution Debiasing in Narrative Generation | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.13683) | - | - | - | controllability, consistency |
| TaleFrame: An Interactive Story Generation System with Fine-Grained Control and Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-12 | [arXiv](https://arxiv.org/abs/2512.02402) | - | - | - | controllability, interactive |
| SCORE: Story Coherence and Retrieval Enhancement for AI Narratives | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.23512) | - | - | ![citation](https://img.shields.io/badge/citation-17-0A66C2) | controllability, retrieval |
| Whose story is it? Personalizing story generation by inferring author styles | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.13028) | - | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| Pastiche Novel Generation Creating: Fan Fiction You Love in Your Favorite Author's Style | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.15616) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| CS4: Measuring the Creativity of Large Language Models Automatically by Controlling the Number of Story-Writing Constraints | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.04197) | - | [Code](https://github.com/anirudhlakkaraju/cs4_benchmark) | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | controllability, consistency |
| Crafting Narrative Closures: Zero-Shot Learning with SSM Mamba for Short Story Ending Generation | ArXiv 2024 (arXiv preprint) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.10848) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| MirrorStories: Reflecting Diversity through Personalized Narrative Generation with Large Language Models | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.13935) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| FACTTRACK: Time-Aware World State Tracking in Story Outlines | NAACL 2025 (North American Chapter of ACL) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.16347) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | controllability, consistency |
| Suri: Multi-constraint Instruction Following for Long-form Text Generation | ArXiv 2024 (arXiv preprint) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.19371) | - | [Code](https://github.com/chtmp223/suri) | - | controllability, consistency |
| MoPS: Modular Story Premise Synthesis for Open-Ended Automatic Story Generation | ACL 2024 (Annual Meeting of the Association for Computational Linguistics) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.05690) | [Project](https://github.com/GAIR-NLP/MoPS) | [Code](https://github.com/GAIR-NLP/MoPS) | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| Measuring Psychological Depth in Language Models | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.12680) | - | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | controllability, consistency |
| Guiding and Diversifying LLM-Based Story Generation via Answer Set Programming | ACL Workshop 2025 (ACL Workshop) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.00554) | - | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| Multigenre AI-powered Story Composition | ArXiv 2024 (arXiv preprint) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.06685) | - | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| Returning to the Start: Generating Narratives with Related Endpoints | NAACL 2024 (North American Chapter of ACL) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.00829) | [Project](https://github.com/adbrei/RENarGen) | [Code](https://github.com/adbrei/RENarGen) | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | controllability, consistency |
| NarrativeGenie: Generating Narrative Beats and Dynamic Storytelling with Large Language Models | AIIDE 2024 (Conference on Artificial Intelligence and Interactive Digital Entertainment) | 2024-01 | [Published](https://ojs.aaai.org/index.php/AIIDE/article/view/31868) | - | - | - | controllability, consistency |
| CAT-LLM: Prompting Large Language Models with Text Style Definition for Chinese Article-style Transfer | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.05707) | - | - | ![citation](https://img.shields.io/badge/citation-13-0A66C2) | controllability, consistency |
| Learning to Generate Text in Arbitrary Writing Styles | ArXiv 2023 (arXiv preprint) | 2023-12 | [arXiv](https://arxiv.org/abs/2312.17242) | - | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | controllability, consistency |
| RLCD: Reinforcement Learning from Contrast Distillation for Language Model Alignment | ICLR 2024 (International Conference on Learning Representations) | 2023-07 | [arXiv](https://arxiv.org/abs/2307.12950) | - | - | ![citation](https://img.shields.io/badge/citation-24-0A66C2) | controllability, consistency |

<a id="refinement-self-critique"></a>
### Refinement / Self-Critique / Iterative Editing

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| StoryLens: Preference-Aligned Story Rewriting via Context-Aware Narrative Enrichment | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.28073) | - | - | - | refinement, revision |
| DTO: a Differentiable Training Objective for Effective Counterfactual Story Rewriting | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.24885) | - | - | - | refinement, revision |
| R2-Write: Reflection and Revision for Open-Ended Writing with Deep Reasoning | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.03004) | - | - | - | refinement, revision |
| LLM Review: Enhancing Creative Writing via Blind Peer Review Feedback | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.08003) | - | - | - | refinement, revision |
| All Stories Are One Story: Emotional Arc Guided Procedural Game Level Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.02132) | - | - | - | refinement, revision |
| SuperWriter: Reflection-Driven Long-Form Generation with Large Language Models | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.04180) | - | - | - | refinement, revision |
| Finding Flawed Fictions: Evaluating Complex Reasoning in Language Models via Plot Hole Detection | ArXiv 2025 (arXiv preprint) | 2025-04 | [arXiv](https://arxiv.org/abs/2504.11900) | - | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | refinement, revision |
| MLD-EA: Check and Complete Narrative Coherence by Introducing Emotions and Actions | ArXiv 2024 (arXiv preprint) | 2024-12 | [arXiv](https://arxiv.org/abs/2412.02897) | - | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | refinement, revision |
| Collective Critics for Creative Story Generation | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.02428) | - | - | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | refinement, revision |
| SWAG: Storytelling With Action Guidance | EMNLP Findings 2024 (Findings of EMNLP) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.03483) | - | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | refinement, revision |
| GROVE: A Retrieval-augmented Complex Story Generation Framework with A Forest of Evidence | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.05388) | - | - | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | refinement, retrieval |
| EIPE-text: Evaluation-Guided Iterative Plan Extraction for Long-Form Narrative Text Generation | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08185) | - | - | ![citation](https://img.shields.io/badge/citation-9-0A66C2) | refinement, revision |
| Branch-Solve-Merge Improves Large Language Model Evaluation and Generation | ArXiv 2023 (arXiv preprint) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.15123) | - | - | - | refinement, revision |
| Re3: Generating Longer Stories With Recursive Reprompting and Revision | ArXiv 2022 (arXiv preprint) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.06774) | - | - | - | refinement, revision |
| Model Criticism for Long-Form Text Generation | ArXiv 2022 (arXiv preprint) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.08444) | - | - | - | refinement, revision |

<a id="evaluation-benchmarks"></a>
### Evaluation / Benchmarks / Metrics

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Same Lesson, Different Story: Cross-Lingual Reconstruction of Cultural Narratives in Large Language Models | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.24610) | - | - | - | benchmark, evaluation |
| Do Language Models Pass the Bechdel Test? Auditing Gender Biases in LLM-Generated Screenplays | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.24022) | - | - | - | benchmark, screenplay |
| CASPER in the Machine: Insights into Character Variety in LLM-Generated Stories | ACL 2026 (Annual Meeting of the Association for Computational Linguistics) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.22454) | - | - | - | benchmark, evaluation |
| NEST: Narrative Event Structures in Time for Long Video Understanding | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.19706) | - | - | - | benchmark, narrative-understanding |
| NarrativeWorldBench: A Frontier-Saturated Benchmark and a Latent World Model for Long-Horizon Co-Creative Audio Drama | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.17391) | - | - | - | benchmark, audio-story |
| Do Large Language Models Always Tell The Same Stories? | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.17350) | - | - | - | benchmark, diversity |
| ttda704 at SemEval-2026 Task 4: Modeling Narrative Structures via Pseudonymization and Multi-View Sentence Alignment | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.15783) | - | [Code](https://github.com/dinhthienan33/SemEval2026-Task4-ttda704) | - | benchmark, narrative-representation |
| Characterizing Cultural Localization in AI-Generated Stories | ACL Workshop 2026 (C3NLP Workshop) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.14626) | - | - | - | benchmark, evaluation |
| Automated Creativity Evaluation of Language Models Across Open-Ended Tasks | ACL 2026 (Annual Meeting of the Association for Computational Linguistics) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.11762) | - | [Code](https://github.com/tanminsen/creativity-eval) | - | benchmark, evaluation |
| Can Image Models Imagine Time? ImageTime: A Novel Benchmark for Probing Visual World Modeling Through Spatiotemporal Consistency | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.10620) | - | - | - | benchmark, visual-story |
| VideoWeaver: Evaluating and Evolving Skills for Agentic Long Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.08091) | - | [Code](https://github.com/JianhuiWei7/VideoWeaver) | - | benchmark, video-story |
| Neutrality Bites: Gender Representation in AI-Generated Animal Stories | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.07969) | - | - | - | benchmark, evaluation |
| Illusions of the Gold Standard: A Large-scale Analysis of Human Evaluation Protocols for Long-form Text Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.07936) | - | - | - | benchmark, evaluation |
| StoryVideoQA: Scaling Deep Video Understanding with a Large-Scale, Multi-Genre and Auto-Generated Dataset | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.06338) | - | [Code](https://github.com/nercms-mmap/StoryVideoQA) | - | benchmark, video-story |
| ArcANE: Do Role-Playing Language Agents Stay in Character at the Right Time? | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.05553) | - | - | - | benchmark, character-consistency |
| SagaQA: A Multi-hop Reasoning Benchmark for Long-form Narrative Understanding in TV Series | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.03301) | - | - | - | benchmark, narrative-understanding |
| "I've Seen How This Goes": Characterizing Diversity via Progressive Conditional Surprise | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.01811) | - | [Code](https://github.com/AMindToThink/icl-diversity) | - | benchmark, diversity |
| Benchmarking LLM-as-a-Judge for Long-Form Output Evaluation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.01629) | - | [Code](https://github.com/cjj826/LongJudgeBench) | - | benchmark, evaluation |
| RoleCDE:Benchmarking and Mitigating Role-Alignment Trade-offs in Role-Playing Agents | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.01552) | - | [Code](https://github.com/rabbitrose/RoleCDE) | - | benchmark, character-consistency |
| Deep Research as Rubric for Reinforcement Learning | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2606.01091) | - | [Code](https://github.com/meiotoufa/DR-Rubric) | - | evaluation, rubric |
| DirectorBench: Diagnosing Long-Form Video Generation with Personalized Multi-Agent Evaluation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.30090) | - | - | - | benchmark, video-story |
| DynSess: Dynamic Session-Level Evaluation and Optimization Framework for Role-Playing Agents | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.29256) | - | - | - | benchmark, character-consistency |
| MTAVG-Bench 2.0: Diagnosing Failure Modes of Cinematic Expressiveness in Multi-Talker Audio-Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.28035) | - | - | - | benchmark, audio-video |
| Narrative Flattening: How Post-Training Compresses Thematic, Affective, and Stylistic Variation in LLM Fiction | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.27878) | - | - | - | benchmark, evaluation |
| Elias in the Lighthouse, Again? Diagnosing Low Diversity in LLM Stories | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.26492) | - | - | - | benchmark, evaluation |
| OmniToM: Benchmarking Theory of Mind in LLMs via Explicit Belief Modeling | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.26322) | - | - | - | benchmark, narrative-understanding |
| LongAV-Compass: Towards Unified Evaluation of Minute-Scale Audio-Visual Generation Across T2AV, I2AV, and V2AV | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.26244) | - | - | - | benchmark, audio-video |
| QUIET: A Multi-Blank Cascaded Story Cloze Benchmark for LLM Creative Generation Capability | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.25955) | - | - | - | benchmark, evaluation |
| EvalVerse: Pipeline-Aware and Expert-Calibrated Benchmarking for Professional Cinematic Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.23271) | - | - | - | benchmark, video-story |
| When Reasoning Supervision Hurts: TTCW-Based Long-Form Literary Review Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.20364) | - | - | - | evaluation, dataset |
| MSAVBench: Towards Comprehensive and Reliable Evaluation of Multi-Shot Audio-Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.20183) | - | - | - | benchmark, audio-video |
| EntityBench: Towards Entity-Consistent Long-Range Multi-Shot Video Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.15199) | [Project](https://catherine-r-he.github.io/EntityBench/) | [Code](https://github.com/Catherine-R-He/EntityBench) | - | benchmark, video-story |
| Narrative Landscape: Mapping Narrative Dispositions Across LLMs | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.08742) | - | - | - | benchmark, evaluation |
| NARRA-Gym for Evaluating Interactive Narrative Agents | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.08503) | - | - | - | benchmark, evaluation |
| SAGE: Hierarchical LLM-Based Literary Evaluation through Ontology-Grounded Interpretive Dimensions | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.07102) | - | - | - | benchmark, evaluation |
| StoryAlign: Evaluating and Training Reward Models for Story Generation | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.04831) | - | - | - | benchmark, evaluation |
| SemEval-2026 Task 4: Narrative Story Similarity and Narrative Representation Learning | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.21782) | - | - | - | benchmark, evaluation |
| ATANT v1.1: Positioning Continuity Evaluation Against Memory, Long-Context, and Agentic-Memory Benchmarks | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.10981) | - | - | - | benchmark, evaluation |
| Attention Flows: Tracing LLM Conceptual Engagement via Story Summaries | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.06416) | - | - | - | benchmark, dataset |
| MCSC-Bench: Multimodal Context-to-Script Creation for Realistic Video Production | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.15127) | - | - | - | benchmark, dataset |
| Spoiler Alert: Narrative Forecasting as a Metric for Tension in LLM Storytelling | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.09854) | - | - | - | benchmark, evaluation |
| Lessons Without Borders? Evaluating Cultural Alignment of LLMs Using Multilingual Story Moral Generation | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.08797) | - | - | - | benchmark, evaluation |
| Stories of Your Life as Others: A Round-Trip Evaluation of LLM-Generated Life Stories Conditioned on Rich Psychometric Profiles | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.06071) | - | - | - | benchmark, evaluation |
| StoryScope: Investigating idiosyncrasies in AI fiction | ArXiv 2026 (arXiv preprint) | 2026-04 | [arXiv](https://arxiv.org/abs/2604.03136) | - | - | - | benchmark, evaluation |
| Humans vs Vision-Language Models: A Unified Measure of Narrative Coherence | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.25537) | - | - | - | benchmark, evaluation |
| Creative Convergence or Imitation? Genre-Specific Homogeneity in LLM-Generated Chinese Literature | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.14430) | - | - | - | benchmark, evaluation |
| Lost in Stories: Consistency Bugs in Long Story Generation by LLMs | ArXiv 2026 (arXiv preprint) | 2026-03 | [arXiv](https://arxiv.org/abs/2603.05890) | [Project](https://picrew.github.io/constory-bench.github.io/) | [Code](https://github.com/Picrew/ConStory-Bench) | - | benchmark, evaluation |
| LLMs Exhibit Significantly Lower Uncertainty in Creative Writing Than Professional Writers | ArXiv 2026 (arXiv preprint) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.16162) | - | - | - | benchmark, evaluation |
| Do readers prefer AI-generated Italian short stories? | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.17363) | - | - | - | benchmark, evaluation |
| STAGE: A Full-Screenplay Benchmark for Reasoning over Evolving Storie | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.08510) | - | - | - | benchmark, screenplay |
| Evaluation Framework for AI Creativity: A Case Study Based on Story Generation | ArXiv 2026 (arXiv preprint) | 2026-01 | [arXiv](https://arxiv.org/abs/2601.03698) | - | - | - | benchmark, evaluation |
| Evaluating LLM Story Generation through Large-scale Network Analysis of Social Structures | ArXiv 2025 (arXiv preprint) | 2025-10 | [arXiv](https://arxiv.org/abs/2510.18932) | - | - | - | benchmark, evaluation |
| EvolvR: Self-Evolving Pairwise Reasoning for Story Evaluation to Enhance Generation | ArXiv 2025 (arXiv preprint) | 2025-08 | [arXiv](https://arxiv.org/abs/2508.06046) | - | - | - | benchmark, evaluation |
| LitBench: A Benchmark and Dataset for Reliable Evaluation of Creative Writing | ArXiv 2025 (arXiv preprint) | 2025-07 | [arXiv](https://arxiv.org/abs/2507.00769) | - | - | - | benchmark, dataset |
| WritingBench: A Comprehensive Benchmark for Generative Writing | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.05244) | - | - | - | benchmark, evaluation |
| CoKe: Customizable Fine-Grained Story Evaluation via Chain-of-Keyword Rationalization | ArXiv 2025 (arXiv preprint) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.17136) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | benchmark, evaluation |
| LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm | ArXiv 2025 (arXiv preprint) | 2025-02 | [arXiv](https://arxiv.org/abs/2502.19103) | - | [Code](https://github.com/Wusiwei0410/LongEval) | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| Echoes in AI: Quantifying Lack of Plot Diversity in LLM Outputs | ArXiv 2025 (arXiv preprint) | 2025-01 | [arXiv](https://arxiv.org/abs/2501.00273) | - | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | benchmark, evaluation |
| Evaluating Creative Short Story Generation in Humans and Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-11 | [arXiv](https://arxiv.org/abs/2411.02316) | - | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | benchmark, evaluation |
| Small Language Models can Outperform Humans in Short Creative Writing: A Study Comparing SLMs with Humans and LLMs | COLING 2025 (International Conference on Computational Linguistics) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.11547) | - | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | benchmark, evaluation |
| HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-09 | [arXiv](https://arxiv.org/abs/2409.16191) | - | [Code](https://github.com/Quehry/HelloBench) | - | benchmark, evaluation |
| STORYSUMM: Evaluating Faithfulness in Story Summarization | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.06501) | - | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| Pron vs Prompt: Can Large Language Models already Challenge a World-Class Fiction Author at Creative Text Writing? | ArXiv 2024 (arXiv preprint) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01119) | - | - | ![citation](https://img.shields.io/badge/citation-17-0A66C2) | benchmark, evaluation |
| Are Large Language Models Capable of Generating Human-Level Narratives? | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.13248) | - | - | ![citation](https://img.shields.io/badge/citation-33-0A66C2) | benchmark, evaluation |
| Do Language Models Enjoy Their Own Stories? Prompting Large Language Models for Automatic Story Evaluation | TACL 2024 (Transactions of the Association for Computational Linguistics) | 2024-05 | [arXiv](https://arxiv.org/abs/2405.13769) | - | - | ![citation](https://img.shields.io/badge/citation-18-0A66C2) | benchmark, evaluation |
| Reading Subtext: Evaluating Large Language Models on Short Story Summarization with Writers | TACL 2024 (Transactions of the Association for Computational Linguistics) | 2024-03 | [arXiv](https://arxiv.org/abs/2403.01061) | - | - | ![citation](https://img.shields.io/badge/citation-15-0A66C2) | benchmark, evaluation |
| Learning Personalized Alignment for Evaluating Open-ended Text Generation | EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.03304) | - | - | ![citation](https://img.shields.io/badge/citation-11-0A66C2) | benchmark, evaluation |
| A Confederacy of Models: a Comprehensive Evaluation of LLMs on Creative Writing | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.08433) | - | - | ![citation](https://img.shields.io/badge/citation-83-0A66C2) | benchmark, evaluation |
| Art or Artifice? Large Language Models and the False Promise of Creativity | CHI 2023 (Conference on Human Factors in Computing Systems) | 2023-09 | [arXiv](https://arxiv.org/abs/2309.14556) | - | - | ![citation](https://img.shields.io/badge/citation-136-0A66C2) | benchmark, evaluation |
| HAUSER: Towards Holistic and Automatic Evaluation of Simile Generation | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-06 | [arXiv](https://arxiv.org/abs/2306.07554) | - | - | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | benchmark, evaluation |
| Can Large Language Models Be an Alternative to Human Evaluations? | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.01937) | - | - | ![citation](https://img.shields.io/badge/citation-634-0A66C2) | benchmark, evaluation |
| DeltaScore: Evaluating Story Generation with Differentiating Perturbations | EMNLP Findings 2023 (Findings of EMNLP) | 2023-03 | [arXiv](https://arxiv.org/abs/2303.08991) | - | - | ![citation](https://img.shields.io/badge/citation-4-0A66C2) | benchmark, evaluation |
| StoryER: Automatic Story Evaluation via Ranking, Rating and Reasoning | EMNLP 2022 (Conference on Empirical Methods in Natural Language Processing) | 2022-10 | [arXiv](https://arxiv.org/abs/2210.08459) | - | [Code](https://github.com/sairin1202/StoryER) | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | benchmark, evaluation |
| Of Human Criteria and Automatic Metrics: A Benchmark of the Evaluation of Story Generation | COLING 2022 (International Conference on Computational Linguistics) | 2022-08 | [arXiv](https://arxiv.org/abs/2208.11646) | - | - | ![citation](https://img.shields.io/badge/citation-55-0A66C2) | benchmark, evaluation |

<a id="datasets-surveys"></a>
### Datasets / Surveys / Resources

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AI Fiction in the Wild | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.22748) | - | - | - | resource, fiction-generation |
| Characterizing Narrative Content in Web-scale LLM Pretraining Data | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.19468) | - | - | - | dataset, resource |
| OmniVideo-100K: A Dataset for Audio-Visual Reasoning through Structured Scripts and Evidence Chains | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.14702) | - | [Code](https://github.com/MiG-NJU/OmniVideo-100K) | - | dataset, audio-video |
| CineDance: Towards Next-Generation Multi-Shot Long-Form Cinematic Audio-Video Generation | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.09639) | [Project](https://aliothchen.github.io/projects/CineDance/) | - | - | dataset, audio-video |
| AI as a Tool for Simulation-Based Experiments in Literary Studies | ArXiv 2026 (arXiv preprint) | 2026-06 | [arXiv](https://arxiv.org/abs/2606.02293) | - | - | - | resource, literary-study |
| GraphLit: Learning Text-Enriched Dynamic Character Network Representations for Literary Study | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.28643) | - | - | - | dataset, resource |
| LitSeg: Narrative-Aware Document Segmentation for Literary RAG | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.27156) | - | - | - | dataset, resource |
| Manga109-v2026: Revisiting Manga109 Annotations for Modern Manga Understanding | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.21182) | [Project](https://manga109.github.io/manga109-project-website/en/) | - | - | dataset, dataset |
| LLMs for automatic annotation of Mandarin narrative transcripts | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.17205) | - | - | - | dataset, narrative-understanding |
| StereoTales: A Multilingual Framework for Open-Ended Stereotype Discovery in LLMs | ArXiv 2026 (arXiv preprint) | 2026-05 | [arXiv](https://arxiv.org/abs/2605.10442) | - | - | - | dataset, dataset |
| Narrative Theory-Driven LLM Methods for Automatic Story Generation and Understanding: A Survey | ArXiv 2026 (arXiv preprint) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.15851) | - | - | - | dataset, survey |
| MUSE: A Multi-agent Framework for Unconstrained Story Envisioning via Closed-Loop Cognitive Orchestration | ArXiv 2026 (arXiv preprint) | 2026-02 | [arXiv](https://arxiv.org/abs/2602.03028) | - | - | - | dataset, resource |
| StoryWriter: A Multi-Agent Framework for Long Story Generation | ArXiv 2025 (arXiv preprint) | 2025-06 | [arXiv](https://arxiv.org/abs/2506.16445) | - | - | - | dataset, resource |
| Reasoning-Enhanced Self-Training for Long-Form Personalized Text Generation | ArXiv 2025 (arXiv preprint) | 2025-01 | [arXiv](https://arxiv.org/abs/2501.04167) | [Project](https://github.com/Alex-Gurung/ReasoningNCP) | [Code](https://github.com/Alex-Gurung/ReasoningNCP) | - | dataset, resource |
| Multi-Agent Based Character Simulation for Story Writing | IN2Writing 2025 (IN2Writing Workshop) | 2025-01 | [Published](https://aclanthology.org/2025.in2writing-1.9/) | - | - | - | dataset, resource |
| BookWorm: A Dataset for Character Description and Analysis | EMNLP Findings 2024 (Findings of EMNLP) | 2024-10 | [arXiv](https://arxiv.org/abs/2410.10372) | - | - | ![citation](https://img.shields.io/badge/citation-2-0A66C2) | dataset, dataset |
| What Makes a Good Story and How Can We Measure It? A Comprehensive Survey of Story Evaluation | ArXiv 2024 (arXiv preprint) | 2024-08 | [arXiv](https://arxiv.org/abs/2408.14622) | - | - | ![citation](https://img.shields.io/badge/citation-7-0A66C2) | dataset, survey |
| The GPT-WritingPrompts Dataset: A Comparative Analysis of Character Portrayal in Short Stories | EMNLP Workshop 2025 (EMNLP Workshop) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.16767) | - | [Code](https://github.com/KristinHuangg/gpt-writing-prompts) | ![citation](https://img.shields.io/badge/citation-3-0A66C2) | dataset, dataset |
| CollabStory: Multi-LLM Collaborative Story Generation and Authorship Analysis | NAACL Findings 2025 (Findings of NAACL) | 2024-06 | [arXiv](https://arxiv.org/abs/2406.12665) | - | [Code](https://github.com/saranya-venkatraman/CollabStory) | ![citation](https://img.shields.io/badge/citation-14-0A66C2) | dataset, resource |
| The Value, Benefits, and Concerns of Generative AI-Powered Assistance in Writing | CHI 2024 (Conference on Human Factors in Computing Systems) | 2024-03 | [arXiv](https://arxiv.org/abs/2403.12004) | - | - | ![citation](https://img.shields.io/badge/citation-59-0A66C2) | dataset, resource |
| Large Language Models Fall Short: Understanding Complex Relationships in Detective Narratives | ACL Findings 2024 (Findings of ACL) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.11051) | - | - | ![citation](https://img.shields.io/badge/citation-13-0A66C2) | dataset, resource |
| CMDAG: A Chinese Metaphor Dataset with Annotated Grounds as CoT for Boosting Metaphor Generation | LREC-COLING 2024 (LREC-COLING) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.13145) | - | [Code](https://github.com/JasonShao55/Chinese_Metaphor_Explanation) | ![citation](https://img.shields.io/badge/citation-6-0A66C2) | dataset, dataset |
| Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models | ArXiv 2024 (arXiv preprint) | 2024-02 | [arXiv](https://arxiv.org/abs/2402.14207) | - | - | - | dataset, resource |
| Weaver: Foundation Models for Creative Writing | ArXiv 2024 (arXiv preprint) | 2024-01 | [arXiv](https://arxiv.org/abs/2401.17268) | - | - | ![citation](https://img.shields.io/badge/citation-20-0A66C2) | dataset, resource |
| Reflections & Resonance: Two-Agent Partnership for Advancing LLM-based Story Annotation | LREC-COLING 2024 (LREC-COLING) | 2024-01 | [Published](https://aclanthology.org/2024.lrec-main.1206/) | - | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | dataset, resource |
| CLAUSE-ATLAS: A Corpus of Narrative Information to Scale up Computational Literary Analysis | LREC-COLING 2024 (LREC-COLING) | 2024-01 | [Published](https://aclanthology.org/2024.lrec-main.292/) | - | - | ![citation](https://img.shields.io/badge/citation-0-0A66C2) | dataset, resource |
| STONYBOOK: A System and Resource for Large-Scale Analysis of Novels | ArXiv 2023 (arXiv preprint) | 2023-11 | [arXiv](https://arxiv.org/abs/2311.03614) | - | - | ![citation](https://img.shields.io/badge/citation-1-0A66C2) | dataset, resource |
| Are NLP Models Good at Tracing Thoughts: An Overview of Narrative Understanding | EMNLP Findings 2023 (Findings of EMNLP) | 2023-10 | [arXiv](https://arxiv.org/abs/2310.18783) | - | - | ![citation](https://img.shields.io/badge/citation-5-0A66C2) | dataset, resource |
| StoryWars: A Dataset and Instruction Tuning Baselines for Collaborative Story Understanding and Generation | ACL 2023 (Annual Meeting of the Association for Computational Linguistics) | 2023-05 | [arXiv](https://arxiv.org/abs/2305.08152) | - | - | ![citation](https://img.shields.io/badge/citation-8-0A66C2) | dataset, dataset |
| Open-world Story Generation with Structured Knowledge Enhancement: A Comprehensive Survey | Neurocomputing 2023 (Neurocomputing (Journal)) | 2022-12 | [arXiv](https://arxiv.org/abs/2212.04634) | - | - | - | dataset, survey |
| Co-Writing Screenplays and Theatre Scripts with Language Models: An Evaluation by Industry Professionals | ArXiv 2022 (arXiv preprint) | 2022-09 | [arXiv](https://arxiv.org/abs/2209.14958) | [Project](https://github.com/google-deepmind/dramatron) | [Code](https://github.com/google-deepmind/dramatron) | - | dataset, screenplay |
| A corpus for understanding and generating moral stories | NAACL 2022 (North American Chapter of ACL) | 2022-04 | [arXiv](https://arxiv.org/abs/2204.09438) | - | - | ![citation](https://img.shields.io/badge/citation-10-0A66C2) | dataset, resource |

<a id="open-source-projects"></a>
### Open-source Projects (No Paper Required)

| Title | Venue | Date | Paper | Project | Code | Citations | Tags |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FireRed-OpenStoryline | GitHub 2026 (Open-source repository) | 2026-01 | - | [Project](https://github.com/FireRedTeam/FireRed-OpenStoryline) | [Code](https://github.com/FireRedTeam/FireRed-OpenStoryline) | - | tooling, open-source |
| ReasoningNCP (Official Repository) | GitHub 2025 (Open-source repository) | 2025-03 | [arXiv](https://arxiv.org/abs/2503.22828) | [Project](https://github.com/Alex-Gurung/ReasoningNCP) | [Code](https://github.com/Alex-Gurung/ReasoningNCP) | - | tooling, open-source |
| SEED-Story (Official Repository) | GitHub 2024 (Open-source repository) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.08683) | [Project](https://github.com/TencentARC/SEED-Story) | [Code](https://github.com/TencentARC/SEED-Story) | - | tooling, open-source |
| IBSEN (Official Repository) | GitHub 2024 (Open-source repository) | 2024-07 | [arXiv](https://arxiv.org/abs/2407.01093) | [Project](https://github.com/OpenDFM/ibsen) | [Code](https://github.com/OpenDFM/ibsen) | - | tooling, open-source |
| RENarGen (Official Repository) | GitHub 2024 (Open-source repository) | 2024-04 | [arXiv](https://arxiv.org/abs/2404.00829) | [Project](https://github.com/adbrei/RENarGen) | [Code](https://github.com/adbrei/RENarGen) | - | tooling, open-source |
| fictionx-story-gen | GitHub 2024 (Open-source repository) | 2024-01 | - | [Project](https://github.com/WyseOS/fictionx-story-gen) | [Code](https://github.com/WyseOS/fictionx-story-gen) | - | tooling, open-source |
| SillyTavern | GitHub 2023 (Open-source repository) | 2023-01 | - | [Project](https://github.com/SillyTavern/SillyTavern) | [Code](https://github.com/SillyTavern/SillyTavern) | - | tooling, open-source |
| GOAT-Storytelling-Agent | GitHub 2023 (Open-source repository) | 2023-01 | - | [Project](https://github.com/GOAT-AI-lab/GOAT-Storytelling-Agent) | [Code](https://github.com/GOAT-AI-lab/GOAT-Storytelling-Agent) | - | tooling, open-source |
| Dramatron (Official Repository) | GitHub 2022 (Open-source repository) | 2022-09 | [arXiv](https://arxiv.org/abs/2209.14958) | [Project](https://github.com/google-deepmind/dramatron) | [Code](https://github.com/google-deepmind/dramatron) | - | tooling, screenplay |
| TavernAI | GitHub 2022 (Open-source repository) | 2022-01 | - | [Project](https://github.com/TavernAI/TavernAI) | [Code](https://github.com/TavernAI/TavernAI) | - | tooling, open-source |

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
