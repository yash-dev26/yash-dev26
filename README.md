<div align="center">

# Hi, I'm Yashwardhan Singh 👋

### Backend Engineer • Applied AI • 3rd Year B.Tech IT Student

📍 Delhi NCR, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashwardhan-singh-a5191a330)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/SinghGeekjs)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yash.pvt2601@gmail.com)

</div>

---

## 🚀 About Me

I build **production-oriented backend systems** and **Applied AI applications**.

My focus areas are **distributed backend architecture**, **RAG pipelines**, **LLM agents/orchestration**, and designing software that is production-ready rather than just functional.

---

## 🛠 Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Applied AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)

**Databases & Infra**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## 💻 Featured Projects

### 🧠 [Adaptive RAG](https://adaptive-rag-1.vercel.app/)

A **production-oriented RAG system** that treats retrieval as a series of decisions, not a fixed pipeline — built with LangGraph orchestration on top of a full-stack, bring-your-own-key architecture.

- **Adaptive routing**: a heuristic + LLM planner decides whether a query even needs retrieval, skipping the vector store entirely for chit-chat or general knowledge.
- **CRAG-style evaluation**: retrieved context is graded on relevance (similarity heuristics first, LLM grader as fallback) and routed to *generate*, *rewrite & retry*, or *fall back to general knowledge*.
- **Query rewriting with RRF** for ambiguous, context-dependent questions before they ever hit the retriever.
- **Cost-aware reranking**: only ambiguous rankings get sent to a Cohere reranker; a clear score gap skips straight to generation.
- **Semantic + response caching** via Redis, multi-provider LLM orchestration (OpenAI + Groq), and document-scoped PDF ingestion with duplicate detection.
- Streaming graph execution with live node-by-node tracing on the frontend, full chat history with MongoDB-backed threads, and a no-login BYOK flow (your API keys, used per-request, never stored).

**Tech:** `Python` `FastAPI` `LangGraph` `LangChain` `Qdrant` `Redis` `MongoDB` `OpenAI` `Groq` `Cohere` `React` `Vite`

---

### ⚙️ AlgoHub

A **distributed, LeetCode-style code judge** built on a microservices architecture, capable of securely compiling and executing arbitrary user code across multiple languages at scale.

- **4 decoupled services** — enqueuer, evaluation, problem management, and WebSocket delivery — each independently scalable and deployable.
- **Isolated Docker-based code execution** to safely run untrusted submissions.
- **Asynchronous evaluation pipeline** using BullMQ + Redis, decoupling submission intake from execution.
- **Real-time verdicts** pushed to clients over WebSockets — no polling.
- React frontend with an in-browser code editor and Markdown-rendered problem statements.

**Tech:** `Node.js` `Fastify` `TypeScript` `Docker` `Redis` `MongoDB` `React`

---

## 📌 Currently Exploring

- 🏗 Distributed systems and scalable service architecture
- 📚 Data Structures & Algorithms

---

<div align="center">

**Building scalable backends • Exploring Applied AI • Learning every day**

</div>
