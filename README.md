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

## Core Evolutionary Frameworks & Open-Source Agents

### [AlphaEvolve: A coding agent for scientific and algorithmic discovery](https://arxiv.org/abs/2506.13131)
**Authors:** Alexander Novikov et al. (2025)
This paper introduces an evolutionary coding agent that iteratively improves algorithms via continuous evaluator feedback. It demonstrates broad capabilities in scientific and algorithmic discovery, including optimizing Google's computational infrastructure and finding a novel algorithm for complex matrix multiplication that surpasses Strassen's 56-year-old method.

### [ShinkaEvolve: Towards Open-Ended And Sample-Efficient Program Evolution](https://arxiv.org/abs/2509.19349)
**Authors:** Robert Tjarko Lange et al. (2025)
This work presents a highly sample-efficient, open-source framework leveraging LLMs as mutation operators. It introduces novel parent sampling, code novelty rejection-sampling, and bandit-based ensemble selection to democratize open-ended discovery across diverse mathematical and programming tasks without relying on massive compute budgets.

### [CodeEvolve: an open source evolutionary coding agent for algorithmic discovery and optimization](https://arxiv.org/abs/2510.14150)
**Authors:** Henrique Assumpção et al. (2025)
This open-source framework couples an islands-based genetic algorithm with modular LLM orchestration to synthesize high-performing algorithms. By utilizing context-aware recombination and adaptive meta-prompting, the system matches or exceeds closed-source baselines on AlphaEvolve benchmarks at a fraction of the cost.

### [CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery](https://arxiv.org/abs/2604.01658)
**Authors:** Ao Qu et al. (2026)
This paper proposes an autonomous multi-agent evolution framework for open-ended discovery. It replaces rigid heuristics with long-running agents that explore, reflect, and collaborate through shared memory and asynchronous execution, significantly improving optimization rates on mathematical and systems tasks.

## Principled Search Strategies & Theoretical Frameworks

### [DeltaEvolve: Accelerating Scientific Discovery through Momentum-Driven Evolution](https://arxiv.org/abs/2602.02919)
**Authors:** Jiachen Jiang et al. (2026)
This paper frames LLM evolutionary agents as an Expectation-Maximization process and introduces a momentum-driven framework. By replacing full-code histories with structured semantic deltas that capture how and why modifications work, the system reduces token consumption and provides clearer guidance for subsequent evolutionary steps.

### [SMCEvolve: Principled Scientific Discovery via Sequential Monte Carlo Evolution](https://arxiv.org/abs/2605.15308)
**Authors:** Jiachen Jiang et al. (2026)
This work recasts program search as sampling from a reward-tilted target distribution using a Sequential Monte Carlo sampler. It provides a principled mathematical foundation for evolutionary components like adaptive parent resampling and automatic convergence control, alongside finite-sample complexity analysis for LLM-call budgets.

## Adaptive Search & Meta-Evolution Strategies

### [SeaEvo: Advancing Algorithm Discovery with Strategy Space Evolution](https://arxiv.org/abs/2604.24372)
**Authors:** Sichun Luo et al. (2026)
This research introduces a modular strategy-space layer that elevates natural-language strategic reasoning into population-level evolutionary states. This prevents evolutionary search from saturating on syntactically different but strategically identical ideas, substantially improving existing evolutionary backbones across algorithmic discovery tasks.

### [LEVI: Stronger Search Architectures Can Substitute for Larger LLMs in Evolutionary Search](https://arxiv.org/abs/2605.09764)
**Authors:** Temoor Tanveer (2026)
This work argues that robust search architectures can substitute for the heavy costs of frontier LLMs in evolutionary search. By utilizing a diversity-preserving database, smart mutation routing between large and small LLMs, and proxy benchmarks, LEVI achieves state-of-the-art results on budgets drastically smaller than previous frameworks.

### [EvoX: Meta-Evolution for Automated Discovery](https://arxiv.org/abs/2602.23413)
**Authors:** Shu Liu et al. (2026)
This paper explores a meta-evolutionary approach where the system adaptively optimizes its own evolutionary process. By jointly evolving the candidate solutions and the search strategies used to generate them, EvoX continuously updates how prior solutions are selected and varied, outperforming methods with static search schedules.

