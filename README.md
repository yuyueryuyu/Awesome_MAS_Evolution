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

The tables below are **auto-generated from citations in** `latex/bare_jrnl_new_sample4.tex` and metadata in `latex/reference.bib`.

> Auto-generation script: `python scripts/generate_paper_list.py`

---

### Individual Intelligence: Core Capabilities and Boundary Analysis

#### Overview: From LLM to LLM-based Agent

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `openai2023gpt4` | GPT-4 technical report | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.08774) | - |
| 2023 | `touvron2023llama` | LLaMA: Open and efficient foundation language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2302.13971) | - |
| 2024 | `jimenez2024swebench` | SWE-bench: Can language models resolve real-world GitHub issues? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024-05 | `bran2024chemcrow` | Augmenting large language models with chemistry tools | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhou2024webarena` | WebArena: A realistic web environment for building autonomous agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yao2023react` | ReAct: Synergizing reasoning and acting in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `xi2023rise` | The rise and potential of large language model based agents: A survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.07864) | - |

#### Reasoning: Input-Stage Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `xi2023rise` | The rise and potential of large language model based agents: A survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.07864) | - |
| TBD | `wei2022chain` | PLACEHOLDER_TITLE_FOR_wei2022chain | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `huang2023towards` | Towards Reasoning in Large Language Models: A Survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `sun2025survey` | A Survey of Reasoning Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.17419) | - |
| 2020 | `lewis2020retrieval` | Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `asai2024selfrag` | Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025subgraphrag` | Simple is Effective: The Roles of Graphs and Large Language Models in Knowledge-Graph-Based Retrieval-Augmented Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `sun2024thinkongraph` | Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `feng2024knowledgecard` | Knowledge Card: Filling LLMs' Knowledge Gaps with Plug-in Specialized Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025ruag` | RuAG: Learned-Rule-Augmented Generation for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024multimodalcot` | Multimodal Chain-of-Thought Reasoning in Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `hu2024sketchpad` | Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `qi2025cogcom` | CogCoM: A Visual Language Model with Chain-of-Manipulations Reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Reasoning: Reasoning-Process Enhancement

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `wei2022chain` | PLACEHOLDER_TITLE_FOR_wei2022chain | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2022 | `kojima2022zeroshotcot` | Large Language Models are Zero-Shot Reasoners | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yao2023tot` | Tree of Thoughts: Deliberate Problem Solving with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `besta2024got` | Graph of Thoughts: Solving Elaborate Problems with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `deepseek2025r1` | DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024cpo` | Chain of Preference Optimization: Improving Chain-of-Thought Reasoning in LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `snell2024scaling` | Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2408.03314) | - |
| 2023 | `wang2023selfconsistency` | Self-Consistency Improves Chain of Thought Reasoning in Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `madaan2023selfrefine` | Self-Refine: Iterative Refinement with Self-Feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `lightman2024lets` | Let's Verify Step by Step | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024mathshepherd` | Math-Shepherd: Verify and Reinforce LLMs Step-by-Step without Human Annotations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `luo2025wizardmath` | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Reasoning: Output-Stage Regulation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `ji2023hallucination` | Survey of Hallucination in Natural Language Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `min2023factscore` | FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `chern2023factool` | FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024factcheckgpt` | Factcheck-GPT: End-to-End Fine-Grained Document-Level Fact-Checking and Correction of LLM Output | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `manakul2023selfcheckgpt` | SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `kuhn2023semantic` | Semantic Uncertainty: Linguistic Invariances for Uncertainty Estimation in Natural Language Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `du2024haloscope` | HaloScope: Harnessing Unlabeled LLM Generations for Hallucination Detection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `bang2025hallulens` | HalluLens: LLM Hallucination Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `dhuliawala2024cove` | Chain-of-Verification Reduces Hallucination in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `gao2023rarr` | RARR: Researching and Revising What Language Models Say, Using Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chuang2024dola` | DoLa: Decoding by Contrasting Layers Improves Factuality in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shi2024cad` | Trusting Your Evidence: Hallucinate Less with Context-Aware Decoding | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `li2024iti` | Inference-Time Intervention: Eliciting Truthful Answers from a Language Model | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `sadi2025iclr` | SADI: Semantic-Aligned Dynamic Intervention for Language Model Behavior Steering | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `mcd2025neurips` | Alleviating Hallucinations in Large Language Models through Multi-Model Contrastive Decoding and Dynamic Hallucination Detection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `tian2024facttune` | Fine-tuning Language Models for Factuality | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024rtuning` | R-Tuning: Instructing Large Language Models to Say ``I Don't Know'' | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wu2025calibratedrl` | Mitigating LLM Hallucination via Behaviorally Calibrated Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.19920) | - |
| 2024 | `gou2024critic` | CRITIC: Large language models can self-correct with tool-interactive critiquing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zweiger2025seal` | Self-adapting language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.10943) | - |
| 2023 | `suris2023vipergpt` | ViperGPT: Visual inference via Python execution for reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `sarthi2024raptor` | RAPTOR: Recursive abstractive processing for tree-organized retrieval | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `asai2024selfrag` | Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `liu2023llava` | Visual instruction tuning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `li2024topviewrs` | TopViewRS: Vision--language models as top-view spatial reasoners | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shao2024viscot` | Visual CoT: Advancing multi-modal language models with a comprehensive dataset and benchmark for chain-of-thought reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `gutierrez2025hipporag2` | HippoRAG 2: From RAG to memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ong2025theanine` | Do LLM agents have regret? A case study in online learning and games | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2406.10996) | - |
| 2025 | `li2025subgraphrag` | Simple is Effective: The Roles of Graphs and Large Language Models in Knowledge-Graph-Based Retrieval-Augmented Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023selfconsistency` | Self-Consistency Improves Chain of Thought Reasoning in Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhou2024lats` | Language agent tree search unifies reasoning, acting, and planning in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `li2024chainofcode` | Chain of code: Reasoning with a language model-augmented code emulator | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2312.04474) | - |
| 2024 | `du2024anytool` | AnyTool: Self-reflective, hierarchical agents for large-scale API calls | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `li2024rain` | RAIN: Your language models can align themselves without finetuning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024mathshepherd` | Math-Shepherd: Verify and Reinforce LLMs Step-by-Step without Human Annotations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024cpo` | Chain of Preference Optimization: Improving Chain-of-Thought Reasoning in LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `qi2025rstar` | Mutual reasoning makes smaller LLMs stronger problem-solvers | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `guan2025rstarmath` | rStar-Math: Small LLMs can master math reasoning with self-evolved deep thinking | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `snell2025tts` | Scaling LLM test-time compute optimally can be more effective than scaling model parameters | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yang2025tops` | Towards thinking-optimal scaling of test-time compute for LLM reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.18080) | - |
| 2025 | `setlur2025rewarding` | Rewarding progress: Scaling automated process verifiers for LLM reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `luo2025wizardmath` | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024-06 | `farquhar2024semantic` | Detecting hallucinations in large language models using semantic entropy | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `cao2023l2r` | Learn to refuse: Making large language models more controllable and reliable through knowledge scope limitation and refusal mechanism | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2311.01041) | - |
| 2025 | `grand2025smc` | Syntactic and semantic control of large language models via sequential Monte Carlo | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.13139) | - |

