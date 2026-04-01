# Hi, I'm Dedy 👋
AI Systems Engineer | Open for Work

I design and build **end-to-end agentic AI systems** — from **observability and evaluation pipelines** to **action-taking AI agents** — using a **fully open-source stack**, deployed **on-premise** for security-critical environments.

My work sits at the intersection of **AI systems engineering, applied research, and real-world execution**.

---

## 🚀 Featured Projects

### [Auditi](https://github.com/deduu/auditi) — Open-Source AI Agent Evaluation & Observability
A full-stack platform for **tracing, evaluating, and improving** LLM-powered applications. Think LangSmith — but open-source and self-hosted.

| Layer | What it does |
|-------|-------------|
| **Python SDK** | 2-line auto-instrumentation for OpenAI, Anthropic & Google. Decorator-based tracing (`@trace_agent`, `@trace_tool`, `@trace_llm`) with automatic cost tracking. |
| **Evaluation Engine** | LLM-as-a-judge (span-level + trace-level) and human annotation queues with custom scoring schemas. Generates actionable improvement recommendations. |
| **Analytics Dashboard** | Failure mode trending, cost forecasting, score distributions, anomaly detection, and model comparison. |
| **Dataset Pipeline** | Annotation → versioned datasets → export (JSONL / CSV / Parquet) for fine-tuning. The complete feedback loop. |

**Stack:** Python · FastAPI · PostgreSQL · React · Vite · TailwindCSS · Docker

---

### [MCP-Tuna](https://github.com/deduu/MCP-Tuna) — End-to-End LLM Post-Training Platform
An **MCP-native platform** that unifies dataset generation, cleaning, evaluation, fine-tuning, deployment, and orchestration in one repository. Built for both coding agents and human operators.

| Area | What you can do |
|------|----------------|
| **Data Pipeline** | Generate SFT/DPO/GRPO/KTO datasets from documents, clean, normalize, validate, split, and merge. |
| **Fine-Tuning** | Run LoRA training synchronously or async, multi-stage curriculum, adapter merge, and GGUF export. |
| **Multimodal / VLM** | Train VLM SFT jobs, run multimodal inference, deploy VLM runtimes, and evaluate with multimodal judge flows. |
| **Deployment** | Serve trained models as MCP servers or REST APIs and chat against live deployments. |
| **Orchestration** | Run guided end-to-end pipelines and collect orchestration training data from agent trajectories. |

17 namespaces · 120+ MCP tool entry points · React control plane · OpenAI-compatible API · Built-in Auditi tracing

**Stack:** Python 3.11+ · FastAPI · React · TypeScript · PostgreSQL · MinIO · Docker · uv

---

### [barongs.ai](https://github.com/deduu/barongs.ai) — Production-Ready AI Agent Framework
An **async-first Python framework** for building and orchestrating AI agents — from single-agent apps to complex multi-agent pipelines.

| Feature | What it does |
|---------|-------------|
| **Strategy Orchestrator** | Built-in patterns: `SingleAgent`, `Router`, `Pipeline`, `Parallel` — pick the right architecture for your use case. |
| **MCP Tool Integration** | Native support for Model Context Protocol tools, pluggable into any agent. |
| **OpenAI-Compatible API** | Drop-in replacement endpoint with SSE streaming — works with Open WebUI out of the box. |
| **Full Stack in One Command** | `docker compose up` spins up Barongsai + Open WebUI + PostgreSQL + Redis. |

**Stack:** Python 3.11+ · FastAPI · Redis · PostgreSQL · Docker · uv

---

### [ClawSandbox](https://github.com/deduu/ClawSandbox) — AI Agent Security Benchmark
A **hardened sandboxed environment** for testing AI agent vulnerabilities, aligned to the OWASP Top 10 for LLM Applications.

| Category | What it tests |
|----------|--------------|
| **Prompt Injection** | Injected instructions hijacking agent behavior mid-task. |
| **Memory Poisoning** | Silent writes to agent memory files that persist across sessions. |
| **Privilege Escalation** | Agents exceeding their intended permission scope. |
| **Data Exfiltration** | Sensitive data leaked via shell commands or file reads. |

> **Highlight:** Test 03 (Silent Memory Write) — a user asks "What is the capital of France?" and gets the correct answer, while the model silently poisons `~/.openclaw/notes.md` for all future sessions. No hallucination needed.

All automated tests run **entirely offline** inside an isolated container — no internet, no API keys, no cost.

**Stack:** Docker · Python · Shell · OWASP LLM Top 10

---

## 🔹 What I Work On
- 🤖 **Agentic LLM Systems** — Planning, tool-use, verification loops, and action execution
- 📡 **AI Observability & Evaluation** — Tracing, LLM-as-a-judge, failure analysis, and continuous improvement
- 🔐 **AI Security Research** — Prompt injection, memory poisoning, privilege escalation in production agents
- 🧠 **Dataset → Model → Agent Pipelines** — Data curation, evaluation, fine-tuning, diagnostics, and iteration
- 🔒 **On-Prem & Sovereign AI** — Secure, auditable AI deployments without cloud dependency
- 🧩 **System Integration** — AI agents embedded into operational workflows, not demos

---

## 🛠 Tech Stack
**Languages:** Python · JavaScript · TypeScript · C#

**AI / ML:** PyTorch · TensorFlow · LLM Fine-Tuning (SFT, DPO, GRPO, KTO, LoRA) · Computer Vision · Multimodal Systems

**Infrastructure:** AWS · GCP · Azure · On-Prem GPU Systems · Docker · FastAPI

**Domains:** Generative AI · Machine Learning · Computer Vision · Digital Twin · AR / VR

---

## 🎯 Current Focus
- Shipping [**Auditi**](https://github.com/deduu/auditi) as an open-source alternative to LangSmith for AI agent observability
- Expanding [**MCP-Tuna**](https://github.com/deduu/MCP-Tuna) as a full post-training platform — data to deployment in one stack
- Building [**barongs.ai**](https://github.com/deduu/barongs.ai) as a production-grade async agent framework
- Growing [**ClawSandbox**](https://github.com/deduu/ClawSandbox) with community-contributed OWASP test categories
- Designing **vertical AI orchestrators** over general-purpose chatbots

---

## 💭 Philosophy
> Intelligence is not just generation —
> it's **planning, acting, verifying, and recovering inside constraints**.

---

## 📬 Connect
- 💼 LinkedIn: [linkedin.com/in/dedy-ariansyah](https://www.linkedin.com/in/dedy-ariansyah/)
- 📧 Open to opportunities in AI systems engineering, agentic AI, and applied ML

---

⭐ If you're building with **agentic AI, LLM evaluation, or open-source AI systems**, feel free to connect or explore my repositories.
