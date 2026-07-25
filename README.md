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

#### 🧠 [Adaptive RAG](https://github.com/yash-dev26/adaptive-rag) &nbsp; [`Live`](https://adaptive-rag-1.vercel.app/)
> A production-oriented RAG system that treats retrieval as a series of decisions, not a fixed pipeline — built with LangGraph orchestration on top of a full-stack, bring-your-own-key architecture.

* **Adaptive Routing:** Designed a heuristic + LLM planner that decides whether a query even needs retrieval, skipping the vector store entirely for chit-chat or general knowledge.
* **CRAG-Style Evaluation:** Built a grading layer that scores retrieved context on relevance (similarity heuristics first, LLM grader as fallback) and routes to *generate*, *rewrite & retry*, or *fall back to general knowledge*.
* **Query Rewriting with RRF:** Implemented single/multi-query rewriting with Reciprocal Rank Fusion for ambiguous, context-dependent questions before they hit the retriever.
* **Cost-Aware Reranking:** Integrated a Cohere reranker that only fires on ambiguous rankings, skipping straight to generation when there's a clear score gap.
* **Semantic + Response Caching:** Engineered a Redis-backed caching layer alongside multi-provider LLM orchestration (OpenAI + Groq) and document-scoped PDF ingestion with duplicate detection.
* **Streaming & History:** Built streaming graph execution with live node-by-node tracing on the frontend, full chat history via MongoDB-backed threads, and a no-login BYOK flow (your API keys, used per-request, never stored).

![Python](https://img.shields.io/badge/-Python-14161A?style=flat-square&logo=python&logoColor=3776AB)
![LangGraph](https://img.shields.io/badge/-LangGraph-14161A?style=flat-square&logo=langchain&logoColor=1C3C3C)
![FastAPI](https://img.shields.io/badge/-FastAPI-14161A?style=flat-square&logo=fastapi&logoColor=009688)
![Qdrant](https://img.shields.io/badge/-Qdrant-14161A?style=flat-square&logo=qdrant&logoColor=DC244C)
![Redis](https://img.shields.io/badge/-Redis-14161A?style=flat-square&logo=redis&logoColor=FF4438)
![MongoDB](https://img.shields.io/badge/-MongoDB-14161A?style=flat-square&logo=mongodb&logoColor=47A248)
![OpenAI](https://img.shields.io/badge/-OpenAI-14161A?style=flat-square&logo=openai&logoColor=FFFFFF)
![Groq](https://img.shields.io/badge/-Groq-14161A?style=flat-square&logo=groq&logoColor=F55036)
![React](https://img.shields.io/badge/-React-14161A?style=flat-square&logo=react&logoColor=61DAFB)

---

#### ⚙️ [AlgoHub](https://github.com/yash-dev26/algohub)
> A distributed, LeetCode-style code judge built on a microservices architecture, capable of securely compiling and executing arbitrary user code across multiple languages at scale.

* **Distributed Microservices:** Architected 4 decoupled services — enqueuer, evaluation, problem management, and WebSocket delivery — each independently scalable and deployable.
* **Secure Execution Sandbox:** Built isolated, Docker-based code execution to safely run untrusted submissions across multiple languages.
* **Async Pipeline & Monitoring:** Implemented an asynchronous evaluation pipeline using BullMQ + Redis, decoupling submission intake from execution.
* **Real-Time Verdicts:** Integrated a dedicated WebSocket service to push live evaluation results to the client — no polling.
* **Modern Interface:** Built a React frontend with an in-browser code editor and Markdown-rendered problem statements.

![Node.js](https://img.shields.io/badge/-Node.js-14161A?style=flat-square&logo=nodedotjs&logoColor=339933)
![Fastify](https://img.shields.io/badge/-Fastify-14161A?style=flat-square&logo=fastify&logoColor=FFFFFF)
![TypeScript](https://img.shields.io/badge/-TypeScript-14161A?style=flat-square&logo=typescript&logoColor=3178C6)
![Docker](https://img.shields.io/badge/-Docker-14161A?style=flat-square&logo=docker&logoColor=2496ED)
![Redis](https://img.shields.io/badge/-Redis-14161A?style=flat-square&logo=redis&logoColor=FF4438)
![MongoDB](https://img.shields.io/badge/-MongoDB-14161A?style=flat-square&logo=mongodb&logoColor=47A248)
![React](https://img.shields.io/badge/-React-14161A?style=flat-square&logo=react&logoColor=61DAFB)

---

## 📌 Currently Exploring

- 🏗 Distributed systems and scalable service architecture
- 📚 Data Structures & Algorithms

---

<div align="center">

**Building scalable backends • Exploring Applied AI • Learning every day**

</div>
