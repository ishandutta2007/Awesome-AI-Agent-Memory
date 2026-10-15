# Awesome-AI-Agent-Memory

## Top AI Agent Memory Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Long-Term Memory, Conversational Memory, Vector Stores & Personalized Agent Context*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Memory**. These systems store, retrieve, and manage short-term and long-term memory for AI agents and assistants—covering conversation history, facts, embeddings, and personalized context.



**Examples** include Zep, Pinecone, Mem0, LangSmith, Langfuse, Weaviate, Qdrant, Chroma, Redis Cloud, and Milvus Managed (the category leaders).



**Open-source emphasis**: Agent memory is highly amenable to open-source solutions. **Mem0**, **Zep**, **Chroma**, **Qdrant**, **Weaviate**, **Milvus**, **Letta**, and related projects enable fully self-hosted, controllable memory layers. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI agent and context memory infrastructure market is estimated at approximately $6.4B to $11.5B (as part of the rapidly growing $180B+ agentic AI trajectory by the mid-2030s, compounding at ~40% CAGR). The market exhibits a bifurcated structure: it is **moderately to highly fragmented** at the developer-tooling and specialized episodic memory layer where agile startups innovate, while remaining **concentrated** at the high-performance vector infrastructure and hyperscaler cloud layers where scale, compute efficiencies, and enterprise compliance create strong competitive moats.

## SaaS/Hosted Platforms