#### Memory: Formation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `zhang2024memorymechanism` | A Survey on the Memory Mechanism of Large Language Model based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wu2025humantoai` | From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.15965) | - |
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `packer2024memgpt` | MemGPT: Towards LLMs as Operating Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) | - |
| 2023 | `lu2023memochat` | MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.08239) | - |
| 2025 | `wang2025recursum` | Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chhikara2025mem0` | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.19413) | - |
| 2025 | `pan2025secom` | SeCom: On Memory Construction and Retrieval for Personalized Conversational Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `patel2025engram` | ENGRAM: Effective, Lightweight Memory Orchestration for Conversational Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.12960) | - |
| 2024 | `sumers2024cognitive` | Cognitive Architectures for Language Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Memory: Maintenance

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `rasmussen2025zep` | Zep: A Temporal Knowledge Graph Architecture for Agent Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.13956) | - |
| 2024 | `gutierrez2024hipporag` | HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kang2024emg` | Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `aadhithya2025memtree` | From Isolated Conversations to Hierarchical Schemas: Dynamic Tree Memory Representation for LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `xu2025amem` | A-MEM: Agentic Memory for LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhong2024memorybank` | MemoryBank: Enhancing Large Language Models with Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `pneg2025timeline` | Towards Lifelong Dialogue Agents via Timeline-Based Memory Management | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chhikara2025mem0` | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.19413) | - |
| 2025 | `chen2025comedy` | Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `gao2025memos` | MemOS: An Operating System for Memory-Augmented Generation in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `yan2026memrl` | MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.03192) | - |
| 2024 | `packer2024memgpt` | MemGPT: Towards LLMs as Operating Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) | - |

#### Memory: Retrieval and Utilization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `chhikara2025mem0` | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.19413) | - |
| 2024 | `zhong2024memorybank` | MemoryBank: Enhancing Large Language Models with Long-Term Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `packer2024memgpt` | MemGPT: Towards LLMs as Operating Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.08560) | - |
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `patel2025engram` | ENGRAM: Effective, Lightweight Memory Orchestration for Conversational Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.12960) | - |
| 2025 | `rasmussen2025zep` | Zep: A Temporal Knowledge Graph Architecture for Agent Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.13956) | - |
| 2026 | `yan2026memrl` | MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.03192) | - |
| 2025 | `agashe2025agents` | Agent S: An Open Agentic Framework that Uses Computers Like a Human | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.08164) | - |
| 2024 | `wang2023voyager` | Voyager: An Open-Ended Embodied Agent with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `lu2023memochat` | MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.08239) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `gutierrez2024hipporag` | HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kang2024emg` | Crafting Personalized Agents through Retrieval-Augmented Generation on Editable Memory Graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `pan2025secom` | SeCom: On Memory Construction and Retrieval for Personalized Conversational Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `aadhithya2025memtree` | From Isolated Conversations to Hierarchical Schemas: Dynamic Tree Memory Representation for LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `xu2025amem` | A-MEM: Agentic Memory for LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025recursum` | Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chen2025comedy` | Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `gao2025memos` | MemOS: An Operating System for Memory-Augmented Generation in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Planning: Decomposition-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `wei2025plangenllms` | PlanGenLLMs: A modern survey of LLM planning capabilities | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `xie2024travelplanner` | TravelPlanner: A Benchmark for Real-World Planning with Language Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `zhou2023leasttomost` | Least-to-Most Prompting Enables Complex Reasoning in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023planandsolve` | Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shen2023hugginggpt` | HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kim2024llmcompiler` | An LLM Compiler for Parallel Function Calling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `song2023llmplanner` | LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `liu2023llmp` | LLM+P: Empowering Large Language Models with Optimal Planning Proficiency | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2304.11477) | - |
| 2025 | `zheng2025planninganything` | Planning Anything with Rigor: General-Purpose Zero-Shot Planning with LLM-based Formalized Programming | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `ning2024skeleton` | Skeleton-of-Thought: Prompting LLMs for Efficient Parallel Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `erdogan2025planandact` | Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.09572) | - |
| 2023 | `yao2023react` | ReAct: Synergizing reasoning and acting in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shinn2023reflexion` | Reflexion: Language agents with verbal reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `prasad2024adapt` | ADaPT: As-Needed Decomposition and Planning with Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yang2025selfgoal` | SelfGoal: Your Language Agents Already Know How to Achieve High-Level Goals | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2023voyager` | Voyager: An Open-Ended Embodied Agent with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024codeact` | Executable Code Actions Elicit Better LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023deps` | Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhu2024knowagent` | KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.03101) | - |

