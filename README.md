# Agentic Systems & LLM Code Evolution Papers

A curated collection of research papers, articles, and resources focused on Large Language Models, agentic architectures, and automated code or algorithm evolution.

## Foundational Agentic Architectures

### [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
**Authors:** Shunyu Yao et al. (2022)
This paper introduces the ReAct prompting framework, which allows LLMs to interleave reasoning traces with task-specific actions. This framework is foundational for agents that need to write code, test it, and decide on the next step.

### [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366)
**Authors:** Noah Shinn et al. (2023)
This research demonstrates how agents can reflect on task feedback and execution errors to maintain a linguistic episodic memory. This self-reflection loop is a primary mechanism for iterative code debugging and evolution.

## LLM-Driven Algorithm Discovery

### [Mathematical discoveries from program search with large language models (FunSearch)](https://www.nature.com/articles/s41586-023-06924-6)
**Authors:** Bernardino Romera-Paredes et al. (2023)
Google DeepMind's paper on pairing a pre-trained LLM with an automated evaluator. The system continuously evolves Python code snippets to discover novel solutions for open mathematical and algorithmic problems.

### [Eureka: Human-Level Reward Design via Coding Large Language Models](https://arxiv.org/abs/2310.12931)
**Authors:** Yecheng Jason Ma et al. (2023)
This work details a zero-shot generation framework where LLMs are used in an evolutionary loop to write, test, and iteratively improve reward function algorithms for complex reinforcement learning environments.

## Code Evolution and Repository-Level Agents

### [Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models (LATS)](https://arxiv.org/abs/2310.04406)
**Authors:** Andy Zhou et al. (2023)
LATS combines Monte Carlo Tree Search with LLM agents to explore different coding paths. By evaluating the execution success of different generated code branches, the system evolves highly optimized programming solutions.

### [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)
**Authors:** John Yang et al. (2024)
This paper details the construction of autonomous software engineering agents. It explores how an agent can navigate entire file systems, iteratively edit codebases, and evolve its understanding of a repository to resolve complex issues.

## How to Read and Add to this Repository
To add new research to this collection, create a level-three heading with the paper's title linked to its arXiv or publication page. Follow this with a bolded section for the authors and publication year, and conclude with a brief paragraph summarizing how the paper advances the field of agentic code evolution.