### [AdaEvolve: Adaptive LLM Driven Zeroth-Order Optimization](https://arxiv.org/abs/2602.20133)
**Authors:** Mert Cemri et al. (2026)
This framework reformulates LLM-driven evolution as a hierarchical adaptive optimization problem to minimize computational waste. It uses an accumulated improvement signal to dynamically manage local exploration intensity, route global resources via bandit scheduling, and generate meta-guidance when progress stalls.

## Prompt & Test-Time Evolution

### [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457)
**Authors:** Lakshya A Agrawal et al. (2025)
This research compares reflective prompt evolution against reinforcement learning techniques like GRPO. GEPA uses natural language reflection to diagnose problems and combine complementary lessons from a Pareto frontier of attempts, demonstrating that language provides a richer, more sample-efficient learning medium than scalar rewards.

### [PACEvolve++: Improving Test-time Learning for Evolutionary Search Agents](https://arxiv.org/abs/2605.07039)
**Authors:** Minghao Yan et al. (2026)
This paper introduces an advisor-model reinforcement learning framework for test-time policy adaptation. It decouples search strategy from implementation, training an advisor model to dynamically adapt its optimization strategy across different phases of evolution to stabilize and speed up convergence.

## Code Evolution and Repository-Level Agents

### [Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models (LATS)](https://arxiv.org/abs/2310.04406)
**Authors:** Andy Zhou et al. (2023)
LATS combines Monte Carlo Tree Search with LLM agents to explore different coding paths. By evaluating the execution success of different generated code branches, the system evolves highly optimized programming solutions.

### [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)
**Authors:** John Yang et al. (2024)
This paper details the construction of autonomous software engineering agents. It explores how an agent can navigate entire file systems, iteratively edit codebases, and evolve its understanding of a repository to resolve complex issues.

## Applied Evolution & Heuristic Design

### [Scientific Algorithm Discovery by Augmenting AlphaEvolve with Deep Research](https://arxiv.org/abs/2510.06056)
**Authors:** Gang Liu et al. (2025)
This system augments the pure algorithm evolution of AlphaEvolve with deep research capabilities. It combines external knowledge retrieval, cross-file editing, and systematic debugging to propose, implement, and validate complex hypotheses across domains like chemistry, biology, and materials science.

### [Autopoiesis: A Self-Evolving System Paradigm for LLM Serving Under Runtime Dynamics](https://arxiv.org/abs/2604.07144)
**Authors:** Youhe Jiang et al. (2026)
This work applies LLM-driven program synthesis to manage real-time workload fluctuations in LLM serving systems. Rather than relying on static scheduling policies, this system treats serving policies as living code, continuously evolving them during deployment to navigate changing runtime dynamics autonomously.

### [CoupleEvo: Evolving Heuristics for Coupled Optimization Problems Using Large Language Models](https://arxiv.org/abs/2605.06341)
**Authors:** Thomas Bömer et al. (2026)
This paper extends LLM heuristic design to tightly coupled, multi-part optimization problems. It introduces and evaluates sequential, iterative, and integrated evolutionary coordination strategies, demonstrating that decomposition-based evolution provides more stable convergence for interdependent subproblems.

### [ParEVO: Synthesizing Code for Irregular Data: High-Performance Parallelism through Agentic Evolution](https://arxiv.org/abs/2603.02510)
**Authors:** Liu Yang et al. (2026)
This framework is designed to synthesize high-performance parallel algorithms for complex, irregular data structures. By combining domain-tuned models, a specialized dataset, and an evolutionary coding agent that iteratively repairs code using feedback from compilers, dynamic race detectors, and performance profilers, ParEVO achieves massive execution speedups that match or outperform state-of-the-art expert human baselines.

## Analysis & Benchmarking

### [What Do Evolutionary Coding Agents Evolve?](https://arxiv.org/abs/2605.20086)
**Authors:** Nico Pelleriti et al. (2026)
This investigation unpacks the actual mechanisms driving score improvements in evolutionary coding agents. By introducing the EvoTrace dataset and EvoReplay methodology, the authors reveal that many benchmark gains stem from a small subset of specific edit types and deterministic cycling patterns rather than purely novel algorithmic structure.

## How to Read and Add to this Repository
To add new research to this collection, create a level-three heading with the paper's title linked to its arXiv or publication page. Follow this with a bolded section for the authors and publication year, and conclude with a brief paragraph summarizing how the paper advances the field of agentic code evolution. Ensure you place the new paper in the most relevant category section above.
