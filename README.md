<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,100:1a1a2e&height=200&section=header&text=Yashwardhan%20Singh&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%7C%20Applied%20AI&descColor=a0a0b0&descAlignY=58&animation=fadeIn" width="100%"/>

</div>

---

<div align="center">

```
  crafting backends that scale  ·  wiring AI that thinks  ·  decent at the frontend too
```

</div>

---

### 👋 About Me

Hey, I'm **Yashwardhan**, a backend engineer who loves building real things with AI.

Most of my time goes into designing scalable backend systems with **Node.js** and **Express**, and exploring the applied AI space particularly **RAG pipelines**, **LangGraph agents**, and anything that makes LLMs actually useful in production. I can hold my own on the frontend with **React** when needed.

- 🧠 Currently deep in **LangGraph**, **RAG**, and agentic workflows
- 🔧 Love clean layered architecture and production-grade patterns

---

### 🛠️ Tech Stack

#### Languages
![Python](https://img.shields.io/badge/Python-14161A?style=for-the-badge&logo=python&logoColor=3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-14161A?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-14161A?style=for-the-badge&logo=typescript&logoColor=3178C6)

#### Backend & Infra
![Node.js](https://img.shields.io/badge/Node.js-14161A?style=for-the-badge&logo=nodedotjs&logoColor=339933)
![Express.js](https://img.shields.io/badge/Express.js-14161A?style=for-the-badge&logo=express&logoColor=ffffff)
![FastAPI](https://img.shields.io/badge/FastAPI-14161A?style=for-the-badge&logo=fastapi&logoColor=009688)
![MongoDB](https://img.shields.io/badge/MongoDB-14161A?style=for-the-badge&logo=mongodb&logoColor=47A248)

#### Applied AI
![LangGraph](https://img.shields.io/badge/LangGraph-14161A?style=for-the-badge&logo=langchain&logoColor=1C3C3C)
![LangChain](https://img.shields.io/badge/LangChain-14161A?style=for-the-badge&logo=langchain&logoColor=1C3C3C)
![OpenAI](https://img.shields.io/badge/OpenAI-14161A?style=for-the-badge&logo=openai&logoColor=ffffff)
![Qdrant](https://img.shields.io/badge/Qdrant-14161A?style=for-the-badge&logo=qdrant&logoColor=DC244C)

#### Frontend
![React](https://img.shields.io/badge/React-14161A?style=for-the-badge&logo=react&logoColor=61DAFB)

---

### 📌 Featured Projects

---

#### ⚙️ [AlgoHub](https://github.com/yash-dev26/algohub)
> A full-scale distributed code submission and evaluation platform — think LeetCode, built from scratch. Users submit code, it gets queued, executed inside isolated Docker containers per language, validated against test cases, and results are pushed back in real time via WebSockets.

- **4 microservices**: Enqueuer · Evaluation · Problem · WebSocket
- **BullMQ + Redis** queue for async submission processing
- **Docker-isolated execution** for Python, Java, and C++ (strategy pattern per language)
- **Real-time result delivery** via WebSocket service to the React frontend
- Clean layered architecture in TypeScript across all services

![TypeScript](https://img.shields.io/badge/-TypeScript-14161A?style=flat-square&logo=typescript&logoColor=3178C6)
![Node.js](https://img.shields.io/badge/-Node.js-14161A?style=flat-square&logo=nodedotjs&logoColor=339933)
![Redis](https://img.shields.io/badge/-Redis-14161A?style=flat-square&logo=redis&logoColor=FF4438)
![Docker](https://img.shields.io/badge/-Docker-14161A?style=flat-square&logo=docker&logoColor=2496ED)
![React](https://img.shields.io/badge/-React-14161A?style=flat-square&logo=react&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/-MongoDB-14161A?style=flat-square&logo=mongodb&logoColor=47A248)

---

#### 🧠 [Adaptive RAG](https://github.com/yash-dev26/adaptive-rag) &nbsp; `WIP`
> An intelligent RAG system that routes queries through a LangGraph agent — deciding whether to retrieve from a vector store, rewrite the query, rerank results, or just answer directly with an LLM.

- **Planner node** classifies intent and routes accordingly
- **Multi/Single query rewrite** for better retrieval coverage
- **Reranking layer** before generation for precision
- Built on **FastAPI + LangGraph + Qdrant + OpenAI**

![Python](https://img.shields.io/badge/-Python-14161A?style=flat-square&logo=python&logoColor=3776AB)
![LangGraph](https://img.shields.io/badge/-LangGraph-14161A?style=flat-square&logo=langchain&logoColor=1C3C3C)
![FastAPI](https://img.shields.io/badge/-FastAPI-14161A?style=flat-square&logo=fastapi&logoColor=009688)
![Qdrant](https://img.shields.io/badge/-Qdrant-14161A?style=flat-square&logo=qdrant&logoColor=DC244C)

---

#### 🤖 [LangGraph Checkpointer Support](https://github.com/yash-dev26/langgraph-checkpointer-support)
> A stateful AI support agent built with LangGraph that can pause mid-conversation, persist state to MongoDB, and resume once a human support agent provides input.

- **Human-in-the-loop** escalation via LangGraph interrupts
- **MongoDB checkpointing** for persistent, thread-based sessions
- Clean role separation: `app.py` (user) · `support.py` (agent) · `graph.py` (AI logic)
- Streaming responses with graceful interrupt handling

![Python](https://img.shields.io/badge/-Python-14161A?style=flat-square&logo=python&logoColor=3776AB)
![LangGraph](https://img.shields.io/badge/-LangGraph-14161A?style=flat-square&logo=langchain&logoColor=1C3C3C)
![MongoDB](https://img.shields.io/badge/-MongoDB-14161A?style=flat-square&logo=mongodb&logoColor=47A248)
![OpenAI](https://img.shields.io/badge/-OpenAI-14161A?style=flat-square&logo=openai&logoColor=ffffff)

---

#### 🔐 [Scalable Auth Service](https://github.com/yash-dev26/scalable-auth-service)
> A production-ready authentication microservice in Node.js + Express with full JWT flows, multi-device session management, OTP email verification, and Argon2 password hashing.

- **JWT** Access + Refresh token rotation with HTTP-only cookies
- **Multi-device session** tracking and revocation (logout single / all)
- **OTP email flow** for registration and password reset
- **Rate limiting** on sensitive routes + Argon2 hashing throughout
- Clean layered architecture: `Routes → Controller → Service → Repository → DB`

![Node.js](https://img.shields.io/badge/-Node.js-14161A?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express](https://img.shields.io/badge/-Express-14161A?style=flat-square&logo=express&logoColor=ffffff)
![MongoDB](https://img.shields.io/badge/-MongoDB-14161A?style=flat-square&logo=mongodb&logoColor=47A248)
![JWT](https://img.shields.io/badge/-JWT-14161A?style=flat-square&logo=jsonwebtokens&logoColor=ffffff)

---

### 🌐 Find Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-yash--dev26-14161A?style=for-the-badge&logo=github&logoColor=ffffff)](https://github.com/yash-dev26)
[![Twitter](https://img.shields.io/badge/Twitter-@SinghGeekjs-14161A?style=for-the-badge&logo=x&logoColor=ffffff)](https://twitter.com/SinghGeekjs)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0f0f0f&height=100&section=footer" width="100%"/>

</div>
