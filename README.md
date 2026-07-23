<div align="center">

Engineer working in AI systems, backend infrastructure, and applied research

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lionel-arce/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lzvxck)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000)](https://huggingface.co/Lzvick)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lioarce1@gmail.com)

</div>

---

## Working on

**[trust-gate](https://github.com/lzvxck/trust-gate)** `TypeScript`
Trajectory-aware regression gate for autonomous coding agents. Open-source and self-hostable: Fastify API, Next.js dashboard, MCP server via xmcp, BullMQ/Redis workers, and Postgres with Drizzle. Ships a reusable GitHub Actions check ([trust-gate-demo](https://github.com/lzvxck/trust-gate-demo)) to gate agent-generated PRs end-to-end.

---

**[agent-arena](https://github.com/lzvxck/agent-arena)** `Python`
Benchmarking platform for autonomous coding agents. Define benchmarks and tasks, run agents in isolated git workspaces, and stream every event live over WebSocket. Trace viewer replays full executions — tool calls, file diffs, stdout/stderr, and token usage with cost breakdown. Claude Code adapter first, extensible to any agent.

---

**[chainforge](https://github.com/lzvxck/chainforge)** `Go`
Provider-agnostic AI agent framework with zero external dependencies. Sequential, parallel, and router-based orchestration. MCP (HTTP + stdio), vector memory (Qdrant, PostgreSQL, Redis), tool memoization, Prometheus metrics, and OpenTelemetry tracing. Swap Anthropic, OpenAI, Ollama, or Gemini with one line.

---

**[dense-retrieval-ft](https://github.com/lzvxck/dense-retrieval-ft)** `Python`
Fine-tuned BGE-M3 with LoRA for domain-specific dense retrieval on a single consumer GPU. Synthetic query generation and hard-negative mining pipeline, contrastive training, and retrieval evaluation against the base model.

---

**[etip](https://github.com/lzvxck/etip)** `Python · TypeScript`
Enterprise Talent Intelligence Platform. Ingests GitHub and Jira activity, infers skills against the ESCO taxonomy, and ranks candidates via vector similarity + cross-encoder reranking + LLM explanations. Multi-tenant with PostgreSQL Row-Level Security, pgvector, Celery workers, and Qdrant.

---

**[websearch-ng](https://github.com/lzvxck/websearch-ng)** `Python · TypeScript`
Self-hosted AI search engine. Parallel web search, Jina extraction, semantic reranking, and cited answers streamed token-by-token over SSE. Two modes: fast search (3 queries) and deep research (7 queries + gap analysis + structured report). Multi-provider via LiteLLM.

---

**[gpt-sota-opt](https://github.com/lzvxck/gpt-sota-opt)** `Python`
Production GPT implementation with GQA (25–30% faster inference, 66% smaller KV cache), FlashAttention-2, RMSNorm, SwiGLU, and RoPE. Scales from 10M to 500M parameters. 6,000–7,000 tokens/sec on RTX 5070 with BF16 and gradient checkpointing.

---

**[turboquant-implementation](https://github.com/lzvxck/turboquant-implementation)** `Python`
TurboQuant KV cache compression — 4× size reduction with near-zero quality loss. RHT + Lloyd-Max quantization encoded at 3–4 bits. Custom Triton GPU kernels: ~9× faster quantization, ~5× faster dequantization. Validated on Llama-3.2-3B: +2.2% perplexity, 100% needle accuracy.

---

**[rl-framework-qwen3.5-2B](https://github.com/lzvxck/rl-framework-qwen3.5-2B)** `Python`
Full SFT + GRPO reinforcement learning pipeline for reasoning on Qwen3.5-2B. QLoRA 4-bit quantization fits on 12GB VRAM. Self-improvement loop: generates reasoning traces, filters top performers, augments the dataset, and repeats. Evaluated on math and code benchmarks with structured `<think>` chain-of-thought.

---

**[autonomous-sae-researcher](https://github.com/lzvxck/autonomous-sae-researcher)** `Python`
Autonomous hyperparameter search for Sparse Autoencoders on Qwen3.5-0.8B activations. Agent forms hypotheses, runs training cycles, logs to SQLite, and generates its own leaderboard and state summary for the next iteration. Best result: 0.9956 explained variance at 12.5% feature activation.

---

**[marl-drone-swarm-rl](https://github.com/lzvxck/marl-drone-swarm-rl)** `Python`
Multi-agent reinforcement learning for cooperative quadcopter swarm control. MAPPO with centralized critic and shared actor. Curriculum learning from 3 drones on 10×10 grids to 6 drones on 20×20. Physics simulation via PyBullet, PettingZoo multi-agent wrapper.

---

**[data-curation-engine](https://github.com/lzvxck/data-curation-engine)** `Python`
LLM-powered pipeline that converts raw documents (PDF, DOCX, HTML, Markdown, source code) into training-ready JSONL datasets. Six-stage pipeline: parse → chunk → generate instructions → rule filter → LLM judge (position-swap bias detection) → output. Multi-provider via LiteLLM. Resumable.

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000)
![LiteLLM](https://img.shields.io/badge/LiteLLM-7C3AED?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Triton](https://img.shields.io/badge/Triton-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

---

## GitHub

<div align="center">
  <img src="https://streak-stats.demolab.com?user=lzvxck&theme=tokyonight&hide_border=true&background=0D1117&stroke=38BDF8&ring=38BDF8&fire=FF6B6B&currStreakLabel=38BDF8" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=lzvxck&theme=tokyo-night&bg_color=0D1117&color=38BDF8&line=FF6B6B&point=FFFFFF&area=true&hide_border=true" alt="Contribution Graph" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=lzvxck&style=flat-square&color=38BDF8" alt="Profile Views"/>
</div>
