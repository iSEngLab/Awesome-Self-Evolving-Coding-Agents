# Self-Evolving Coding Agents

## 项目介绍

随着大语言模型在软件工程中的应用不断深入，编程智能体已经能够完成代码生成、仓库理解、工具调用、测试执行、错误分析和补丁生成等任务。在此基础上，越来越多的研究开始关注智能体如何利用执行结果、任务轨迹、历史经验和环境反馈持续改进自身。

本仓库旨在整理与 **Self-Evolving Coding Agents** 相关的论文、系统、基准和研究资源。除直接研究自进化编程智能体的工作外，我们也关注在代码或软件工程任务上进行评测的通用进化方法，以及与该方向密切相关的基准环境、编程智能体和综述。

本列表将持续更新。当前分类是一个初步框架，后续会随着相关论文的增加和讨论进一步调整。

## 收录范围

目前，本仓库主要收录以下五类工作：

1. **核心自进化编程智能体**  
   直接研究编程智能体或软件工程智能体如何利用反馈、经验或交互过程实现自我改进的工作，其中也包括与协同进化相关的方法。

2. **使用代码或软件工程评测的通用进化方法**  
   方法本身不一定专门面向编程智能体，但使用代码生成、程序修复、软件工程任务或相关 Benchmark 进行评测。

3. **相关基准与环境**  
   用于训练、评估或分析编程智能体和自进化方法的 Benchmark、数据集、执行环境与验证工具。

4. **编程智能体背景工作**  
   与自进化方向密切相关，但本身不一定具有明确进化机制的 Coding Agent、SWE Agent 和软件开发框架。

5. **相关综述**  
   与自进化智能体、编程智能体、代码大模型和大语言模型软件工程应用相关的综述与资源列表。

由于 Self-Evolving Coding Agents 仍然是一个正在发展的研究方向，本仓库暂时采用相对宽泛的收录范围。具体定义、分类方式和论文边界将在后续整理过程中继续讨论和完善。

## 目录

