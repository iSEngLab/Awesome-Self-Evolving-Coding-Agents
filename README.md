# Self-Evolving Coding Agents

## 📖 Introduction

<p align="center">
  <img src="assets/self-evolving-code-agent.png" alt="Overview of self-evolving coding agents" width="100%">
</p>
<p align="center"><em>Overview of self-evolving coding agents.</em></p>

Coding agents increasingly improve persistent components of their own software-engineering loop by learning from execution outcomes, trajectories, accumulated experience, and environmental feedback. This repository accompanies our survey and curates its paper corpus, related methods, benchmarks, products, and background resources. The six target categories and their terminology follow the paper taxonomy.

## 🎯 Scope

This repository covers six groups of resources:

1. **Core Self-Evolving Coding Agents**: curated systems organized by evolving target: agent framework, memory, skill/tool, model, workflow/topology, and environment/context.

2. **General Self-Evolution Methods in Coding Settings**: General agent self-evolution methods whose improvements are evaluated on code generation, program execution, or software engineering tasks.

3. **Benchmarks and Environments**: Code-generation benchmarks, real-world software engineering tasks, data resources, and executable environments used to build, train, and evaluate coding agents.

4. **Products**: deployed coding products with persistent adaptation mechanisms, mapped to the same target vocabulary.

5. **Background**: foundational work on code generation, repository-level software engineering, and multi-agent coding.

6. **Related Surveys**: surveys covering self-evolving agents, coding agents, and their intersection.

## 📚 Contents

