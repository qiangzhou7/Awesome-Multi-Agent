<!--
 * @Author: Qiang Zhou qiz166@pitt.edu
 * @Date: 2025-05-26 10:24:25
 * @LastEditors: Qiang Zhou qiz166@pitt.edu
 * @LastEditTime: 2025-05-26 11:56:23
 * @FilePath: /projects/Awesome-Multi-Agent/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# 🤖🤝 Awesome Multi-Agent with LLMs

> _“One LLM is smart. A swarm of them? That’s a society.”_  
> A curated list of awesome projects, papers, demos, and resources at the intersection of **Large Language Models (LLMs)** and **Multi-Agent Systems**.

---

## 🎯 Why This Repo?

LLMs can do a lot on their own — but things get *really interesting* when they start talking to each other.  
This repo explores the wild, weird, and wonderful world of **multi-agent systems** powered by LLMs:  
agents that chat, collaborate, deceive, plan, negotiate, build, and maybe... start a company?

If you’re into:
- 🤹 Emergent behavior from LLM agents  
- 🧠 Cognitive architectures in agent societies  
- 📦 Agents that plan, act, and revise  
- 🌍 Simulated economies, governments, classrooms, or adventuring parties...

You're in the right place.

---

## 🧭 Directory

### 📜 1. Research Papers
> Where science meets social simulations.

> Multi-Agent Efficiency

- **Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies**, 2025.02, [[paper]](https://arxiv.org/pdf/2502.02533)
- **AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration**, 2025.03, [[paper]](https://arxiv.org/pdf/2503.18891)
- **Cut the Crap: An Economical Communication Pipeline for LLM-based Multi-Agent Systems**, 2024.10, [[paper]](https://arxiv.org/pdf/2410.02506)
- **A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration**，2024.11, [[paper]](https://arxiv.org/pdf/2310.02170)


### 🧪 2. Benchmarks & Simulations
> Single Agent.

- Code Generation(CG)
  - **HumanEval benchmark**: 包含164个由人工编写的函数级代码补全问题和单元测试，用于评估代码生成能力。
  - **MBPP (Mostly Basic Python Problems)**: 包含约1000个众包的Python编程问题，主要侧重于入门级难度，每个问题包含一个任务描述、一个解决方案和一个测试集。
  - **CodeContests (from DeepMind)**: 包含来自编程竞赛的问题，用于评估在更复杂算法和问题解决场景下的代码生成能力，通常需要更深层次的推理和规划。
- Decision Making(DM)
  - **WebShop**: 要求智能体根据顾客的指令在模拟的购物网站上找到指定商品。通过商品与指令的相关性提供“奖励（reward）”作为内在指标，“成功（success）”则在奖励为1.0时标记。
  - **ALFWorld (Abbreviated Language-based Fine-grained World models)**: 智能体需要在基于文本的模拟家庭环境中理解指令并完成一系列日常任务（如拿起、放置、开关物体等）。评估指标包括任务成功率。
  - **ToolBench**: 一个全面的工具使用评测基准，智能体需要学习并组合使用多种API（工具）来完成复杂指令。评估重点在于工具选择、参数填充和执行的正确性。
  - **AgentBench (一部分任务)**: 包含操作系统、数据库、网页浏览等多种环境中的决策任务。例如，在操作系统任务中，智能体需要执行一系列命令来完成特定目标。
- General Reasoning(GR) 
  - **MMLU Dataset**: 涵盖57个学科的大量问题，分为四个类别（人文、社会科学、STEM、其他），用于评估模型的广泛知识和推理能力。
  - **Big-Bench Hard (BBH)**: Big-Bench中被认为对当前语言模型最具挑战性的23个任务的子集，专注于需要多步推理的任务。
  - **GAIA (General AI Assistants)**: 一个旨在评估通用人工智能助手能力的基准，包含需要多步骤推理、工具使用和精确信息检索的复杂、真实世界风格的问题。
  - **HotpotQA**: 一个基于维基百科的多跳问答数据集，需要模型综合来自多个文档的信息进行推理才能回答问题
- Arithmetic Reasoning(AR)
  - **MATH**: 包含7个子领域（代数、几何、预代数、计数与概率、中级代数、数论、微积分预备知识）的12500个具有挑战性的竞赛数学问题。
  - **GSM8K (Grade School Math 8K)**: 包含约8500个高质量的小学数学应用题，测试模型进行多步数学推理的能力。
  - **SVAMP (Simple Variations on Arithmetic Math Problems)**: 通过对已有数学问题进行细微但关键的语义变化，来测试模型对问题结构和语义的鲁棒理解。
  
> Multi-agent.
上述很多基准主要针对单 LLM Agent 的核心能力。对于 Multi-LLM-Agent 系统，评价会更侧重于它们的协作、沟通、角色扮演、社会行为和集体解决问题的能力。虽然一些单智能体基准可以被适配（例如，让多个智能体协作完成 WebShop 或 ALFWorld 中的任务），但也有一些专门或更侧重于多智能体交互的场景和基准正在涌现：


### 🛠️ 3. Frameworks & Toolkits
> Build your own agent society.

- 🏗️ Multi-agent orchestration libraries (AutoGen, CAMEL, ChatDev, etc.)  
- 🎛️ Planning frameworks and tool-assisted action loops  
- 💬 Multi-agent chatroom & simulation engines  
- 🧠 Tools for memory, persona, and world state modeling

### 🎮 4. Demos & Cool Projects
> Agents gone wild.

- 🎲 Simulated societies with emergent behavior  
- 🧬 Scientific experiments in self-organization and adaptation  
- 🧑‍💼 Multi-agent startups & autonomous business systems  
- 👾 Games with LLM-powered NPCs and parties  

### 🧠 5. Theory & Concepts
> Minds, motives, and models.

- 🧭 Agent modeling & decision theory  
- 🎭 Role assignment, identity, and social cognition  
- ⚖️ Negotiation, deception, and moral reasoning  
- 🧠 Group dynamics & distributed cognition  
- 📚 Learning from interaction and memory traces

### 🚀 6. Open Questions & Speculative Directions
> The fun stuff.

- 🪐 Can LLM agents form cultures or traditions?  
- 🤔 What does it mean for agents to "understand" each other?  
- 🧯 Can emergent behavior be guided… or should it?  
- 📽️ When will the LLM Agent Reality Show air?

---

## 💡 Contribution Guide

Wanna help build the ultimate agent archive?  
We **love contributions**! Open a PR or an issue and share your findings.

```bash
📁 Category: (e.g., Research Paper, Framework, Demo)
🔗 Link: Your awesome discovery here
📝 Description: 1–2 lines about what it does and why it’s cool
