<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:020617&height=200&section=header&text=Mohammed%20Khan&fontSize=50&fontColor=ffffff&fontAlignY=45&animation=fadeIn" width="100%"/>

<br/>

## AI Systems Engineer · Full-Stack Developer · Open Source Builder

Building production-grade AI and ML systems that solve real-world problems

<br/>

<p>
<a href="https://react.dev"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/></a>
<a href="https://nextjs.org"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/></a>
<a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/></a>
<a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
<a href="https://fastapi.tiangolo.com"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/></a>
</p>

<p>
<a href="https://www.tensorflow.org"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/></a>
<a href="https://pytorch.org"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/></a>
<a href="https://www.docker.com"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/></a>
<a href="https://www.postgresql.org"><img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/></a>
<a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/></a>
</p>

<p>
<a href="https://github.com/sup3rus3r?tab=followers"><img src="https://img.shields.io/github/followers/sup3rus3r?style=social"/></a>
<a href="https://www.linkedin.com/in/mohammed-khan-aa535597"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://www.mokhan.co.za"><img src="https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge"/></a>
</p>

</div>

---

## About Me

I'm an independent developer specializing in **AI systems architecture**, **machine learning platforms**, and **RL optimization frameworks**. My focus is building production-ready systems that solve real-world problems through intelligent design and robust engineering.

---

## Featured Projects

### Obsidian Networks
**AI-powered machine learning scaffolding platform**

The fastest path from raw data to production ML models. Describe your problem and upload data—the platform generates complete, research-backed TensorFlow/Keras implementations automatically.

**Features:**
- **No ML expertise required** - Natural language problem description
- **Research-grounded** - Queries arXiv for recent relevant papers before code generation
- **End-to-end pipeline** - From CSV upload to trained `.pt` export in a single session
- **Live training insights** - Real-time metrics via Server-Sent Events  
- **Reinforcement learning support** - Full RL agents with Gymnasium environments
- **Docker sandboxing** - Isolated, secure training environments
- **Multi-LLM support** - Works with OpenAI, Anthropic, or local LMs via LMStudio

**Tech stack:** Python (FastAPI, TensorFlow, Celery) + React/TypeScript + Docker

**[View >>](https://github.com/sup3rus3r/obsidian-networks)**

---

### Tensor Optix
**Self-evolving autonomous learning loop for TensorFlow RL agents**

Replace your training loop with an autonomous optimization system that continuously evolves policies, tunes hyperparameters, and detects plateaus automatically. Perfect for RL problems in trading, robotics, game AI, and adaptive control.

**Core capabilities:**
- **Autonomous training loop** - Continuous stepping with no fixed episode count; system detects convergence
- **Intelligent backoff scheduling** - ACTIVE → COOLING → DORMANT state machine with exponential backoff
- **Hyperparameter tuning** - Two-phase finite difference estimation adapts parameters in real-time
- **Checkpoint management** - Automatic rollback to best-known policies on degradation
- **Ensemble support** - Run multiple agents simultaneously as weighted ensemble for non-stationary environments
- **Custom agents & evaluators** - Subclass for PPO, SAC, DQN, or any RL algorithm
- **Live pipelines** - Stream real-time data (financial markets, sensor feeds) as training data

**Key algorithms:**
- `BackoffOptimizer` — Two-phase finite difference with adaptive perturbation
- `PBTOptimizer` — Pseudo population-based training with history-based selection
- `PolicyManager` — Evolution tracking, rollback, and ensemble weighting

**Perfect for:** Trading bots, game AI, robot control, portfolio optimization, multi-agent systems

**[View >> ](https://github.com/sup3rus3r/tensor-optix)** | **[PyPI Package >>](https://pypi.org/project/tensor-optix/)**

---

### Obsidian AI
**Visual platform for building and orchestrating AI agents**

Enterprise-grade agent orchestration without the boilerplate. Build multi-agent teams, define complex workflows, and manage evaluations entirely through a visual interface—no SDKs, no glue code.

**Key capabilities:**
- **Visual orchestration** - Drag-and-drop agent teams, sequential pipelines, parallel DAG workflows
- **No vendor lock-in** - Swap providers (OpenAI → Anthropic → Ollama) instantly without reconfiguring agents
- **Production security** - JWT auth, TOTP 2FA, AES end-to-end encryption, secrets vault, RBAC, rate limiting
- **MCP-native** - First-class Model Context Protocol support for external tool integration
- **Self-hosted & open-source** - Complete data ownership; runs entirely on your infrastructure
- **Sandbox integration** - Isolated containers for safe code execution within agent workflows
- **Evaluation pipelines** - Built-in testing and metrics for agent performance
- **Human-in-the-loop** - Review, refine, and approve agent decisions at every stage

**Tech stack:** Python (FastAPI) + React/TypeScript + PostgreSQL + Docker

**[View >>](https://github.com/sup3rus3r/obsidian-ai)**

---

## Philosophy

**Problem-first:** Every project starts with a real-world constraint that existing solutions don't address.

**User empathy:** Tools succeed when they reduce friction. I obsess over UX for both end-users and developers.

**Production focus:** Systems must be deployable, maintainable, and performant at scale. Security and observability are non-negotiable.

**Open by default:** Code and architecture benefit from transparency. Most of my work is open-source.

---

## Technical Stack

**Frontend:** React, Next.js, TypeScript, Tailwind CSS, HTML/CSS  
**Backend:** Python (FastAPI), Node.js, PostgreSQL, MongoDB  
**AI/ML:** TensorFlow, Keras, Gymnasium, LangChain, LLM integrations (OpenAI, Anthropic, Ollama)  
**Infrastructure:** Docker, Docker Compose, Celery, Redis, Server-Sent Events  
**Advanced:** RL optimization, hyperparameter tuning, policy evolution, ensemble methods  

---

## Let's Connect

I'm always interested in collaborating on AI systems, ML infrastructure, or interesting technical challenges.

<div align="center">

[**Website**](https://www.mokhan.co.za) · [**LinkedIn**](https://www.linkedin.com/in/mohammed-khan-aa535597) · [**GitHub**](https://github.com/sup3rus3r)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a3e,100:0f0f23&height=80&section=footer" width="100%"/>

Building systems at the intersection of **AI, machine learning, and software engineering**

</div>