#### Planning: Search-Based

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `yao2024tot` | Tree of Thoughts: Deliberate Problem Solving with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhou2024lats` | Language agent tree search unifies reasoning, acting, and planning in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `zhao2023llmmcts` | Large Language Models as Commonsense Knowledge for Large-Scale Task Planning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024promptagent` | PromptAgent: Strategic Planning with Language Models Enables Expert-Level Prompt Optimization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `hao2023rap` | Reasoning with Language Model is Planning with World Model | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.14992) | - |
| 2024 | `zhang2024restmcts` | REST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025aflow` | Aflow: Automating agentic workflow generation, 2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhuang2024toolchain` | ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025diffusearch` | Implicit Search via Discrete Diffusion: A Study on Chess | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `huang2024understanding` | Understanding the Planning of LLM Agents: A Survey | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.02716) | - |
| 2024 | `lee2024planrag` | PlanRAG: A Plan-then-Retrieval Augmented Generation for Generative Large Language Models as Decision Makers | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2406.12430) | - |
| 2025 | `agashe2025agents` | Agent S: An Open Agentic Framework that Uses Computers Like a Human | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.08164) | - |
| 2023 | `zhou2023leasttomost` | Least-to-Most Prompting Enables Complex Reasoning in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023planandsolve` | Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `shen2023hugginggpt` | HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `song2023llmplanner` | LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `liu2023llmp` | LLM+P: Empowering Large Language Models with Optimal Planning Proficiency | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2304.11477) | - |
| 2023 | `yao2023react` | ReAct: Synergizing reasoning and acting in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023deps` | Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kim2024llmcompiler` | An LLM Compiler for Parallel Function Calling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `ning2024skeleton` | Skeleton-of-Thought: Prompting LLMs for Efficient Parallel Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2023voyager` | Voyager: An Open-Ended Embodied Agent with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `prasad2024adapt` | ADaPT: As-Needed Decomposition and Planning with Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024codeact` | Executable Code Actions Elicit Better LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhu2024knowagent` | KnowAgent: Knowledge-Augmented Planning for LLM-Based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.03101) | - |
| 2025 | `zheng2025planninganything` | Planning Anything with Rigor: General-Purpose Zero-Shot Planning with LLM-based Formalized Programming | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `erdogan2025planandact` | Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.09572) | - |
| 2025 | `yang2025selfgoal` | SelfGoal: Your Language Agents Already Know How to Achieve High-Level Goals | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Capability Acquisition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `wang2024codeact` | Executable Code Actions Elicit Better LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `schick2023toolformer` | Toolformer: Language Models Can Teach Themselves to Use Tools | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `qin2024toolllm` | ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `liu2024apigen` | APIGen: Automated Pipeline for Generating Verifiable and Diverse Function-Calling Datasets | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yang2023gpt4tools` | GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `liu2025toolace` | ToolACE: Winning the Points of LLM Function Calling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wu2024toolplanner` | ToolPlanner: A Tool Augmented LLM for Multi Granularity Instructions with Path Planning and Feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `qi2025webrl` | WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `patil2024gorilla` | Gorilla: Large Language Model Connected with Massive APIs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `hao2023toolkengpt` | ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yuan2025easytool` | EasyTool: Enhancing LLM-based Agents with Concise Tool Instruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `anthropic2024mcp` | Model Context Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://modelcontextprotocol.io) | - |