- [1. 核心自进化编程智能体](#1-核心自进化编程智能体)
- [2. 使用代码或软件工程评测的通用进化方法](#2-使用代码或软件工程评测的通用进化方法)
- [3. 相关基准与环境](#3-相关基准与环境)
- [4. 编程智能体背景工作](#4-编程智能体背景工作)
- [5. 相关综述](#5-相关综述)

## 1. 核心自进化编程智能体

### 1.1 智能体框架自进化

1. [A Self-Improving Coding Agent (SICA)](https://arxiv.org/abs/2504.15228) `[2025-arXiv]`
2. [Self-Improvement via Fast Tree-Search (SIFT)](https://openreview.net/forum?id=wZMNXHPYcO) `[2026-ICLR]`
3. [Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation](https://arxiv.org/abs/2310.02304) `[2024-COLM]`
4. [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954) `[2025-arXiv]`
5. [Mendel Gödel Machine: Comparative Evolution Enables State-of-the-Art Self-Improving Coding Agents](https://openreview.net/forum?id=EJ7gBBDvCg) `[2026-OpenReview]`
6. [Huxley Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine](https://arxiv.org/abs/2510.21614) `[2025-arXiv]`

### 1.2 记忆自进化

1. [SWE-Exp: Experience-Driven Software Issue Resolution](https://arxiv.org/abs/2507.23361) `[2026-arXiv]`
2. [LLMs as Continuous Learners: Improving the Reproduction of Defective Code in Software Issues (EvoCoder)](https://arxiv.org/abs/2411.13941) `[2024-arXiv]`
3. [Structurally Aligned Subtask-Level Memory for Software Engineering Agents](https://arxiv.org/abs/2602.21611) `[2026-arXiv]`
4. [EvoRepair: Enhancing Vulnerability Repair Agents Through Experience-Based Self-Evolution](https://arxiv.org/abs/2605.30105) `[2026-arXiv]`
5. [Improving Code Localization with Repository Memory](https://arxiv.org/abs/2510.01003) `[2026-arXiv]`
6. [Self-Abstraction from Grounded Experience for Plan-Guided Policy Refinement (SAGE)](https://arxiv.org/abs/2511.05931) `[2025-arXiv]`

### 1.3 技能与工具自进化

1. [CODESKILL: Learning Self-Evolving Skills for Coding Agents](https://arxiv.org/abs/2605.25430) `[2026-arXiv]`
2. [Automatically Learning Skills for Coding Agents (GSkill)](https://doi.org/10.1145/3786335.3813196) `[2026-ACM AI and Agentic Systems]`
3. [Socratic-SWE: Self-Evolving Coding Agents via Trace-Derived Agent Skills](https://arxiv.org/abs/2606.07412) `[2026-arXiv]`
4. [EffiSkill: Agent Skill Based Automated Code Efficiency Optimization](https://arxiv.org/abs/2603.27850) `[2026-arXiv]`
5. [Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly?](https://arxiv.org/abs/2511.13646) `[2025-arXiv]`

### 1.4 模型自进化

1. [Toward Training Superintelligent Software Agents through Self-Play SWE-RL](https://arxiv.org/abs/2512.18552) `[2026-arXiv]`
2. [Agent-RLVR: Training Software Engineering Agents via Guidance and Environment Rewards](https://arxiv.org/abs/2506.11425) `[2025-arXiv]`
3. [ReVeal: Self-Evolving Code Agents via Iterative Generation-Verification](https://arxiv.org/abs/2506.11442) `[2025-arXiv]`
4. [CURE: Co-Evolving LLM Coder and Unit Tester via Reinforcement Learning](https://arxiv.org/abs/2506.03136) `[2025-arXiv]`
5. [ZeroCoder: Can LLMs Improve Code Generation Without Ground-Truth Supervision?](https://arxiv.org/abs/2604.07864) `[2026-arXiv]`
6. [Learning to Solve and Verify: A Self-Play Framework for Code and Test Generation (Sol-Ver)](https://arxiv.org/abs/2502.14948) `[2025-arXiv]`
7. [ACE: Self-Evolving LLM Coding Framework via Adversarial Unit Test Generation and Preference Optimization](https://arxiv.org/abs/2605.16299) `[2026-arXiv]`

### 1.5 工作流与拓扑自进化

1. [SEW: Self-Evolving Agentic Workflows for Automated Code Generation](https://arxiv.org/abs/2505.18646) `[2025-arXiv]`
2. [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762) `[2024-arXiv]`
3. [EvoAgentX: An Automated Framework for Evolving Agentic Workflows](https://arxiv.org/abs/2507.03616) `[2025-arXiv]`
4. [SEMAG: Self-Evolutionary Multi-Agent Code Generation](https://arxiv.org/abs/2603.15707) `[2026-arXiv]`
5. [Self-Evolving Multi-Agent Collaboration Networks for Software Development (EvoMAC)](https://arxiv.org/abs/2410.16946) `[2024-arXiv]`
6. [AgentConductor: Topology Evolution for Multi-Agent Competition-Level Code Generation](https://arxiv.org/abs/2602.17100) `[2026-arXiv]`

## 2. 使用代码或软件工程评测的通用进化方法

<!-- 具体分类和论文列表待补充 -->

## 3. 相关基准与环境

### 3.1 仓库级软件工程基准

1. [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) `[2024-ICLR]`
2. [SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?](https://arxiv.org/abs/2509.16941) `[2025-arXiv]`
3. [SWE-EVO: Benchmarking Coding Agents in Long-Horizon Software Evolution Scenarios](https://arxiv.org/abs/2512.18470) `[2025-arXiv]`
4. [SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?](https://arxiv.org/abs/2410.03859) `[2024-arXiv]`
5. [Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving](https://arxiv.org/abs/2504.02605) `[2025-arXiv]`
6. [SWE-PolyBench: A Multi-Language Benchmark for Repository Level Evaluation of Coding Agents](https://arxiv.org/abs/2504.08703) `[2025-arXiv]`

### 3.2 通用代码能力基准

1. [Evaluating Large Language Models Trained on Code (HumanEval)](https://arxiv.org/abs/2107.03374) `[2021-arXiv]`
2. [Program Synthesis with Large Language Models (MBPP)](https://arxiv.org/abs/2108.07732) `[2021-arXiv]`
3. [Measuring Coding Challenge Competence with APPS](https://arxiv.org/abs/2105.09938) `[2021-arXiv]`
4. [Competition-Level Code Generation with AlphaCode (CodeContests)](https://arxiv.org/abs/2203.07814) `[2022-Science]`
5. [LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974) `[2024-arXiv]`
6. [BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions](https://arxiv.org/abs/2406.15877) `[2024-arXiv]`
7. [Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation (EvalPlus)](https://arxiv.org/abs/2305.01210) `[2023-arXiv]`
8. [MultiPL-E: A Scalable and Extensible Approach to Benchmarking Neural Code Generation](https://arxiv.org/abs/2208.08227) `[2022-arXiv]`
9. [DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation](https://arxiv.org/abs/2211.11501) `[2023-ICML]`
10. [CRUXEval: A Benchmark for Code Reasoning, Understanding and Execution](https://arxiv.org/abs/2401.03065) `[2024-ICML]`
11. [xCodeEval: A Large Scale Multilingual Multitask Benchmark for Code Understanding, Generation, Translation and Retrieval](https://arxiv.org/abs/2303.03004) `[2023-arXiv]`
12. [EffiBench-X: A Multi-Language Benchmark for Measuring Efficiency of LLM-Generated Code](https://arxiv.org/abs/2505.13004) `[2025-arXiv]`

### 3.3 训练与评测基础设施

1. [Training Software Engineering Agents and Verifiers with SWE-Gym](https://arxiv.org/abs/2412.21139) `[2025-arXiv]`
2. [R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents](https://arxiv.org/abs/2504.07164) `[2025-arXiv]`
3. [EnvBench: A Benchmark for Automated Environment Setup](https://arxiv.org/abs/2503.14443) `[2025-arXiv]`
4. [InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback](https://arxiv.org/abs/2306.14898) `[2023-arXiv]`
5. [SWE-smith: Scaling Data for Software Engineering Agents](https://arxiv.org/abs/2504.21798) `[2025-arXiv]`
6. [SWE-RM: Execution-free Feedback For Software Engineering Agents](https://arxiv.org/abs/2512.21919) `[2025-arXiv]`
7. [SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents](https://arxiv.org/abs/2505.20411) `[2025-arXiv]`

## 4. 编程智能体背景工作

### 4.1 通用编程方法

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

### 4.2 仓库级软件工程智能体

1. [CodePlan: Repository-Level Coding using LLMs and Planning](https://doi.org/10.1145/3643757) `[2024-FSE]`
2. [AutoCodeRover: Autonomous Program Improvement](https://2024.issta.org/details/issta-2024-papers/127/AutoCodeRover-Autonomous-Program-Improvement) `[2024-ISSTA]`
3. [RepairAgent: An Autonomous, LLM-Based Agent for Program Repair](https://conf.researchr.org/details/icse-2025/icse-2025-research-track/160/RepairAgent-An-Autonomous-LLM-Based-Agent-for-Program-Repair) `[2025-ICSE]`
4. [SpecRover: Code Intent Extraction via LLMs](https://conf.researchr.org/details/icse-2025/icse-2025-research-track/68/SpecRover-Code-Intent-Extraction-via-LLMs) `[2025-ICSE]`
5. [SWE-Search: Enhancing Software Agents with Monte Carlo Tree Search and Iterative Refinement](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a1e6783e4d739196cad3336f12d402bf-Abstract-Conference.html) `[2025-ICLR]`
6. [RepoGraph: Enhancing AI Software Engineering with Repository-level Code Graph](https://proceedings.iclr.cc/paper_files/paper/2025/hash/4a4a3c197deac042461c677219efd36c-Abstract-Conference.html) `[2025-ICLR]`

### 4.3 多智能体编程

1. [ChatDev: Communicative Agents for Software Development](https://aclanthology.org/2024.acl-long.810/) `[2024-ACL]`
2. [MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://proceedings.iclr.cc/paper_files/paper/2024/hash/6507b115562bb0a305f1958ccc87355a-Abstract-Conference.html) `[2024-ICLR]`
3. [MapCoder: Multi-Agent Code Generation for Competitive Problem Solving](https://aclanthology.org/2024.acl-long.269/) `[2024-ACL]`
4. [MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution](https://papers.nips.cc/paper_files/paper/2024/hash/5d1f02132ef51602adf07000ca5b6138-Abstract-Conference.html) `[2024-NeurIPS]`

## 5. 相关综述

### 5.1 自进化智能体综述

1. [A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence](https://openreview.net/forum?id=CTr3bovS5F) `[2026-TMLR]`
2. [A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems](https://arxiv.org/abs/2508.07407) `[2025-arXiv]`
3. [A Systematic Survey of Self-Evolving Agents: From Model-Centric to Environment-Driven Co-Evolution](https://doi.org/10.36227/techrxiv.177203250.05832634/v2) `[2026-TechRxiv]`
4. [Self-Improvements in Modern Agentic Systems: A Survey](https://arxiv.org/abs/2607.13104) `[2026-arXiv]`
5. [Self-Improving Agents in the Era of Experience: A Survey of Self- to Meta-Evolution](https://openreview.net/forum?id=IUltZSgLMm) `[2026-OpenReview]`
6. [A Survey on Self-Evolution of Large Language Models](https://arxiv.org/abs/2404.14387) `[2024-arXiv]`

### 5.2 编程智能体综述

1. [Large Language Model-Based Agents for Software Engineering: A Survey](https://arxiv.org/abs/2409.02977) `[2025-TOSEM]`
2. [Agents in Software Engineering: Survey, Landscape, and Vision](https://doi.org/10.1007/s10515-025-00544-2) `[2025-Automated Software Engineering]`
3. [LLM-Based Multi-Agent Systems for Software Engineering: Literature Review, Vision, and the Road Ahead](https://doi.org/10.1145/3712003) `[2025-TOSEM]`

### 5.3 代码大模型综述

1. [Large Language Models for Software Engineering: Survey and Open Problems](https://doi.org/10.1109/ICSE-FoSE59343.2023.00008) `[2023-ICSE FoSE]`
2. [Large Language Models for Software Engineering: A Systematic Literature Review](https://doi.org/10.1145/3695988) `[2024-TOSEM]`
3. [A Survey on Large Language Models for Code Generation](https://doi.org/10.1145/3747588) `[2026-TOSEM]`
4. [A Survey on Large Language Models for Software Engineering](https://doi.org/10.1007/s11432-025-4670-0) `[2026-Science China Information Sciences]`

### 5.4 通用智能体综述

1. [The Rise and Potential of Large Language Model Based Agents: A Survey](https://doi.org/10.1007/s11432-024-4222-0) `[2025-Science China Information Sciences]`
2. [A Survey on Large Language Model Based Autonomous Agents](https://doi.org/10.1007/s11704-024-40231-1) `[2024-Frontiers of Computer Science]`
3. [Large Language Model Based Multi-Agents: A Survey of Progress and Challenges](https://www.ijcai.org/proceedings/2024/890) `[2024-IJCAI]`