- [Introduction](#introduction)
- [Scope](#scope)
- [1. Core Self-Evolving Coding Agents](#1-core-self-evolving-coding-agents)
  - [1.1 Agent Framework Self-Evolution](#11-agent-framework-self-evolution)
  - [1.2 Memory Self-Evolution](#12-memory-self-evolution)
  - [1.3 Skill and Tool Self-Evolution](#13-skill-and-tool-self-evolution)
  - [1.4 Model Self-Evolution](#14-model-self-evolution)
  - [1.5 Workflow and Topology Self-Evolution](#15-workflow-and-topology-self-evolution)
  - [1.6 Environment and Context Self-Evolution](#16-environment-and-context-self-evolution)
- [2. General Self-Evolution Methods in Coding Settings](#2-general-self-evolution-methods-in-coding-settings)
  - [2.1 Feedback Optimization](#21-feedback-optimization)
  - [2.2 Experience-Based Learning](#22-experience-based-learning)
  - [2.3 Skill Learning](#23-skill-learning)
  - [2.4 Self-Generated Training](#24-self-generated-training)
  - [2.5 System Optimization](#25-system-optimization)
  - [2.6 Collective Evolution](#26-collective-evolution)
- [3. Benchmarks and Environments](#3-benchmarks-and-environments)
  - [3.1 Repository-Level Software Engineering Benchmarks](#31-repository-level-software-engineering-benchmarks)
  - [3.2 General Coding Benchmarks](#32-general-coding-benchmarks)
  - [3.3 Training and Evaluation Infrastructure](#33-training-and-evaluation-infrastructure)
- [4. Self-Evolving Coding Products](#4-self-evolving-coding-products)
- [5. Background](#5-background)
  - [5.1 General Coding Agents](#51-general-coding-agents)
  - [5.2 Repository-Level Software Engineering Agents](#52-repository-level-software-engineering-agents)
  - [5.3 Multi-Agent Coding](#53-multi-agent-coding)
- [6. Related Surveys](#6-related-surveys)
  - [6.1 Surveys on Self-Evolving Agents](#61-surveys-on-self-evolving-agents)
  - [6.2 Surveys on Coding Agents](#62-surveys-on-coding-agents)

## 1. Core Self-Evolving Coding Agents

### 1.1 Agent Framework Self-Evolution

1. [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents (DGM)](https://arxiv.org/abs/2505.22954) `[2026-ICLR]`
2. [Mendel Gödel Machine: Comparative Evolution Enables State-of-the-Art Self-Improving Coding Agents (Mendel GM)](https://openreview.net/forum?id=EJ7gBBDvCg) `[2026-OpenReview]`
3. [Huxley Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine (Huxley GM)](https://arxiv.org/abs/2510.21614) `[2026-ICLR]`
4. [A Self-Improving Coding Agent (SICA)](https://arxiv.org/abs/2504.15228) `[2025-ICLR]`
5. [Self-Improvement via Fast Tree-Search (SIFT)](https://openreview.net/forum?id=wZMNXHPYcO) `[2026-ICLR]`
6. [Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation](https://arxiv.org/abs/2310.02304) `[2024-COLM]`
7. [Agentic Harness Engineering: Observability-Driven Automatic Evolution of Coding-Agent Harnesses (AHE)](https://arxiv.org/abs/2604.25850) `[2026-arXiv]`
8. [From Failed Trajectories to Reliable LLM Agents: Diagnosing and Repairing Harness Flaws (HarnessFix)](https://arxiv.org/abs/2606.06324) `[2026-arXiv]`
9. [TTHE: Test-Time Harness Evolution](https://arxiv.org/abs/2607.08124) `[2026-arXiv]`
10. [HarnessCompass: Guiding Automatic Harness Evolution toward Generalizable and Effective Agent Harnesses](https://arxiv.org/abs/2608.01918) `[2026-arXiv]`
11. [Evo-Harness: Context-to-Harness Skill Compilation for Self-Evolving Agents](https://arxiv.org/abs/2608.15071) `[2026-arXiv]`
12. [EvolveNet: Collaborative Harness Evolution for Agent Self-Improvement](https://arxiv.org/abs/2608.04968) `[2026-arXiv]`
13. [Confucius Code Agent: Scalable Agent Scaffolding for Real-World Codebases (CCA)](https://arxiv.org/abs/2512.10398) `[2025-arXiv]`
14. [Argus: A General-Purpose Agentic Reasoning Runtime for Long-Horizon Tasks](https://arxiv.org/abs/2608.05144) `[2026-arXiv]`
15. [Self-Evolving Agents with Anytime-Valid Certificates (SEA)](https://arxiv.org/abs/2607.00871) `[2026-arXiv]`
16. [One Recipe, Many Harnesses: What Self-Evolution Encodes Across Languages and Models](https://arxiv.org/abs/2608.10178) `[2026-arXiv]`
17. [Rethinking the Evaluation of Harness Evolution for Agents](https://arxiv.org/abs/2607.12227) `[2026-arXiv]`
18. [HELIX: Model-Harness Co-evolution for Recursive Self-Improvement](https://arxiv.org/abs/2608.13951) `[2026-arXiv]`
19. [Ouroboros: A Self-Developing Frontier Coding Agent with Reviewed Core Evolution](https://arxiv.org/abs/2608.08311) `[2026-arXiv]`
20. [Group-Evolving Agents: Open-Ended Self-Improvement via Experience Sharing (GEA)](https://arxiv.org/abs/2602.04837) `[2026-arXiv]`
21. [HarnessBank: Semantic Gene-Bank Search with Gated Verification for Agent-Harness Self-Evolution](https://arxiv.org/abs/2607.13683) `[2026-arXiv]`
22. [DarwinX: Evolving Agent Harnesses Through Natural Selection](https://arxiv.org/abs/2608.07545) `[2026-arXiv]`
23. [Adapting the Interface, Not the Model: Runtime Harness Adaptation for Deterministic LLM Agents (Life-Harness)](https://arxiv.org/abs/2605.22166) `[2026-arXiv]`
24. [Self-Harness: Harnesses That Improve Themselves](https://arxiv.org/abs/2606.09498) `[2026-arXiv]`
25. [Meta-Harness: End-to-End Optimization of Model Harnesses](https://arxiv.org/abs/2603.28052) `[2026-arXiv]`
26. [Harness Updating Is Not Harness Benefit: Disentangling Evolution Capabilities in Self-Evolving LLM Agents](https://arxiv.org/abs/2605.30621) `[2026-arXiv]`
27. [HarnessX: A Composable, Adaptive, and Evolvable Agent Harness Foundry](https://arxiv.org/abs/2606.14249) `[2026-arXiv]`

### 1.2 Memory Self-Evolution

1. [Self-Abstraction from Grounded Experience for Plan-Guided Policy Refinement (SAGE)](https://arxiv.org/abs/2511.05931) `[2025-arXiv]`
2. [Improving Code Localization with Repository Memory](https://arxiv.org/abs/2510.01003) `[2026-ICLR]`
3. [SWE-Exp: Experience-Driven Software Issue Resolution](https://arxiv.org/abs/2507.23361) `[2025-arXiv]`
4. [LLMs as Continuous Learners: Improving the Reproduction of Defective Code in Software Issues (EvoCoder)](https://arxiv.org/abs/2411.13941) `[2024-arXiv]`
5. [Structurally Aligned Subtask-Level Memory for Software Engineering Agents (Subtask Memory)](https://arxiv.org/abs/2602.21611) `[2026-arXiv]`
6. [EvoRepair: Enhancing Vulnerability Repair Agents Through Experience-Based Self-Evolution](https://arxiv.org/abs/2605.30105) `[2026-arXiv]`
7. [SWE-MeM: Learning Adaptive Memory Management for Long-Horizon Coding Agents](https://arxiv.org/abs/2606.28434) `[2026-arXiv]`
8. [Your Code Agent Can Grow Alongside You with Structured Memory (MemCoder)](https://arxiv.org/abs/2603.13258) `[2026-arXiv]`
9. [Coupling Planning with Episodic Memory in LLM Agents for Software Issue Resolution (PMCoder)](https://arxiv.org/abs/2608.06811) `[2026-arXiv]`
10. [EXPEREPAIR: Dual-Memory Enhanced LLM-based Repository-Level Program Repair](https://arxiv.org/abs/2506.10484) `[2026-FSE]`

### 1.3 Skill and Tool Self-Evolution

1. [Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly?](https://arxiv.org/abs/2511.13646) `[2025-arXiv]`
2. [CODESKILL: Learning Self-Evolving Skills for Coding Agents](https://arxiv.org/abs/2605.25430) `[2026-arXiv]`
3. [Automatically Learning Skills for Coding Agents (GSkill)](https://doi.org/10.1145/3786335.3813196) `[2026-ACM CAIS]`
4. [Socratic-SWE: Self-Evolving Coding Agents via Trace-Derived Agent Skills](https://arxiv.org/abs/2606.07412) `[2026-arXiv]`
5. [EffiSkill: Agent Skill Based Automated Code Efficiency Optimization](https://arxiv.org/abs/2603.27850) `[2026-arXiv]`
6. [Learning Globally Reusable Skills for Coding Agents (GSE)](https://arxiv.org/abs/2608.06153) `[2026-arXiv]`
7. [Ratchet: How Reliable Must an LLM Judge Be to Retire a Skill?](https://arxiv.org/abs/2605.22148) `[2026-arXiv]`
8. [Self-Improving AI Coding Agents Through Accumulated Behavioral Rules: A Closed-Loop Framework](https://arxiv.org/abs/2607.13091) `[2026-IEEE ICE]`
9. [Do Personalized Skills Help Coding Agents? An Empirical Study of Developer Interaction Histories](https://arxiv.org/abs/2608.10319) `[2026-arXiv]`
10. [SIGA: Self-Evolving Coding-Agent Adapters for Scientific Simulation](https://arxiv.org/abs/2606.09774) `[2026-arXiv]`

### 1.4 Model Self-Evolution

1. [Toward Training Superintelligent Software Agents through Self-Play SWE-RL](https://arxiv.org/abs/2512.18552) `[2026-ICML]`
2. [Agent-RLVR: Training Software Engineering Agents via Guidance and Environment Rewards](https://arxiv.org/abs/2506.11425) `[2026-ICLR]`
3. [ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification](https://arxiv.org/abs/2506.11442) `[2026-ICLR]`
4. [CURE: Co-Evolving LLM Coder and Unit Tester via Reinforcement Learning](https://arxiv.org/abs/2506.03136) `[2025-NeurIPS]`
5. [ZeroCoder: Can LLMs Improve Code Generation Without Ground-Truth Supervision?](https://arxiv.org/abs/2604.07864) `[2026-arXiv]`
6. [Learning to Solve and Verify: A Self-Play Framework for Code and Test Generation (Sol-Ver)](https://arxiv.org/abs/2502.14948) `[2025-NeurIPS]`
7. [ACE: Self-Evolving LLM Coding Framework via Adversarial Unit Test Generation and Preference Optimization](https://arxiv.org/abs/2605.16299) `[2026-arXiv]`
8. [Harness-R1: Learning to Edit Executable Runtime Harnesses from Agent Failure Trajectories](https://arxiv.org/abs/2608.02276) `[2026-arXiv]`

### 1.5 Workflow and Topology Self-Evolution

1. [SEMAG: Self-Evolutionary Multi-Agent Code Generation](https://arxiv.org/abs/2603.15707) `[2026-arXiv]`
2. [Self-Evolving Multi-Agent Collaboration Networks for Software Development (EvoMAC)](https://arxiv.org/abs/2410.16946) `[2025-ICLR]`
3. [AgentConductor: Topology Evolution for Multi-Agent Competition-Level Code Generation](https://arxiv.org/abs/2602.17100) `[2026-ICML]`
4. [SEW: Self-Evolving Agentic Workflows for Automated Code Generation](https://arxiv.org/abs/2505.18646) `[2025-arXiv]`
5. [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762) `[2025-ICLR]`
6. [EvoAgentX: An Automated Framework for Evolving Agentic Workflows](https://arxiv.org/abs/2507.03616) `[2025-EMNLP Demos]`

### 1.6 Environment and Context Self-Evolution

1. [A Self-Evolving Framework for Efficient Terminal Agents via Observational Context Compression (TACO)](https://arxiv.org/abs/2604.19572) `[2026-arXiv]`
2. [SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents](https://arxiv.org/abs/2601.16746) `[2026-arXiv]`
3. [Libra: Training the Environment for Agentic Information Retrieval](https://arxiv.org/abs/2607.00016) `[2026-arXiv]`
4. [EvoConfig: Self-Evolving Multi-Agent Systems for Efficient Autonomous Environment Configuration](https://arxiv.org/abs/2601.16489) `[2026-arXiv]`

## 2. General Self-Evolution Methods in Coding Settings

### 2.1 Feedback Optimization

1. [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651) `[2023-NeurIPS]`
2. [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) `[2023-NeurIPS]`
3. [CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing](https://proceedings.iclr.cc/paper_files/paper/2024/hash/fef126561bbf9d4467dbb8d27334b8fe-Abstract-Conference.html) `[2024-ICLR]`
4. [Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models](https://proceedings.mlr.press/v235/zhou24r.html) `[2024-ICML]`
5. [Optimizing Generative AI by Backpropagating Language Model Feedback](https://doi.org/10.1038/s41586-025-08661-4) `[2025-Nature]`
6. [Training Language Models to Self-Correct via Reinforcement Learning](https://proceedings.iclr.cc/paper_files/paper/2025/hash/871ac99fdc5282d0301934d23945ebaa-Abstract-Conference.html) `[2025-ICLR]`
7. [SE-Agent: Self-Evolution Trajectory Optimization in Multi-Step Reasoning with LLM-Based Agents](https://arxiv.org/abs/2508.02085) `[2025-NeurIPS]`
8. [PromptBridge: Cross-Model Prompt Transfer for Large Language Models](https://arxiv.org/abs/2512.01420) `[2025-arXiv]`

### 2.2 Experience-Based Learning

1. [ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory](https://arxiv.org/abs/2509.25140) `[2026-ICLR]`
2. [Agent KB: Leveraging Cross-Domain Experience for Agentic Problem Solving](https://arxiv.org/abs/2507.06229) `[2025-ICML Workshop]`
3. [MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory](https://arxiv.org/abs/2601.03192) `[2026-arXiv]`
4. [ReCreate: Reasoning and Creating Domain Agents Driven by Experience](https://aclanthology.org/2026.acl-long.1432/) `[2026-ACL]`
5. [OPD-Evolver: Cultivating Holistic Agent Evolver via On-Policy Distillation](https://arxiv.org/abs/2606.17628) `[2026-arXiv]`
6. [SAGE: Self-Evolving Agents with Reflective and Memory-Augmented Abilities](https://doi.org/10.1016/j.neucom.2025.130470) `[2025-Neurocomputing]`

### 2.3 Skill Learning

1. [Who Grades the Grader? Co-Evolving Evaluation Metrics and Skills for Self-Improving LLM Agents](https://arxiv.org/abs/2607.12790) `[2026-arXiv]`
2. [FlowEvo: Self-Evolving Agents through the Co-Evolution of Workflows and Executable Skills](https://arxiv.org/abs/2607.21596) `[2026-arXiv]`
3. [From Procedural Skills to Strategy Genes: Towards Experience-Driven Test-Time Evolution](https://arxiv.org/abs/2604.15097) `[2026-arXiv]`

### 2.4 Self-Generated Training

1. [Absolute Zero: Reinforced Self-Play Reasoning with Zero Data](https://arxiv.org/abs/2505.03335) `[2025-NeurIPS]`
2. [Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis](https://arxiv.org/abs/2602.03279) `[2026-arXiv]`
3. [SAGE: Multi-Agent Self-Evolution for LLM Reasoning](https://arxiv.org/abs/2603.15255) `[2026-arXiv]`
4. [Self-Play Only Evolves When Self-Synthetic Pipeline Ensures Learnable Information Gain](https://arxiv.org/abs/2603.02218) `[2026-ICML Position Paper]`

### 2.5 System Optimization

1. [Language Agents as Optimizable Graphs](https://arxiv.org/abs/2402.16823) `[2024-ICML]`
2. [Symbolic Learning Enables Self-Evolving Agents](https://doi.org/10.1016/j.aiopen.2025.11.004) `[2025-AI Open]`
3. [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435) `[2025-ICLR]`
4. [MaAS: Multi-agent Architecture Search via Agentic Supernet](https://proceedings.mlr.press/v267/zhang25bi.html) `[2025-ICML]`
5. [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457) `[2026-ICLR]`
6. [A²Flow: Automating Agentic Workflow Generation via Self-Adaptive Abstraction Operators](https://ojs.aaai.org/index.php/AAAI/article/view/40240) `[2026-AAAI]`
7. [JudgeFlow: Agentic Workflow Optimization via Block Judge](https://arxiv.org/abs/2601.07477) `[2026-arXiv]`
8. [AgentEvo: Cost-Aware Agentic Workflow Generation via Adaptive Multi-Stage Evolution](https://doi.org/10.1007/s40747-026-02325-0) `[2026-Complex & Intelligent Systems]`
9. [Autogenesis: A Self-Evolving Agent Protocol](https://arxiv.org/abs/2604.15034) `[2026-arXiv]`
10. [FlowBot: Inducing LLM Workflows with Bilevel Optimization and Textual Gradients](https://arxiv.org/abs/2604.26258) `[2026-ICML]`
11. [EEVEE: Towards Test-time Prompt Learning in the Real World for Self-Improving Agents](https://arxiv.org/abs/2606.11182) `[2026-arXiv]`
12. [Automatically Evolving Prompt Guidelines for Task-Specific Optimization](https://arxiv.org/abs/2607.14105) `[2026-arXiv]`
13. [Harnessing Agentic Evolution](https://arxiv.org/abs/2605.13821) `[2026-arXiv]`
14. [Hyperagents](https://arxiv.org/abs/2603.19461) `[2026-arXiv]`

### 2.6 Collective Evolution

1. [Multi-Agent Evolve: LLM Self-Improve through Co-Evolution](https://arxiv.org/abs/2510.23595) `[2025-arXiv]`
2. [Self-Evolving Multi-Agent Systems via Textual Backpropagation](https://aclanthology.org/2026.findings-acl.483/) `[2026-ACL Findings]`
3. [LangMARL: Natural Language Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2604.00722) `[2026-arXiv]`
4. [CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery](https://arxiv.org/abs/2604.01658) `[2026-arXiv]`
5. [Evolve as a Team: Collaborative Self-Evolution for LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2605.29790) `[2026-arXiv]`

## 3. Benchmarks and Environments

### 3.1 Repository-Level Software Engineering Benchmarks

1. [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) `[2024-ICLR]`
2. [SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?](https://arxiv.org/abs/2509.16941) `[2026-ICML]`
3. [SWE-EVO: Benchmarking Coding Agents in Long-Horizon Software Evolution Scenarios](https://arxiv.org/abs/2512.18470) `[2025-arXiv]`
4. [SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?](https://arxiv.org/abs/2410.03859) `[2025-ICLR]`
5. [Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving](https://arxiv.org/abs/2504.02605) `[2025-NeurIPS Datasets and Benchmarks]`
6. [SWE-PolyBench: A Multi-Language Benchmark for Repository Level Evaluation of Coding Agents](https://arxiv.org/abs/2504.08703) `[2025-arXiv]`

### 3.2 General Coding Benchmarks

1. [Evaluating Large Language Models Trained on Code (HumanEval)](https://arxiv.org/abs/2107.03374) `[2021-arXiv]`
2. [Program Synthesis with Large Language Models (MBPP)](https://arxiv.org/abs/2108.07732) `[2021-arXiv]`
3. [Measuring Coding Challenge Competence with APPS](https://arxiv.org/abs/2105.09938) `[2021-NeurIPS Datasets and Benchmarks]`
4. [Competition-Level Code Generation with AlphaCode (CodeContests)](https://arxiv.org/abs/2203.07814) `[2022-Science]`
5. [LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974) `[2025-ICLR]`
6. [BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions](https://arxiv.org/abs/2406.15877) `[2025-ICLR]`
7. [Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation (EvalPlus)](https://arxiv.org/abs/2305.01210) `[2023-NeurIPS]`
8. [MultiPL-E: A Scalable and Extensible Approach to Benchmarking Neural Code Generation](https://arxiv.org/abs/2208.08227) `[2023-IEEE TSE]`
9. [DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation](https://arxiv.org/abs/2211.11501) `[2023-ICML]`
10. [CRUXEval: A Benchmark for Code Reasoning, Understanding and Execution](https://arxiv.org/abs/2401.03065) `[2024-ICML]`
11. [xCodeEval: A Large Scale Multilingual Multitask Benchmark for Code Understanding, Generation, Translation and Retrieval](https://arxiv.org/abs/2303.03004) `[2024-ACL]`
12. [EffiBench-X: A Multi-Language Benchmark for Measuring Efficiency of LLM-Generated Code](https://arxiv.org/abs/2505.13004) `[2025-NeurIPS Datasets and Benchmarks]`

### 3.3 Training and Evaluation Infrastructure

1. [Training Software Engineering Agents and Verifiers with SWE-Gym](https://arxiv.org/abs/2412.21139) `[2025-ICML]`
2. [R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents](https://arxiv.org/abs/2504.07164) `[2025-COLM]`
3. [EnvBench: A Benchmark for Automated Environment Setup](https://arxiv.org/abs/2503.14443) `[2025-ICLR Workshop]`
4. [InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback](https://arxiv.org/abs/2306.14898) `[2023-NeurIPS Datasets and Benchmarks]`
5. [SWE-smith: Scaling Data for Software Engineering Agents](https://arxiv.org/abs/2504.21798) `[2025-NeurIPS Datasets and Benchmarks]`
6. [SWE-RM: Execution-free Feedback For Software Engineering Agents](https://arxiv.org/abs/2512.21919) `[2026-ICLR]`
7. [SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents](https://arxiv.org/abs/2505.20411) `[2025-NeurIPS Datasets and Benchmarks]`

## 4. Self-Evolving Coding Products

The following products persist memories, skills, agent configurations, or environment settings across tasks. They are mapped to the same **Target** vocabulary as the paper taxonomy; inclusion describes a documented product mechanism and does not by itself imply a fully autonomous, experimentally validated self-evolution loop.

- **[Prime Agent (PA)](https://www.primeintellect.ai/blog/prime-agent)** — **Year:** 2026 · **Company:** Prime Intellect · **Target:** Agent framework, memory, skill and tool · [Code](https://github.com/PrimeIntellect-ai/prime-agent)
- **[Gemini CLI Auto Memory (GCAM)](https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/auto-memory.md)** — **Year:** 2026 · **Company:** Google · **Target:** Memory, skill and tool · [Changelog](https://github.com/google-gemini/gemini-cli/blob/main/docs/changelogs/index.md)
- **[GitHub Copilot Memory (GCM)](https://docs.github.com/en/copilot/concepts/agents/copilot-memory)** — **Year:** 2026 · **Company:** GitHub · **Target:** Memory · [Announcement](https://github.blog/changelog/2026-03-04-copilot-memory-now-on-by-default-for-pro-and-pro-users-in-public-preview/)
- **[Augment Agent / Cosmos Learning Flywheel (AA/CLF)](https://www.augmentcode.com/guides/agent-learning-flywheel)** — **Year:** 2025–2026 · **Company:** Augment Code · **Target:** Agent framework, memory, skill and tool · [Memory review](https://www.augmentcode.com/blog/how-we-built-memory-review)
- **[Claude Code Auto Memory (CCAM)](https://code.claude.com/docs/en/memory)** — **Year:** 2026 · **Company:** Anthropic · **Target:** Memory · [Changelog](https://code.claude.com/docs/en/changelog)
- **[Cursor Memories / Automations (CMA)](https://cursor.com/changelog/03-05-26)** — **Year:** 2025–2026 · **Company:** Cursor · **Target:** Agent framework, memory · [Memories](https://cursor.com/changelog/1-2)
- **[Devin Session Insights / Knowledge / Playbooks (Devin SIKP)](https://docs.devin.ai/product-guides/session-insights)** — **Year:** 2025–2026 · **Company:** Cognition · **Target:** Memory, skill and tool · [Advanced capabilities](https://docs.devin.ai/work-with-devin/advanced-capabilities)
- **[Windsurf Cascade Memories (WCM)](https://docs.windsurf.com/windsurf/cascade/memories)** — **Year:** 2025–2026 · **Company:** Windsurf / Cognition · **Target:** Memory
- **[OpenBlock Agent (OB-1)](https://www.openblocklabs.com/)** — **Year:** 2026 · **Company:** OpenBlock Labs · **Target:** Agent framework, skill and tool, environment and context · [Waitlist](https://waitlist.openblocklabs.com/)

Across these systems, memory is the most common entry point because it can improve continuity without changing model weights. A smaller group turns repeated experience into reusable skills or modifies the surrounding agent framework. OB-1 extends the target to environment and context, showing how productized evolution can reach beyond the agent's internal state.

## 5. Background

### 5.1 General Coding Agents

1. [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5a7c947568c1b1328ccc5230172e1e7c-Abstract-Conference.html) `[2024-NeurIPS]`
2. [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a4b6ad6b48850c0c331d1259fc66a69c-Abstract-Conference.html) `[2025-ICLR]`
3. [Executable Code Actions Elicit Better LLM Agents](https://proceedings.mlr.press/v235/wang24h.html) `[2024-ICML]`
4. [CodeT: Code Generation with Generated Tests](https://iclr.cc/virtual/2023/poster/12011) `[2023-ICLR]`
5. [LEVER: Learning to Verify Language-to-Code Generation with Execution](https://proceedings.mlr.press/v202/ni23b.html) `[2023-ICML]`
6. [CodeRL: Mastering Code Generation through Pretrained Models and Deep Reinforcement Learning](https://proceedings.neurips.cc/paper_files/paper/2022/hash/8636419dea1aa9fbd25fc4248e702da4-Abstract-Conference.html) `[2022-NeurIPS]`
7. [Teaching Large Language Models to Self-Debug](https://proceedings.iclr.cc/paper_files/paper/2024/hash/2460396f2d0d421885997dd1612ac56b-Abstract-Conference.html) `[2024-ICLR]`
8. [Is Self-Repair a Silver Bullet for Code Generation?](https://proceedings.iclr.cc/paper_files/paper/2024/hash/9ddc141bdbf9d1db510cefff56c586ad-Abstract-Conference.html) `[2024-ICLR]`
9. [Self-Edit: Fault-Aware Code Editor for Code Generation](https://aclanthology.org/2023.acl-long.45/) `[2023-ACL]`
10. [Debug like a Human: A Large Language Model Debugger via Verifying Runtime Execution Step by Step](https://aclanthology.org/2024.findings-acl.49/) `[2024-ACL Findings]`
11. [AlphaEvolve: A Coding Agent for Scientific and Algorithmic Discovery](https://arxiv.org/abs/2506.13131) `[2025-arXiv]`
12. [CodeEvolve: An Open-Source Evolutionary Coding Agent for Algorithmic Discovery and Optimization](https://arxiv.org/abs/2510.14150) `[2025-arXiv]`
13. [Reward Hacking in Self-Improving Code Agents](https://openreview.net/forum?id=JCjGvbsOmQ) `[2026-OpenReview]`

### 5.2 Repository-Level Software Engineering Agents

1. [CodePlan: Repository-Level Coding using LLMs and Planning](https://doi.org/10.1145/3643757) `[2024-FSE]`
2. [AutoCodeRover: Autonomous Program Improvement](https://2024.issta.org/details/issta-2024-papers/127/AutoCodeRover-Autonomous-Program-Improvement) `[2024-ISSTA]`
3. [RepairAgent: An Autonomous, LLM-Based Agent for Program Repair](https://conf.researchr.org/details/icse-2025/icse-2025-research-track/160/RepairAgent-An-Autonomous-LLM-Based-Agent-for-Program-Repair) `[2025-ICSE]`
4. [SpecRover: Code Intent Extraction via LLMs](https://conf.researchr.org/details/icse-2025/icse-2025-research-track/68/SpecRover-Code-Intent-Extraction-via-LLMs) `[2025-ICSE]`
5. [SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a1e6783e4d739196cad3336f12d402bf-Abstract-Conference.html) `[2025-ICLR]`
6. [RepoGraph: Enhancing AI Software Engineering with Repository-level Code Graph](https://proceedings.iclr.cc/paper_files/paper/2025/hash/4a4a3c197deac042461c677219efd36c-Abstract-Conference.html) `[2025-ICLR]`
7. [Demystifying LLM-Based Software Engineering Agents (Agentless)](https://doi.org/10.1145/3715754) `[2025-FSE]`
8. [SWE-Master: Unleashing the Potential of Software Engineering Agents via Post-Training](https://arxiv.org/abs/2602.03411) `[2026-arXiv]`
9. [Rethinking the Value of Agent-Generated Tests for LLM-Based Software Engineering Agents](https://arxiv.org/abs/2602.07900) `[2026-arXiv]`
10. [Scaling Test-Time Compute for Agentic Coding](https://arxiv.org/abs/2604.16529) `[2026-arXiv]`
11. [SWE-Replay: Efficient Test-Time Scaling for Software Engineering Agents](https://arxiv.org/abs/2601.22129) `[2026-arXiv]`
12. [SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution](https://arxiv.org/abs/2502.18449) `[2025-NeurIPS]`
13. [Understanding Code Agent Behaviour: An Empirical Study of Success and Failure Trajectories](https://arxiv.org/abs/2511.00197) `[2025-arXiv]`
14. [Your Agent May Misevolve: Emergent Risks in Self-Evolving LLM Agents](https://openreview.net/forum?id=lS1gWUHbfx) `[2026-ICLR]`

### 5.3 Multi-Agent Coding

1. [ChatDev: Communicative Agents for Software Development](https://aclanthology.org/2024.acl-long.810/) `[2024-ACL]`
2. [MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://proceedings.iclr.cc/paper_files/paper/2024/hash/6507b115562bb0a305f1958ccc87355a-Abstract-Conference.html) `[2024-ICLR]`
3. [MapCoder: Multi-Agent Code Generation for Competitive Problem Solving](https://aclanthology.org/2024.acl-long.269/) `[2024-ACL]`
4. [MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution](https://papers.nips.cc/paper_files/paper/2024/hash/5d1f02132ef51602adf07000ca5b6138-Abstract-Conference.html) `[2024-NeurIPS]`

## 6. Related Surveys

### 6.1 Surveys on Self-Evolving Agents

1. [A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence](https://openreview.net/forum?id=CTr3bovS5F) `[2026-TMLR]`
2. [A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems](https://arxiv.org/abs/2508.07407) `[2025-arXiv]`
3. [A Systematic Survey of Self-Evolving Agents: From Model-Centric to Environment-Driven Co-Evolution](https://doi.org/10.36227/techrxiv.177203250.05832634/v2) `[2026-TechRxiv]`
4. [Self-Improvements in Modern Agentic Systems: A Survey](https://arxiv.org/abs/2607.13104) `[2026-arXiv]`
5. [Self-Improving Agents in the Era of Experience: A Survey of Self- to Meta-Evolution](https://openreview.net/forum?id=IUltZSgLMm) `[2026-OpenReview]`
6. [A Survey on Self-Evolution of Large Language Models](https://arxiv.org/abs/2404.14387) `[2024-arXiv]`
7. [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224) `[2026-arXiv]`

### 6.2 Surveys on Coding Agents

1. [Large Language Model-Based Agents for Software Engineering: A Survey](https://arxiv.org/abs/2409.02977) `[2025-TOSEM]`
2. [Agents in Software Engineering: Survey, Landscape, and Vision](https://doi.org/10.1007/s10515-025-00544-2) `[2025-Automated Software Engineering]`
3. [LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision, and the Road Ahead](https://doi.org/10.1145/3712003) `[2025-TOSEM]`
4. [Large Language Models for Software Engineering: A Systematic Literature Review](https://doi.org/10.1145/3695988) `[2024-TOSEM]`
5. [A Survey on Large Language Models for Code Generation](https://doi.org/10.1145/3747588) `[2026-TOSEM]`
6. [Advances and Frontiers of LLM-Based Issue Resolution in Software Engineering: A Comprehensive Survey](https://arxiv.org/abs/2601.11655) `[2026-arXiv]`

## Citation

```bibtex
@article{zhou2026self,
  title={Self-Evolving Coding Agents},
  author={Zhou, Hao and Hu, Haichuan and Shang, Ye and Zhang, Quanjun},
  journal={arXiv preprint arXiv:2608.03392},
  year={2026}
}
```