#### Tool Use: Invocation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `openai2023functioncalling` | Function Calling and Other API Updates | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://openai.com/index/function-calling-and-other-api-updates/) | - |
| 2025 | `patil2025bfcl` | The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `schick2023toolformer` | Toolformer: Language Models Can Teach Themselves to Use Tools | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `patil2024gorilla` | Gorilla: Large Language Model Connected with Massive APIs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `gou2024critic` | CRITIC: Large language models can self-correct with tool-interactive critiquing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `du2024anytool` | AnyTool: Self-reflective, hierarchical agents for large-scale API calls | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yao2023react` | ReAct: Synergizing reasoning and acting in language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kim2024llmcompiler` | An LLM Compiler for Parallel Function Calling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `fan2025workflowllm` | WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhuge2024gptswarm` | Gptswarm: Language agents as optimizable graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025aflow` | Aflow: Automating agentic workflow generation, 2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Tool Use: Generalization

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `liu2025gentool` | GenTool: Enhancing Tool Generalization in Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `mekala2024toolverifier` | TOOLVERIFIER: Generalization to New Tools via Self-Verification | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `patil2024gorilla` | Gorilla: Large Language Model Connected with Massive APIs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `qin2024toolllm` | ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024reinvoke` | Re-Invoke: Tool Invocation Rewriting for Zero-Shot Tool Retrieval | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `shi2025toolret` | Retrieval Models Aren't Tool-Savvy: Benchmarking Tool Retrieval for Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `huang2024metatool` | MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.03128) | - |
| 2025 | `shi2025skillweaver` | SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.07079) | - |
| 2025 | `wang2025sage` | Reinforcement Learning for Self-Improving Agent with Skill Library | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.17102) | - |
| 2023 | `schick2023toolformer` | Toolformer: Language Models Can Teach Themselves to Use Tools | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `hao2023toolkengpt` | ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `yang2023gpt4tools` | GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `gou2024critic` | CRITIC: Large language models can self-correct with tool-interactive critiquing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `du2024anytool` | AnyTool: Self-reflective, hierarchical agents for large-scale API calls | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `liu2024apigen` | APIGen: Automated Pipeline for Generating Verifiable and Diverse Function-Calling Datasets | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wu2024toolplanner` | ToolPlanner: A Tool Augmented LLM for Multi Granularity Instructions with Path Planning and Feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `liu2025toolace` | ToolACE: Winning the Points of LLM Function Calling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yuan2025easytool` | EasyTool: Enhancing LLM-based Agents with Concise Tool Instruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `qi2025webrl` | WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `fan2025workflowllm` | WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `patil2025bfcl` | The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent Collaboration

#### Role

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `liu2025advances` | Advances and challenges in foundation agents: From brain-inspired intelligence to evolutionary, collaborative, and safe systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.01990) | - |
| 2024 | `li2024survey` | A survey on LLM-based multi-agent systems: workflow, infrastructure, and challenges | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `long2025role` | Role play: Learning adaptive role-specific strategies in multi-agent interactions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `dong2024villageragent` | Villageragent: A graph-based multi-agent framework for coordinating complex task dependencies in minecraft | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chan2024chateval` | ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `he2025selfcorrect` | SelfCorrect-Agent: Toward robust and generalizable LLM-based agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhong2024heterogeneous` | Heterogeneous-agent reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ye2025x` | X-mas: Towards building multi-agent systems with heterogeneous llms | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.16997) | - |
| 2025 | `guo2025heterogeneous` | Heterogeneous multi-agent reinforcement learning for zero-shot scalable collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `li2023camel` | Camel: Communicative agents for" mind" exploration of large language model society | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `yao2026hieramas` | HieraMAS: Optimizing Intra-Node LLM Mixtures and Inter-Node Topology for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.20229) | - |
| 2025 | `zhou2025adaptive` | Adaptive heterogeneous multi-agent debate for enhanced educational and factual reasoning in large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `park2025maporl` | MAPoRL: Multi-agent post-co-training for collaborative large language models with reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `vaccaro2025multi` | Multi-Agentic LLMs for personalizing STEM texts | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `kim2024mdagents` | Mdagents: An adaptive collaboration of llms for medical decision-making | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `nguyen2026automated` | Automated summarization of software documents: an LLM-based multi-agent approach | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025optdispro` | OptDisPro: LLM-based Multi-agent Framework for Flexibly Adapting Heuristic Optimal DisFlow | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `barbosa2024collaborative` | Collaborative problem-solving with LLM: a multi-agent system approach to solve complex tasks using autogen | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2011 | `campbell2011multi` | Multi-agent role allocation: issues, approaches, and multiple perspectives | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `amayuelas2025self` | Self-resource allocation in multi-agent llm systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.02051) | - |
| 2025 | `borghoff2025organizational` | An organizational theory for multi-agent interactions integrating human agents, LLMs, and specialized AI | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `youwai2026large` | Large language model-based multi-agent systems for automated foundation design: router-driven task classification and expert selection framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yue2025masrouter` | Masrouter: Learning to route llms for multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `tarasova2025decentralized` | Decentralized adaptive task allocation for dynamic multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `goel2025r3dm` | R3DM: Enabling Role Discovery and Diversity Through Dynamics Models in Multi-agent Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `qian2024chatdev` | ChatDev: Communicative agents for software development | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `fei2026codedelegator` | CodeDelegator: Mitigating Context Pollution via Role Separation in Code-as-Action Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.14914) | - |
| 2026 | `zhu2026atomizer` | Atomizer: An LLM-based Collaborative Multi-Agent Framework for Intent-Driven Commit Untangling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.01233) | - |
| 2024 | `chen2024sheetagent` | Sheetagent: A generalist agent for spreadsheet reasoning and manipulation via large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `jin2024mare` | Mare: Multi-agents collaboration framework for requirements engineering | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.03256) | - |
| 2025 | `yao2025comal` | Comal: Collaborative multi-agent large language models for mixed-autonomy traffic | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025colacare` | Colacare: Enhancing electronic health record modeling through large language model-driven multi-agent collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wei2024medco` | Medco: Medical education copilots based on a multi-agent framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `jinxin2023cgmi` | Cgmi: Configurable general multi-agent interaction framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.12503) | - |
| 2025 | `xu2025multiagentesc` | Multiagentesc: A llm-based multi-agent collaboration framework for emotional support conversation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024autoagents` | AutoAgents: a framework for automatic agent generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yang2025medaide` | MedAide: information fusion and anatomy of medical intents via LLM-based agent collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `li2024agent` | Agent hospital: A simulacrum of hospital with evolvable medical agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.02957) | - |
| 2024 | `chen2024agentverse` | Agentverse: Facilitating multi-agent collaboration and exploring emergent behaviors | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `perera2025auto` | Auto-scaling LLM-based multi-agent systems through dynamic integration of agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2020 | `wang2020roma` | ROMA: multi-agent reinforcement learning with emergent roles | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2017 | `lowe2017multi` | Multi-agent actor-critic for mixed cooperative-competitive environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2017 | `sunehag2017value` | Value-decomposition networks for cooperative multi-agent learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/1706.05296) | - |
| 2020 | `rashid2020monotonic` | Monotonic value function factorisation for deep multi-agent reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `zhou2026resmas` | ResMAS: Resilience Optimization in LLM-based Multi-agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.04694) | - |
| 2025 | `tu2025adaptive` | Adaptive Role Learning with Evolutionary Multi-agent Reinforcement Learning for UAV-Vehicle Collaboration in Sparse Mobile Crowdsensing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Communication

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `guo2024large` | Large language model based multi-agents: a survey of progress and challenges | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `yan2025beyond` | Beyond self-talk: A communication-centric survey of llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.14321) | - |
| 2023 | `hong2023metagpt` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025talk` | Talk structurally, act hierarchically: A collaborative framework for llm multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.11098) | - |
| 2024 | `tao2024magis` | Magis: Llm-based multi-agent framework for github issue resolution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ma2025autodata` | AutoData: A Multi-Agent System for Open Web Data Collection | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `mou2025ecolang` | EcoLANG: Efficient and Effective Agent Communication Language Induction for Social Simulation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025megaagent` | MegaAgent: A large-scale autonomous LLM-based multi-agent system without predefined SOPs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025cut` | Cut the Crap: An Economical Communication Pipeline for LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `fan2026todycomm` | TodyComm: Task-Oriented Dynamic Communication for Multi-Round LLM-based Multi-Agent System | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.03688) | - |
| 2023 | `nascimento2023self` | Self-adaptive large language model (llm)-based multiagent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024reconcile` | Reconcile: Round-table conference improves reasoning via consensus among diverse llms | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `yang2026dynamic` | Dynamic Consensus Communication Mechanism for Large Language Model-Based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `pan2025agentcoord` | Agentcoord: Visually exploring coordination strategy for llm-based multi-agent collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhu2024survey` | A survey of multi-agent deep reinforcement learning with communication | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2022 | `shaw2022formic` | Formic: Foraging via multiagent rl with implicit communication | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `buscemi2026numbers` | When Numbers Start Talking: Implicit Numerical Coordination Among LLM-Based Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.03846) | - |
| 2022 | `wang2022tomc` | ToM2C: Target-oriented Multi-agent Communication and Cooperation with Theory of Mind | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ge2025efficient` | Efficient training in multi-agent reinforcement learning: A communication-free framework for the box-pushing problem | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zou2025latent` | Latent collaboration in multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.20639) | - |
| 2002 | `hunt2002tcp` | TCP/IP network administration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2014 | `denardis2014global` | The global war for internet governance | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2002 | `gourley2002http` | HTTP: the definitive guide | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2011 | `campbell2011multi` | Multi-agent role allocation: issues, approaches, and multiple perspectives | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2022 | `chen2022unmanned` | From unmanned systems to autonomous intelligent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `stefan2025interconnected` | Interconnected Autonomous Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `tang2026llm` | LLM-Based Agentic Systems for Software Engineering: Challenges and Opportunities | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.09822) | - |
| 2024 | `yang2024llm` | Llm-based multi-agent systems: Techniques and business perspectives | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2411.14033) | - |
| 2025 | `chen2025internet` | Internet of Agents: Weaving a Web of Heterogeneous Agents for Collaborative Intelligence | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `kwon2025cp` | Cp-agentnet: Autonomous and explainable communication protocol design using generative agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ehtesham2025survey` | A survey of agent interoperability protocols: Model context protocol (mcp), agent communication protocol (acp), agent-to-agent protocol (a2a), and agent network protocol (anp) | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.02279) | - |
| 2024 | `marro2024scalable` | A scalable communication protocol for networks of large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.11905) | - |
| 2024 | `anthropic2024context` | Model Context Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://www.anthropic.com/news/model-contextprotocol) | - |
| 2024 | `chang2024anp` | ANP: Agent Network Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://www.agent-networkprotocol.com/) | - |
| 2025 | `eclipse2025lmos` | Language Model Operating System (LMOS) | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://eclipse.dev/lmos/) | - |
| 2025 | `linux2025acp` | ACP: Agent Communication Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://agentcommunicationprotocol.dev/introduction/welcome) | - |
| 2025 | `google2025a2a` | A2A: Agent2Agent Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://github.com/google/A2A) | [![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/google/A2A) |
| 2025 | `alengineer2025protocol` | Agent Protocol | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://agentprotocol.ai/) | - |

#### Orchestration

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `yue2025masrouter` | Masrouter: Learning to route llms for multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `liu2025rcr` | Rcr-router: Efficient role-aware context routing for multi-agent llm systems with structured memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.04903) | - |
| 2026 | `zhao2026tcandon` | TCAndon-Router: Adaptive Reasoning Router for Multi-Agent Collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.04544) | - |
| 2025 | `yang2025agentnet` | Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems, 2025 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `zhang2026stackplanner` | StackPlanner: A Centralized Hierarchical Multi-Agent System with Task-Experience Memory Management | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.05890) | - |
| 2025 | `li2025agent` | Agent-Oriented Planning in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `dang2025multi` | Multi-agent collaboration via evolving orchestration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.19591) | - |
| 2024 | `aso2024efficient` | An Efficient Approach for Cooperative Multi-Agent Learning Problems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `jin2025controlling` | Controlling Performance and Budget of a Centralized Multi-agent LLM System with Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.02755) | - |
| 2025 | `de2025centrally` | Centrally coordinated multi-agent reinforcement learning for power grid topology control | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025symphony` | Symphony: A Decentralized Multi-Agent Framework for Scalable Collective Intelligence | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.20019) | - |
| 2026 | `liu2026learning` | Learning Decentralized LLM Collaboration with Multi-Agent Actor Critic | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.21972) | - |
| TBD | `yang2025llm` | LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ratnabala2025hippo` | Hippo-mat: Decentralized task allocation using graphsage and multi-agent deep reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.07662) | - |
| 2025 | `chen2025agentflow` | Agentflow: Resilient adaptive cloud-edge framework for multi-agent coordination | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.07603) | - |
| 2024 | `qian2024chatdev` | ChatDev: Communicative agents for software development | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `hong2023metagpt` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025agentorchestra` | Agentorchestra: A hierarchical multi-agent framework for general-purpose task solving | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `wang2023plan` | Plan-and-solve prompting: Improving zero-shot chain-of-thought reasoning by large language models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `yu2025tree` | Tree of Agents: Improving Long-Context Capabilities of Large Language Models through Multi-Perspective Reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `yun2026graph` | Graph-of-Agents: A Graph-based Framework for Multi-Agent LLM Collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `yu2026adaptorch` | AdaptOrch: Task-Adaptive Multi-Agent Orchestration in the Era of LLM Performance Convergence | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.16873) | - |

