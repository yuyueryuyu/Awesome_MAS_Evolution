<div align="center">

<img src="figs/logo.png" style="width: 70%;"/>

## Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution

[![Awesome](https://img.shields.io/badge/Awesome-0066CC?style=for-the-badge&logo=awesome-lists&logoColor=white)](https://github.com/sindresorhus/awesome) [![Survey](https://img.shields.io/badge/Paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_ARXIV_ID) [![Github](https://img.shields.io/badge/Awesome--MAS--Evolution-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mira-ai-lab/Awesome_MAS_Evolution) [![HF Papers](https://img.shields.io/badge/HF--Paper-%23FFD14D?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/papers/PLACEHOLDER_HF_PAPER_ID) 

</div>

> We welcome issues for missing or misclassified papers: `https://github.com/mira-ai-lab/Awesome_MAS_Evolution`.

## News

- **[2026-04-15]** The repository for our survey is established!

## Citation

If you find this survey useful, please cite (update venue fields after publication):

Survey placeholders in this README can be updated via config file `configs/readme_survey_config.json` without editing README directly:
`python scripts/apply_readme_config.py`

```bibtex
@article{qi2026beyond,
  title   = {Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution},
  author  = {Qi, Shihao and Ma, Jie and Xing, Rui and Guo, Wei and Huang, Xiao and Gao, Zhitao and Deng, Jianhao and Liu, Jun and Zhang, Lingling and Wei, Bifan and Wang, Pinghui and Wu, Yaqiang and Liu, Hui and Tao, Jing and Liu, Tongliang},
  journal = {PLACEHOLDER_VENUE},
  year    = {PLACEHOLDER_YEAR}
}
```

## Contents

- [Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution](#beyond-individual-intelligence-a-survey-of-multi-agent-collaboration-attribution-and-evolution)
- [News](#news)
- [Citation](#citation)
- [Contents](#contents)
- [Overview](#overview)
- [Paper List](#paper-list)
  - [Individual Intelligence: Core Capabilities and Boundary Analysis](#individual-intelligence-core-capabilities-and-boundary-analysis)
    - [Overview: From LLM to LLM-based Agent](#overview-from-llm-to-llm-based-agent)
    - [Reasoning: Input-Stage Enhancement](#reasoning-input-stage-enhancement)
    - [Reasoning: Reasoning-Process Enhancement](#reasoning-reasoning-process-enhancement)
    - [Reasoning: Output-Stage Regulation](#reasoning-output-stage-regulation)
    - [Memory: Formation](#memory-formation)
    - [Memory: Maintenance](#memory-maintenance)
    - [Memory: Retrieval and Utilization](#memory-retrieval-and-utilization)
    - [Planning: Decomposition-Based](#planning-decomposition-based)
    - [Planning: Search-Based](#planning-search-based)
    - [Tool Use: Capability Acquisition](#tool-use-capability-acquisition)
    - [Tool Use: Invocation](#tool-use-invocation)
    - [Tool Use: Generalization](#tool-use-generalization)
  - [Multi-Agent Collaboration](#multi-agent-collaboration)
    - [Role](#role)
    - [Communication](#communication)
    - [Orchestration](#orchestration)
    - [Interaction](#interaction)
    - [Evaluation](#evaluation)
    - [Discussion](#discussion)
  - [Multi-Agent System Failure Attribution](#multi-agent-system-failure-attribution)
    - [Formal Definition](#formal-definition)
    - [MAS Failure Category](#mas-failure-category)
    - [Failure Attribution Taxonomy](#failure-attribution-taxonomy)
    - [Failure Attribution Evaluation](#failure-attribution-evaluation)
    - [Challenges and Future Directions](#challenges-and-future-directions)
  - [Multi-Agent System Self-Evolution](#multi-agent-system-self-evolution)
    - [Motivation](#motivation)
    - [From Attribution to Evolution](#from-attribution-to-evolution)
    - [Formalizing Multi-Agent System Self-Evolution](#formalizing-multi-agent-system-self-evolution)
    - [MAS Self-Evolution Taxonomy](#mas-self-evolution-taxonomy)
    - [Agentic Self-Evolution](#agentic-self-evolution)
    - [Systemic Self-Evolution](#systemic-self-evolution)
    - [Meta Self-Evolution](#meta-self-evolution)
- [Acknowledgment](#acknowledgment)
- [Star History](#star-history)

## Overview

This companion repository supports the survey **Beyond Individual Intelligence: A Survey of Multi-agent Collaboration, Attribution and Evolution**, which studies the **full operational lifecycle** of LLM-based multi-agent systems (MAS): single-agent foundations, collaboration design, runtime failure attribution, and self-evolution that closes the loop from diagnosis to structural adaptation.

<p align="center">
   <img src="figs/teaser.png" alt="Survey overview figure (replace with lifecycle figure if needed)" style="width: 100%;">
</p>

We organize the literature around **four main pillars** (mirroring the manuscript):

1. **Individual intelligence:** Reasoning, memory, planning, and tool use as modular capabilities of a single LLM-based agent.
2. **Multi-agent collaboration:** Roles, communication modes/protocols, orchestration topology, and interaction policies.
3. **Failure attribution:** Formal definitions, failure taxonomies, attribution methods, and evaluation benchmarks.
4. **Self-evolution:** From postmortem signals to updates at agentic, systemic, and meta levels (prompts, memory, parameters, topology, team composition, and whole-system design).

## Paper List

### Individual Intelligence: Core Capabilities and Boundary Analysis

#### Overview: From LLM to LLM-based Agent

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `openai2023gpt4` | GPT-4 technical report | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.08774) | - |
| 2023 | `touvron2023llama` | LLaMA: Open and efficient foundation language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2302.13971) | - |
| 2024 | `jimenez2024swebench` | SWE-bench: Can language models resolve real-world GitHub issues? | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024-05 | `bran2024chemcrow` | Augmenting large language models with chemistry tools | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhou2024webarena` | WebArena: A realistic web environment for building autonomous agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yao2023react` | ReAct: Synergizing reasoning and acting in language models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `xi2023rise` | The rise and potential of large language model based agents: A survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.07864) | - |

#### Reasoning: Input-Stage Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `xi2023rise` | The rise and potential of large language model based agents: A survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.07864) | - |
| TBD | `wei2022chain` | PLACEHOLDER_TITLE_FOR_wei2022chain | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `huang2023towards` | Towards Reasoning in Large Language Models: A Survey | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `sun2025survey` | A Survey of Reasoning Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.17419) | - |

#### Reasoning: Reasoning-Process Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Reasoning: Output-Stage Regulation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `ji2023hallucination` | Survey of Hallucination in Natural Language Generation | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Formation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `zhang2024memorymechanism` | A Survey on the Memory Mechanism of Large Language Model based Agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wu2025humantoai` | From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.15965) | - |

#### Memory: Maintenance

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Retrieval and Utilization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Planning: Decomposition-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `wei2025plangenllms` | PlanGenLLMs: A modern survey of LLM planning capabilities | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `xie2024travelplanner` | TravelPlanner: A Benchmark for Real-World Planning with Language Agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Planning: Search-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `yao2024tot` | Tree of Thoughts: Deliberate Problem Solving with Large Language Models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhou2024lats` | Language agent tree search unifies reasoning, acting, and planning in language models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Capability Acquisition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `wang2024codeact` | Executable Code Actions Elicit Better LLM Agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Invocation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Generalization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent Collaboration

#### Role

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Communication

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Orchestration

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `yue2025masrouter` | Masrouter: Learning to route llms for multi-agent systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `liu2025rcr` | Rcr-router: Efficient role-aware context routing for multi-agent llm systems with structured memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.04903) | - |
| 2026 | `zhao2026tcandon` | TCAndon-Router: Adaptive Reasoning Router for Multi-Agent Collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.04544) | - |
| 2025 | `yang2025agentnet` | Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems, 2025 | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Interaction

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `lee2025gemmas` | Gemmas: Graph-based evaluation metrics for multi agent systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `gioacchini2024agentquest` | Agentquest: A modular benchmark framework to measure progress and improve llm agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `agashe2025llm` | LLM-Coordination: Evaluating and Analyzing Multi-agent Coordination Abilities in Large Language Models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024llmarena` | LLMArena: Assessing Capabilities of Large Language Models in Dynamic Multi-Agent Environments | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024battleagentbench` | BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2408.15971) | - |
| 2025 | `zhu2025multiagentbench` | MultiAgentBench : Evaluating the Collaboration and Competition of LLM agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `schmidgall2025agentclinic` | AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.07960) | - |
| 2025 | `fan2025aihospital` | AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shu2024towards` | Towards effective genai multi-agent collaboration: design and evaluation for enterprise applications | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.05449) | - |
| 2025 | `geng2025realm` | Realm-bench: A real-world planning benchmark for llms and multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.18836) | - |

#### Discussion

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `li2023camel` | Camel: Communicative agents for" mind" exploration of large language model society | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `fu2023improving` | Improving language model negotiation with self-play and in-context learning from ai feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.10142) | - |
| 2023 | `hong2023metagpt` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wu2024autogen` | AutoGen: Enabling next-gen LLM applications via multi-agent conversations | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024agentverse` | Agentverse: Facilitating multi-agent collaboration and exploring emergent behaviors | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024autoagents` | AutoAgents: a framework for automatic agent generation | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `park2025maporl` | MAPoRL: Multi-agent post-co-training for collaborative large language models with reinforcement learning | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025osc` | OSC: Cognitive Orchestration through Dynamic Knowledge Alignment in Multi-Agent LLM Collaboration | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `dang2025multi` | Multi-agent collaboration via evolving orchestration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.19591) | - |
| 2026 | `jafari2026lightweight` | A Lightweight Modular Framework for Constructing Autonomous Agents Driven by Large Language Models: Design, Implementation, and Applications in AgentForge | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.13383) | - |
| 2026 | `liu2026masfactory` | MASFactory: A Graph-centric Framework for Orchestrating LLM-Based Multi-Agent Systems with Vibe Graphing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.06007) | - |
| 2018 | `bechlioulis2018collaborative` | Collaborative multi-robot transportation in obstacle-cluttered environments via implicit communication | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhao2025udon` | UDON: Uncertainty-weighted Distributed Optimization for Multi-Robot Neural Implicit Mapping under Extreme Communication Constraints | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.12702) | - |
| 2025 | `yang2025implicit` | Implicit communication in human-robot collaborative transport | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Failure Attribution

#### Formal Definition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `zhang2025which` | Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2026 | `wang2026flat` | From Flat Logs to Causal Graphs: Hierarchical Failure Attribution for LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.23701) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |

#### MAS Failure Category

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |

#### Failure Attribution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `Zhang2025AgenTracerWI` | AgenTracer: Who Is Inducing Failure in the LLM Agentic Systems? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.03312) | - |
| 2026 | `wang2026flat` | From Flat Logs to Causal Graphs: Hierarchical Failure Attribution for LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.23701) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2025 | `West2025AbductAP` | Abduct, Act, Predict: Scaffolding Causal Inference for Automated Failure Attribution in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.10401) | - |
| 2025 | `deshpande2025trail` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2025 | `Ge2025WhoII` | Who is introducing the failure? automatically attributing failures of multi-agent systems via spectrum analysis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.13782) | - |
| 2025 | `kong2025aegis` | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.14295) | - |
| 2025 | `Shen2025MetacognitiveSF` | Metacognitive Self-Correction for Multi-Agent System via Prototype-Guided Next-Execution Reconstruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.14319) | - |
| 2025 | `zhengtrajectory` | Trajectory Graph Copilot: Pre-Action Error Diagnosis in LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2026 | `advani2026trajectory` | Trajectory Guard--A Lightweight, Sequence-Aware Model for Real-Time Anomaly Detection in Agentic AI | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.00516) | - |
| 2026 | `sheng2026dills` | DiLLS: Interactive Diagnosis of LLM-based Multi-agent Systems via Layered Summary of Agent Behaviors | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.05446) | - |
| 2026 | `anonymous2026seeing` | Seeing the Whole Elephant: A Benchmark for Failure Attribution in LLM-based Multi-Agent Systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Zhu2025WhereLA` | Where LLM Agents Fail and How They can Learn From Failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025 | `barrak2025traceability` | Traceability and Accountability in Role-Specialized Multi-Agent LLM Pipelines | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `banerjee2025` | Where Did It All Go Wrong? A Hierarchical Look into Multi-Agent Error Attribution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.04886) | - |
| 2025 | `ma2025dover` | DoVer: Intervention-Driven Auto Debugging for LLM Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.06749) | - |
| 2026 | `barke2026agentrx` | AgentRx: Diagnosing AI Agent Failures from Execution Trajectories | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.02475) | - |
| 2025 | `wang2025xagen` | XAgen: An Explainability Tool for Identifying and Correcting Failures in Multi-Agent Workflows | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.17896) | - |
| 2026 | `sun2026scope` | Scope Delineation Before Localization: A Two-Stage Framework for Enhancing Failure Attribution in Multi-Agent Systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chen2025understanding` | Understanding individual agent importance in multi-agent system via counterfactual reasoning | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `epperson2025interactive` | Interactive debugging and steering of multi-agent ai systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Ma2025AutomaticFA` | Automatic Failure Attribution and Critical Step Prediction Method for Multi-Agent Systems Based on Causal Inference | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.08682) | - |
| 2023 | `triantafyllou2023agent` | Agent-specific effects: A causal effect propagation analysis in multi-agent MDPs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.11334) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2026 | `ma2026demystifying` | Demystifying the Lifecycle of Failures in Platform-Orchestrated Agentic Workflows | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2024 | `triantafyllou2024counterfactual` | Counterfactual effect decomposition in multi-agent sequential decision making | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.12539) | - |
| 2026 | `anonymous2025diagnosing` | Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `zhu2026raffles` | Raffles: Reasoning-based attribution of faults for llm systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Failure Attribution Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `deshpande2025trail` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2025 | `Zhu2025WhereLA` | Where LLM Agents Fail and How They can Learn From Failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `kong2025aegis` | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.14295) | - |
| 2025 | `Zhang2025GraphTracerGF` | GraphTracer: Graph-Guided Failure Tracing in LLM Agents for Robust Multi-Turn Deep Search | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.10581) | - |
| 2026 | `anonymous2025diagnosing` | Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2026 | `anonymous2026seeing` | Seeing the Whole Elephant: A Benchmark for Failure Attribution in LLM-based Multi-Agent Systems | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Challenges and Future Directions

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Self-Evolution

#### Motivation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `kim2025towards` | Towards a science of scaling agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.08296) | - |
| TBD | `koduriefficiency` | Efficiency-First Design for LLM-Based Multi-Agent Systems: A Framework and Empirical Analysis | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### From Attribution to Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2007 | `galhardo2007mutation` | Mutation as a stress response and the regulation of evolvability | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 1989 | `goss1989self` | Self-organized shortcuts in the Argentine ant | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Formalizing Multi-Agent System Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `PLACEHOLDER_ROW` | *No citation extracted for this subsection yet; keep this placeholder for manual curation.* | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### MAS Self-Evolution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `lu2024morphagent` | Morphagent: Empowering agents through self-evolving profiles and decentralized collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.15048) | - |
| 2024 | `bo2024Reflective` | Reflective Multi-Agent Collaboration based on Large Language Models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `chen2025optima` | PLACEHOLDER_TITLE_FOR_chen2025optima | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `xue2025comas` | CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08529) | - |
| 2024 | `zhuge2024gptswarm` | Gptswarm: Language agents as optimizable graphs | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Agentic Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `lu2024morphagent` | Morphagent: Empowering agents through self-evolving profiles and decentralized collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.15048) | - |
| 2025 | `mangla2025negotiationgym` | NegotiationGym: Self-Optimizing Agents in a Multi-Agent Social Simulation Environment | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.04368) | - |
| 2024 | `bo2024Reflective` | Reflective Multi-Agent Collaboration based on Large Language Models | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chen2024agentcourt` | Agentcourt: Simulating court with adversarial evolvable lawyer agents | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `guan2024richelieu` | Richelieu: Self-evolving llm-based agents for ai diplomacy | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025learn` | Learn as individuals, evolve as a team: Multi-agent llms adaptation in embodied environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.07232) | - |
| 2025 | `wang2025annaagent` | AnnaAgent: Dynamic evolution agent system with multi-session memory for realistic seeker simulation | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `xue2025comas` | CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08529) | - |
| 2025 | `chen2025multiagent` | Multi-agent evolve: Llm self-improve through co-evolution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.23595) | - |
| 2025 | `pan2025advevo` | AdvEvo-MARL: Shaping Internalized Safety through Adversarial Co-Evolution in Multi-Agent Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01586) | - |
| 2026 | `zhou2026epistemic` | Epistemic Context Learning: Building Trust the Right Way in LLM-Based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.21742) | - |
| TBD | `chen2025optima` | PLACEHOLDER_TITLE_FOR_chen2025optima | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `kar2026towards` | Towards AGI A Pragmatic Approach Towards Self Evolving Agent | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.11658) | - |
| 2024 | `liu2024odyssey` | Odyssey: Empowering minecraft agents with open-world skills | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.15325) | - |

#### Systemic Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `zhuge2024gptswarm` | Gptswarm: Language agents as optimizable graphs | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025adaptive` | Adaptive graph pruning for multi-agent communication | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.02951) | - |
| 2024 | `zhang2024cut` | Cut the crap: An economical communication pipeline for llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.02506) | - |
| 2025 | `zhou2025multi` | Multi-agent design: Optimizing agents with better prompts and topologies | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.02533) | - |
| 2025 | `yang2025agentnet` | Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems, 2025 | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `chen2023autoagents` | Autoagents: A framework for automatic agent generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.17288) | - |
| 2025 | `yuan2025evoagent` | Evoagent: Towards automatic multi-agent generation via evolutionary algorithms | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `hu2024self` | Self-evolving multi-agent collaboration networks for software development | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.16946) | - |
| 2025 | `ma2025agentic` | Agentic neural networks: Self-evolving multi-agent systems via textual backpropagation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.09046) | - |
| 2025 | `zhang2025g` | G-memory: Tracing hierarchical memory for multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.07398) | - |

#### Meta Self-Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `hu2025automated` | Automated design of agentic systems, 2024 | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `rosser2025agentbreeder` | AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.00757) | - |
| 2025 | `zhang2025aflow` | Aflow: Automating agentic workflow generation, 2024 | [![Placeholder](https://img.shields.io/badge/placeholder-9E9E9E?style=for-the-badge)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shang2024agentsquare` | Agentsquare: Automatic llm agent search in modular design space | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.06153) | - |
| 2025 | `ke2025mas` | Mas-zero: Designing multi-agent systems with zero supervision | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.14996) | - |
| 2025 | `zhang2025multi` | Multi-agent architecture search via agentic supernet | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.04180) | - |
| 2025 | `ye2025mas` | Mas-gpt: Training llms to build llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.03686) | - |
| 2025 | `wang2025mas` | MAS $\^ 2$: Self-Generative, Self-Configuring, Self-Rectifying Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.24323) | - |

## Acknowledgment

This survey is extended and refined from the original **Awesome RL for LRMs** repo. We are deeply grateful to all contributors for their efforts, and we sincerely thank for their all interest in **Awesome RL for LRMs**. The contents of the previous repository are available [here](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mira-ai-lab/Awesome_MAS_Evolution&type=Date)](https://www.star-history.com/#mira-ai-lab/Awesome_MAS_Evolution&Date)