| Platform | Valuation / Size | Starting Pricing | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| [Redis Cloud](https://redis.io/cloud/) | ~$2.0B (Valuation) | $5/month (Essentials plan; scalable RAM) | 30 MB shared DB, 100 ops/sec, 1 DB, free forever | Managed Redis service frequently used for session memory, caching, and low-latency vector search (Redis Search). |
| [LangSmith](https://www.langchain.com/langsmith) | ~$1.25B (LangChain valuation) | $39/seat/month (Plus plan; $2.50/1k extra traces) | 1 seat max, 5,000 base traces/month, 14-day retention, free forever | LangChain’s commercial platform for tracing, evaluation, and dataset management across agent runs. |
| [Pinecone](https://www.pinecone.io/) | ~$750M (Valuation) | $50/month min. usage (Serverless pay-as-you-go) | 2 GB storage (~300k vectors), 2M write units/mo, 1M read units/mo, 5 indexes, AWS us-east-1, free forever | Fully managed serverless vector database widely used as the embedding and retrieval backbone for agent memory. |
| [Qdrant Cloud](https://qdrant.tech/) | ~$350M–$500M (Est. valuation) | ~$80–$130/month (Standard cluster pricing based on vCPU/RAM) | 1 cluster, 0.5 vCPU, 1 GB RAM, 4 GB disk storage, free forever (no credit card required) | Managed offering of the open-source Qdrant vector database, optimized for high-performance similarity search. |
| [Weaviate Cloud](https://weaviate.io/) | ~$200M (Valuation) | $45/month minimum (Flex consumption tier) | 1 sandbox cluster, 100,000 objects, 1 GB RAM, 10 GB disk, 2k embeddings/day, free forever | Managed vector database service with native hybrid search, used for semantic memory and retrieval in agent systems. |
| [Mem0](https://mem0.ai/) | ~$150M (Est. valuation) | $19/month (Starter tier: 50k adds, 5k retrievals) | 10,000 add requests/month, 1,000 retrieval requests/month, 1 project, free forever | Memory layer for personalized AI assistants and agents, offering hosted APIs for long-term user/agent memory. |
| [Zilliz Cloud](https://zilliz.com/) | ~$113M+ (Venture capital raised) | $99/month (Standard dedicated tier; or serverless pay-as-you-go) | 5 GB storage (~1M vectors), 2.5M vCUs/month, 5 collections, free forever (or 30-day $100 credit trial for dedicated) | Managed Milvus vector database service for large-scale embedding storage and retrieval powering agent memory. |
| [Chroma Cloud](https://www.trychroma.com/) | ~$75M (Valuation) | ~$2.50/GiB written + $0.33/GiB-mo storage (Pay-as-you-go) | Up to 1M stored embeddings and introductory developer credits, free forever tier | Hosted variant of Chroma embedding database designed for developer-friendly agent memory backends. |
| [Langfuse](https://langfuse.com/) | Acquired by ClickHouse ($15B valuation; ~$4M seed prior) | $29/month (Core tier; $8 per 100k extra units) | 50,000 events/units per month, unlimited users, free forever | Open-source LLM engineering and observability platform for tracing, evaluation, and analytics of agent memory usage. |
| [Zep](https://www.getzep.com/) | Seed stage / YC (Undisclosed private valuation) | $125/month (Flex plan: 50,000 credits included) | 10,000 credits/month for prototyping, free forever | Long-term memory platform for LLM applications and agents, providing conversation memory and temporal knowledge graphs. |

## Open-Source GitHub Projects

- **[Mem0](https://github.com/mem0ai/mem0)**  

  Open-source memory layer for personalized AI assistants and agents — simple APIs to add, update, search, and manage long-term memory across conversations and users.



- **[Zep](https://github.com/getzep/zep)**  

  Open-source long-term memory store for LLM apps and agents, designed for conversation history, summarization, and fact retrieval.



- **[Letta](https://github.com/letta-ai/letta)**  

  Framework for advanced agents with self-managed long-term memory (MemGPT lineage) — agents actively manage their own context and persistent memory.



- **[Chroma](https://github.com/chroma-core/chroma)**  

  Open-source embedding database designed for AI applications; lightweight and popular as a local or self-hosted memory/vector store.



- **[Qdrant](https://github.com/qdrant/qdrant)**  

  High-performance open-source vector database written in Rust, widely used for semantic search and agent memory backends.



- **[Weaviate](https://github.com/weaviate/weaviate)**  

  Open-source vector database with strong hybrid search, modules, and GraphQL APIs suitable for agent knowledge and memory.



- **[Milvus](https://github.com/milvus-io/milvus)**  

  Open-source vector database built for scalable similarity search; commonly paired with agents for large-scale embedding memory.



- **[LangGraph](https://github.com/langchain-ai/langgraph)**  

  Stateful agent orchestration framework with checkpointing and memory patterns for durable, multi-step agent runs.



- **[LlamaIndex Memory modules](https://github.com/run-llama/llama_index)**  

  Memory and chat-store abstractions within LlamaIndex for building context-aware and retrieval-augmented agents.



- **[Documentation and memory architecture guides](https://docs.mem0.ai/)**  

  Official docs and community resources for designing short-term, long-term, and hybrid memory systems with open tools.



### Additional Strong Open-Source Options

- Using **Mem0** or **Zep** as dedicated long-term memory layers on top of any agent framework.

- Storing embeddings and knowledge in **Chroma**, **Qdrant**, **Weaviate**, or **Milvus**.

- Building self-managing memory agents with **Letta**.

- Combining **LangGraph** checkpointing for session state with external vector stores for persistent facts.

- Accepting that managed services (Pinecone, Zilliz, Redis Cloud, Mem0 Cloud, LangSmith, etc.) still lead in operational simplicity, scaling, and SLAs.



**Frameworks for building custom systems**: Add **Mem0** or **Zep** for conversational/long-term memory → back embeddings with **Qdrant** / **Chroma** / **Weaviate** / **Milvus** → orchestrate agents with **LangGraph** or **Letta**. Suitable for teams that need full data ownership and customization. Many production systems still use managed vector and memory services for reliability.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent memory systems store user conversations and personal data. Implement encryption, access control, retention policies, and privacy compliance. This list is not security or legal advice.



---

**Made for AI engineers, agent builders, and open-memory advocates.**

Let's keep agent memory powerful, private, and as open as practical.