#### Interaction

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `shen2023hugginggpt` | HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `gu2025explain` | Explain-analyze-generate: A sequential multi-agent collaboration method for complex reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024chain` | Chain of agents: Large language models collaborating on long-context tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025anymac` | Anymac: Cascading flexible multi-agent collaboration via next-agent prediction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024macrec` | Macrec: A multi-agent collaboration framework for recommendation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `xu2024magic` | Magic: Investigation of large language model powered multi-agent in cognition, adaptability, rationality and collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `barrak2025traceability` | Traceability and Accountability in Role-Specialized Multi-Agent LLM Pipelines | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `wang2023self` | PLACEHOLDER_TITLE_FOR_wang2023self | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `du2024improving` | Improving factuality and reasoning in language models through multiagent debate | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `wang2025mixture` | Mixture-of-Agents Enhances Large Language Model Capabilities | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025optimizing` | Optimizing sequential multi-step tasks with parallel llm agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.08944) | - |
| 2025 | `li2025parallelized` | Parallelized planning-acting for efficient LLM-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.03505) | - |
| 2025 | `gu2025agentgroupchat` | Agentgroupchat-v2: Divide-and-conquer is what llm-based multi-agent system need | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.15451) | - |
| 2025 | `yu2025dyntaskmas` | Dyntaskmas: A dynamic task graph-driven framework for asynchronous and parallel llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `hong2023metagpt` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `liu2024drugagent` | DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `Zhang2024ProAgent` | ProAgent: Building Proactive Cooperative Agents with Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024exploring` | Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025cooperative` | Cooperative Multi-Agent Planning with Adaptive Skill Synthesis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.10148) | - |
| 2024 | `bo2024Reflective` | Reflective Multi-Agent Collaboration based on Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhao2024electoral` | An Electoral Approach to Diversify LLM-based Multi-Agent Collective Decision-Making | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `zhang2024beat` | Can LLMs Beat Humans in Debating? A Dynamic Multi-agent Framework for Competitive Debate | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2408.04472) | - |
| 2023 | `fu2023improving` | Improving language model negotiation with self-play and in-context learning from ai feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.10142) | - |
| 2025 | `mao2025alympics` | ALYMPICS: LLM Agents Meet Game Theory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Cai2025RTBAgent` | RTBAgent: A LLM-based Agent System for Real-Time Bidding | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `liang2024encouraging` | Encouraging divergent thinking in large language models through multi-agent debate | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `ye2025multiagentkto` | Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.14225) | - |
| 2026 | `zhu2026align` | ALIGN: Aligned Delegation with Performance Guarantees for Multi-Agent LLM Reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.00127) | - |

#### Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `lee2025gemmas` | Gemmas: Graph-based evaluation metrics for multi agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `gioacchini2024agentquest` | Agentquest: A modular benchmark framework to measure progress and improve llm agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `agashe2025llm` | LLM-Coordination: Evaluating and Analyzing Multi-agent Coordination Abilities in Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024llmarena` | LLMArena: Assessing Capabilities of Large Language Models in Dynamic Multi-Agent Environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024battleagentbench` | BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2408.15971) | - |
| 2025 | `zhu2025multiagentbench` | MultiAgentBench : Evaluating the Collaboration and Competition of LLM agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `schmidgall2025agentclinic` | AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.07960) | - |
| 2025 | `fan2025aihospital` | AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shu2024towards` | Towards effective genai multi-agent collaboration: design and evaluation for enterprise applications | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.05449) | - |
| 2025 | `geng2025realm` | Realm-bench: A real-world planning benchmark for llms and multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.18836) | - |

#### Discussion

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023 | `park2023generative` | Generative agents: Interactive simulacra of human behavior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `li2023camel` | Camel: Communicative agents for" mind" exploration of large language model society | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `fu2023improving` | Improving language model negotiation with self-play and in-context learning from ai feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.10142) | - |
| 2023 | `hong2023metagpt` | MetaGPT: Meta programming for a multi-agent collaborative framework | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wu2024autogen` | AutoGen: Enabling next-gen LLM applications via multi-agent conversations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024agentverse` | Agentverse: Facilitating multi-agent collaboration and exploring emergent behaviors | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `chen2024autoagents` | AutoAgents: a framework for automatic agent generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `park2025maporl` | MAPoRL: Multi-agent post-co-training for collaborative large language models with reinforcement learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhang2025osc` | OSC: Cognitive Orchestration through Dynamic Knowledge Alignment in Multi-Agent LLM Collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `dang2025multi` | Multi-agent collaboration via evolving orchestration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.19591) | - |
| 2026 | `jafari2026lightweight` | A Lightweight Modular Framework for Constructing Autonomous Agents Driven by Large Language Models: Design, Implementation, and Applications in AgentForge | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.13383) | - |
| 2026 | `liu2026masfactory` | MASFactory: A Graph-centric Framework for Orchestrating LLM-Based Multi-Agent Systems with Vibe Graphing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.06007) | - |
| 2018 | `bechlioulis2018collaborative` | Collaborative multi-robot transportation in obstacle-cluttered environments via implicit communication | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `zhao2025udon` | UDON: Uncertainty-weighted Distributed Optimization for Multi-Robot Neural Implicit Mapping under Extreme Communication Constraints | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.12702) | - |
| 2025 | `yang2025implicit` | Implicit communication in human-robot collaborative transport | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Failure Attribution

#### Formal Definition

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `pan2025why` | Why Do Multiagent Systems Fail? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `zhang2025which` | Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `anonymous2026seeing` | Seeing the Whole Elephant: A Benchmark for Failure Attribution in LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2025 | `Zhang2025AgenTracerWI` | AgenTracer: Who Is Inducing Failure in the LLM Agentic Systems? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.03312) | - |
| 2026 | `wang2026flat` | From Flat Logs to Causal Graphs: Hierarchical Failure Attribution for LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.23701) | - |
| 2025 | `Ge2025WhoII` | Who is introducing the failure? automatically attributing failures of multi-agent systems via spectrum analysis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.13782) | - |

