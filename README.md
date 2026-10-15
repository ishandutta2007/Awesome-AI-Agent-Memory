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

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Zep](https://www.getzep.com/)**  

  Long-term memory platform for LLM applications and agents, providing conversation memory, fact extraction, and retrieval APIs (with open-source components).



- **[Pinecone](https://www.pinecone.io/)**  

  Fully managed vector database widely used as the embedding and retrieval backbone for agent memory and RAG systems.



- **[Mem0](https://mem0.ai/)**  

  Memory layer for personalized AI assistants and agents, offering hosted APIs for adding, searching, and managing long-term user/agent memory.



- **[LangSmith](https://www.langchain.com/langsmith)**  

  LangChain’s commercial platform for tracing, evaluation, and dataset management; often used alongside memory stores for full agent observability.



- **[Langfuse](https://langfuse.com/)**  

  LLM engineering platform (open-source core with cloud offering) for tracing, evaluation, and analytics of agent runs and memory usage.



- **[Weaviate Cloud](https://weaviate.io/)**  

  Managed vector database service based on the open-source Weaviate project, used for semantic memory and retrieval in agent systems.



- **[Qdrant Cloud](https://qdrant.tech/)**  

  Managed offering of the open-source Qdrant vector database, popular for high-performance similarity search and agent memory backends.



- **[Chroma Cloud / hosted options](https://www.trychroma.com/)**  

  Hosted variants and enterprise support around the open-source Chroma embedding database commonly used for agent and RAG memory.



- **[Redis Cloud](https://redis.io/cloud/)**  

  Managed Redis service frequently used for session memory, caching, and vector search (Redis Search / Redis Vector) in agent architectures.



- **[Milvus Managed / Zilliz Cloud](https://zilliz.com/)**  

  Managed Milvus vector database service for large-scale embedding storage and retrieval powering agent memory systems.



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
