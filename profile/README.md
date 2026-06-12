# EDOS Engineering

**Enterprise DevOps Solutions** — software consultancy turning hard delivery problems into repeatable systems.

We are a small, senior team with over a century of combined experience in software development and delivery. We build what works, ship it, and stand behind it. Our practice spans release engineering, security, observability, and — increasingly — agentic software systems.

---

## What We Build

### [Orkestera](https://github.com/EDOS-Engineering/Orkestera)

Our flagship product and the current center of our R&D effort. Orkestera is a **proactive, dark-factory agentic development engine** — a full workflow management suite for orchestrating LLM agent swarms at scale.

At its core, Orkestera runs a competitive multi-engineer swarm workflow where parallel agents score against each other until work meets a pass threshold. No human in the loop. A human near the loop; no babysitting. Just working software.

**Architecture:**

| Service | Role |
|---|---|
| **Platform** | Agent orchestration: Executive, Judge, Architects, Engineers, SWABench |
| **Auth** | OAuth 2.1 server with PKCE, client credentials, token rotation |
| **Hive** | MongoDB 8 document store — central data layer |
| **Watch** | Deep observability: event ingestion, sprint board, log explorer, inference view |
| **Core** | Ops portal: health dashboard, config, user management, throughput charts |
| **LLMProxy** | Dynamic inference router — Anthropic, OpenAI-compatible, Ollama, llama.cpp |

Orkestera is provider-agnostic, deployable on-premise or in the cloud, and built on Elixir/Phoenix with TLS on every service boundary.

### [SWABench](https://github.com/EDOS-Engineering/SWABench)

The proprietary competitive-swarm benchmark workflow powering Orkestera's quality engine. Agents compete in parallel; the highest scorer wins the iteration. Work continues until the score reaches 100% or the pass threshold holds for four consecutive rounds.

### [LLMProxy](https://github.com/EDOS-Engineering/LLMProxy)

Lightweight dynamic inference router. Routes to any LLM provider — Anthropic, OpenAI-compatible APIs, Ollama, llama.cpp — with a unified interface.

### [Eel](https://github.com/EDOS-Engineering/Eel)

Agent fleet orchestration tooling.

---

## Our History

EDOS started as a software delivery consultancy with a single operating principle: **ship things that work, or don't ship them.**

We spent years helping engineering teams at scale — release pipelines, distributed systems, security posture, observability stacks. We absorbed pressure so client teams didn't have to. We wrote the playbooks. We carried the pagers.

When LLMs became capable enough to serve as genuine engineering collaborators, we turned our delivery methodology into software. Orkestera is the result: a dark-factory development engine built on the same discipline we applied to our consulting work, now automated and scalable.

---

## Philosophy

- **Rigor over speed.** Fast is good. Correct is better. We build both in.
- **Dark factory default.** Minimal human intervention. Automation handles the loop; humans set direction and approve results.
- **Provider agnostic.** No lock-in. Swap the model, keep the workflow.
- **Security first.** TLS everywhere. AES-256-GCM at rest. 2FA required across the organization.

---

## Team

Small team. Deep experience. 100+ years of combined software delivery.

📬 [travis@edos.io](mailto:travis@edos.io)  
🌐 [edos.io](https://edos.io)