#### MAS Failure Category

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2025 | `pan2025why` | Why Do Multiagent Systems Fail? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `kong2025aegis` | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.14295) | - |
| 2025 | `deshpande2025trail` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2025 | `Zhu2025WhereLA` | Where LLM Agents Fail and How They can Learn From Failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025 | `lu2025exploring` | Exploring autonomous agents: A closer look at why they fail when completing tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.13143) | - |
| 2026 | `ma2026demystifying` | Demystifying the Lifecycle of Failures in Platform-Orchestrated Agentic Workflows | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2026 | `anonymous2025diagnosing` | Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Failure Attribution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `Zhang2025AgenTracerWI` | AgenTracer: Who Is Inducing Failure in the LLM Agentic Systems? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.03312) | - |
| 2026 | `wang2026flat` | From Flat Logs to Causal Graphs: Hierarchical Failure Attribution for LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.23701) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2025 | `West2025AbductAP` | Abduct, Act, Predict: Scaffolding Causal Inference for Automated Failure Attribution in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.10401) | - |
| 2025 | `zhang2025which` | Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `deshpande2025trail` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2025 | `Ge2025WhoII` | Who is introducing the failure? automatically attributing failures of multi-agent systems via spectrum analysis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.13782) | - |
| 2025 | `Yu2025CORRECTCE` | CORRECT: COndensed eRror RECognition via knowledge Transfer in multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.24088) | - |
| 2025 | `kong2025aegis` | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.14295) | - |
| 2025 | `Zhang2025GraphTracerGF` | GraphTracer: Graph-Guided Failure Tracing in LLM Agents for Robust Multi-Turn Deep Search | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.10581) | - |
| 2025 | `Shen2025MetacognitiveSF` | Metacognitive Self-Correction for Multi-Agent System via Prototype-Guided Next-Execution Reconstruction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.14319) | - |
| 2025 | `zhengtrajectory` | Trajectory Graph Copilot: Pre-Action Error Diagnosis in LLM Agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2026 | `advani2026trajectory` | Trajectory Guard--A Lightweight, Sequence-Aware Model for Real-Time Anomaly Detection in Agentic AI | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.00516) | - |
| 2026 | `sheng2026dills` | DiLLS: Interactive Diagnosis of LLM-based Multi-agent Systems via Layered Summary of Agent Behaviors | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.05446) | - |
| 2026 | `anonymous2026seeing` | Seeing the Whole Elephant: A Benchmark for Failure Attribution in LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Zhu2025WhereLA` | Where LLM Agents Fail and How They can Learn From Failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025 | `barrak2025traceability` | Traceability and Accountability in Role-Specialized Multi-Agent LLM Pipelines | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `banerjee2025` | Where Did It All Go Wrong? A Hierarchical Look into Multi-Agent Error Attribution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.04886) | - |
| 2025 | `ma2025dover` | DoVer: Intervention-Driven Auto Debugging for LLM Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.06749) | - |
| 2026 | `barke2026agentrx` | AgentRx: Diagnosing AI Agent Failures from Execution Trajectories | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.02475) | - |
| 2025 | `wang2025xagen` | XAgen: An Explainability Tool for Identifying and Correcting Failures in Multi-Agent Workflows | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.17896) | - |
| 2026 | `sun2026scope` | Scope Delineation Before Localization: A Two-Stage Framework for Enhancing Failure Attribution in Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chen2025understanding` | Understanding individual agent importance in multi-agent system via counterfactual reasoning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `epperson2025interactive` | Interactive debugging and steering of multi-agent ai systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `Ma2025AutomaticFA` | Automatic Failure Attribution and Critical Step Prediction Method for Multi-Agent Systems Based on Causal Inference | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.08682) | - |
| 2023 | `triantafyllou2023agent` | Agent-specific effects: A causal effect propagation analysis in multi-agent MDPs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2310.11334) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2026 | `ma2026demystifying` | Demystifying the Lifecycle of Failures in Platform-Orchestrated Agentic Workflows | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2024 | `triantafyllou2024counterfactual` | Counterfactual effect decomposition in multi-agent sequential decision making | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.12539) | - |
| 2026 | `anonymous2025diagnosing` | Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `zhu2026raffles` | Raffles: Reasoning-based attribution of faults for llm systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `pan2025why` | Why Do Multiagent Systems Fail? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### Failure Attribution Evaluation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025 | `zhang2025which` | Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `deshpande2025trail` | TRAIL: Trace reasoning and agentic issue localization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.08638) | - |
| 2025 | `Ma2025DiagnosingFR` | Diagnosing Failure Root Causes in Platform-Orchestrated Agentic Systems: Dataset, Taxonomy, and Benchmark | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.23735) | - |
| 2025 | `Zhu2025WhereLA` | Where LLM Agents Fail and How They can Learn From Failures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25370) | - |
| 2025 | `Lin2025AgentAskMS` | AgentAsk: Multi-Agent Systems Need to Ask | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.07593) | - |
| 2025 | `Zhang2025AgenTracerWI` | AgenTracer: Who Is Inducing Failure in the LLM Agentic Systems? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.03312) | - |
| 2025 | `Yu2025CORRECTCE` | CORRECT: COndensed eRror RECognition via knowledge Transfer in multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.24088) | - |
| 2025 | `kong2025aegis` | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.14295) | - |
| 2025 | `Zhang2025GraphTracerGF` | GraphTracer: Graph-Guided Failure Tracing in LLM Agents for Robust Multi-Turn Deep Search | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.10581) | - |
| 2026 | `anonymous2025diagnosing` | Diagnosing with Insights: Structured Analysis of Agent Failures via Behavioral Abstractions | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2026 | `in2026rethinking` | Rethinking Failure Attribution in Multi-Agent Systems: A Multi-Perspective Benchmark and Evaluation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.25001) | - |
| 2026 | `anonymous2026seeing` | Seeing the Whole Elephant: A Benchmark for Failure Attribution in LLM-based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

---

### Multi-Agent System Self-Evolution

#### Motivation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 1999 | `bonabeau1999swarm` | Swarm intelligence: from natural to artificial systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `wang2024survey` | A survey on large language model based autonomous agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `kim2025towards` | Towards a science of scaling agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.08296) | - |
| TBD | `koduriefficiency` | Efficiency-First Design for LLM-Based Multi-Agent Systems: A Framework and Empirical Analysis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### From Attribution to Evolution

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2007 | `galhardo2007mutation` | Mutation as a stress response and the regulation of evolvability | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 1989 | `goss1989self` | Self-organized shortcuts in the Argentine ant | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

#### MAS Self-Evolution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024 | `lu2024morphagent` | Morphagent: Empowering agents through self-evolving profiles and decentralized collaboration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.15048) | - |
| 2024 | `bo2024Reflective` | Reflective Multi-Agent Collaboration based on Large Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `chen2025optima` | PLACEHOLDER_TITLE_FOR_chen2025optima | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `xue2025comas` | CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08529) | - |
| 2024 | `zhuge2024gptswarm` | Gptswarm: Language agents as optimizable graphs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `mangla2025negotiationgym` | NegotiationGym: Self-Optimizing Agents in a Multi-Agent Social Simulation Environment | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.04368) | - |
| 2025 | `chen2024agentcourt` | Agentcourt: Simulating court with adversarial evolvable lawyer agents | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `guan2024richelieu` | Richelieu: Self-evolving llm-based agents for ai diplomacy | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `li2025learn` | Learn as individuals, evolve as a team: Multi-agent llms adaptation in embodied environments | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.07232) | - |
| 2025 | `wang2025annaagent` | AnnaAgent: Dynamic evolution agent system with multi-session memory for realistic seeker simulation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `chen2025multiagent` | Multi-agent evolve: Llm self-improve through co-evolution | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.23595) | - |
| 2025 | `pan2025advevo` | AdvEvo-MARL: Shaping Internalized Safety through Adversarial Co-Evolution in Multi-Agent Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01586) | - |
| 2026 | `zhou2026epistemic` | Epistemic Context Learning: Building Trust the Right Way in LLM-Based Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.21742) | - |
| 2026 | `kar2026towards` | Towards AGI A Pragmatic Approach Towards Self Evolving Agent | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.11658) | - |
| 2024 | `liu2024odyssey` | Odyssey: Empowering minecraft agents with open-world skills | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.15325) | - |
| 2025 | `li2025adaptive` | Adaptive graph pruning for multi-agent communication | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.02951) | - |
| 2024 | `zhang2024cut` | Cut the crap: An economical communication pipeline for llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.02506) | - |
| 2025 | `zhou2025multi` | Multi-agent design: Optimizing agents with better prompts and topologies | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.02533) | - |
| 2025 | `yang2025agentnet` | Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems, 2025 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2023 | `chen2023autoagents` | Autoagents: A framework for automatic agent generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.17288) | - |
| 2025 | `yuan2025evoagent` | Evoagent: Towards automatic multi-agent generation via evolutionary algorithms | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `hu2024self` | Self-evolving multi-agent collaboration networks for software development | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.16946) | - |
| 2025 | `ma2025agentic` | Agentic neural networks: Self-evolving multi-agent systems via textual backpropagation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.09046) | - |
| 2025 | `zhang2025g` | G-memory: Tracing hierarchical memory for multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.07398) | - |
| 2025 | `hu2025automated` | Automated design of agentic systems, 2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2025 | `rosser2025agentbreeder` | AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.00757) | - |
| 2025 | `zhang2025aflow` | Aflow: Automating agentic workflow generation, 2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| 2024 | `shang2024agentsquare` | Agentsquare: Automatic llm agent search in modular design space | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.06153) | - |
| 2025 | `ke2025mas` | Mas-zero: Designing multi-agent systems with zero supervision | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.14996) | - |
| 2025 | `zhang2025multi` | Multi-agent architecture search via agentic supernet | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.04180) | - |
| 2025 | `ye2025mas` | Mas-gpt: Training llms to build llm-based multi-agent systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.03686) | - |
| 2025 | `wang2025mas` | MAS $\^ 2$: Self-Generative, Self-Configuring, Self-Rectifying Multi-Agent Systems | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.24323) | - |

#### Multi-Agent Self-Evolution Taxonomy

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| TBD | `advevo2024` | PLACEHOLDER_TITLE_FOR_advevo2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `agentbreeder2024` | PLACEHOLDER_TITLE_FOR_agentbreeder2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `annaagent2024` | PLACEHOLDER_TITLE_FOR_annaagent2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `reflective2024` | PLACEHOLDER_TITLE_FOR_reflective2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `scoreflow2024` | PLACEHOLDER_TITLE_FOR_scoreflow2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `maporl2024` | PLACEHOLDER_TITLE_FOR_maporl2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `ann2024` | PLACEHOLDER_TITLE_FOR_ann2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `evomac2024` | PLACEHOLDER_TITLE_FOR_evomac2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `agp2024` | PLACEHOLDER_TITLE_FOR_agp2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `topoweaver2024` | PLACEHOLDER_TITLE_FOR_topoweaver2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `cutthecrap2024` | PLACEHOLDER_TITLE_FOR_cutthecrap2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `gdesigner2024` | PLACEHOLDER_TITLE_FOR_gdesigner2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `gmemory2024` | PLACEHOLDER_TITLE_FOR_gmemory2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `agentnet2024` | PLACEHOLDER_TITLE_FOR_agentnet2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `gptswarm2024` | PLACEHOLDER_TITLE_FOR_gptswarm2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `adas2024` | PLACEHOLDER_TITLE_FOR_adas2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `maas2024` | PLACEHOLDER_TITLE_FOR_maas2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `maszero2024` | PLACEHOLDER_TITLE_FOR_maszero2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `aflow2024` | PLACEHOLDER_TITLE_FOR_aflow2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `autoflow2024` | PLACEHOLDER_TITLE_FOR_autoflow2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `debflow2024` | PLACEHOLDER_TITLE_FOR_debflow2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `epc2024` | PLACEHOLDER_TITLE_FOR_epc2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `evoagent2024` | PLACEHOLDER_TITLE_FOR_evoagent2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `autoagents2024` | PLACEHOLDER_TITLE_FOR_autoagents2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `flowreasoner2024` | PLACEHOLDER_TITLE_FOR_flowreasoner2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `masgpt2024` | PLACEHOLDER_TITLE_FOR_masgpt2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |
| TBD | `mass2024` | PLACEHOLDER_TITLE_FOR_mass2024 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/PLACEHOLDER_PAPER_TBD) | - |

## Acknowledgment

This survey is extended and refined from the original **Awesome RL for LRMs** repo. We are deeply grateful to all contributors for their efforts, and we sincerely thank for their all interest in **Awesome RL for LRMs**. The contents of the previous repository are available [here](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mira-ai-lab/Awesome_MAS_Evolution&type=Date)](https://www.star-history.com/#mira-ai-lab/Awesome_MAS_Evolution&Date)
