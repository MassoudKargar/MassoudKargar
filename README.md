<div align="center">

# Hi, I'm Massoud Kargar 👋

### Senior .NET Backend Developer & AI Engineer

*Building scalable, distributed, and intelligent backend systems with 6+ years of software engineering experience*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/masoudkargar)
[![Resume](https://img.shields.io/badge/Resume-DC3545?style=for-the-badge\&logo=adobeacrobatreader\&logoColor=white)](https://raw.githubusercontent.com/MassoudKargar/MassoudKargar/main/resume.pdf)
[![Website](https://img.shields.io/badge/Website-1A56A0?style=for-the-badge\&logo=googlechrome\&logoColor=white)](https://masoudkargar.com)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=for-the-badge\&logo=blogger\&logoColor=white)](https://massoudkargar.ir)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge\&logo=telegram\&logoColor=white)](https://t.me/Masoud_kargar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:massoudkargar.web@gmail.com)

</div>

---

## 🧑‍💻 About Me

I'm a **Senior .NET Backend Developer & AI Engineer** focused on designing and building **scalable, distributed, high-performance, and AI-powered backend systems**.

With 6+ years of software engineering experience, I've worked across startups and enterprise environments, building production APIs, distributed systems, microservices, data-intensive applications, and AI-powered services.

My current focus is at the intersection of **Backend Engineering and AI Engineering** — building systems that combine modern backend architecture with LLMs, RAG, vector search, embeddings, and intelligent data retrieval.

* 🔭  Currently focused on **AI Engineering**, **RAG**, **LLM Applications**, **Microservices**, and **Event-Driven Systems**
* 🤖  Experienced in building **Retrieval-Augmented Generation (RAG)** systems
* 🧠  Experienced with **LLM integration, prompt engineering, embeddings, semantic search, and vector databases**
* 🔎  Experienced in building **semantic retrieval pipelines** using embeddings and vector search
* 🗃️  Experienced with **ChromaDB** and vector-based document retrieval
* 🔌  Experienced in integrating **OpenAI, OpenRouter, and OpenAI-compatible APIs**
* 🇮🇷  Worked with **Persian/Farsi embedding models** and local embedding services
* ⚡  Experienced in designing AI services with **streaming and non-streaming inference**
* 🏗️  Strong background in **.NET, Microservices, Clean Architecture, CQRS, and DDD**
* 🐍  Currently expanding my AI/ML stack with **Python**
* 🦀  Currently exploring **Rust**
* 🌍  Open to **remote** and **international** opportunities

---

## 🤖 AI Engineering

### LLM & Generative AI

![LLM](https://img.shields.io/badge/LLM_Applications-412991?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square\&logo=openai\&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7B1FA2?style=flat-square)
![Generative AI](https://img.shields.io/badge/Generative_AI-FF6F00?style=flat-square)

* LLM-powered application development
* OpenAI API integration
* OpenRouter integration
* OpenAI-compatible API design
* Prompt engineering
* System prompts and context-aware generation
* Streaming and non-streaming LLM responses
* Model/provider abstraction
* Integrating multiple LLM providers

### RAG & Knowledge Systems

![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![Vector Search](https://img.shields.io/badge/Vector_Search-0288D1?style=flat-square)
![Semantic Search](https://img.shields.io/badge/Semantic_Search-7B1FA2?style=flat-square)
![Embeddings](https://img.shields.io/badge/Embeddings-00897B?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square)

* Retrieval-Augmented Generation (RAG)
* Document ingestion pipelines
* Document chunking and retrieval
* Text embeddings
* Semantic search
* Vector databases
* Context retrieval and augmentation
* Metadata-aware document storage
* Retrieval pipeline design
* RAG-based question answering systems
* Separating embedding and chat model providers
* Local embedding microservices

### Embeddings & Vector Databases

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square)
![Embedding Models](https://img.shields.io/badge/Embedding_Models-5C6BC0?style=flat-square)
![Semantic Retrieval](https://img.shields.io/badge/Semantic_Retrieval-00897B?style=flat-square)

* OpenAI embeddings
* Local embedding models
* Persian/Farsi embeddings
* `xmanii/maux-gte-persian`
* Vector similarity search
* Embedding-based retrieval
* Vector database architecture
* Persistent vector storage

### AI Infrastructure

* AI/LLM API design
* AI microservices
* Python-based AI services
* FastAPI
* Uvicorn
* Dockerized AI services
* Local inference/embedding services
* Provider abstraction
* Production API deployment
* AI service integration with backend systems

---

## 🧠 AI Engineering Project

### 🚀 RAG API — Production-Oriented Retrieval-Augmented Generation

[![RAG](https://img.shields.io/badge/GitHub-RAG-181717?style=for-the-badge\&logo=github)](https://github.com/MassoudKargar/RAG)

A practical **RAG API** designed to combine LLMs with vector-based retrieval.

The project demonstrates my experience with:

* **Retrieval-Augmented Generation**
* **ChromaDB**
* **Vector search**
* **Semantic search**
* **Document embeddings**
* **OpenAI-compatible APIs**
* **OpenRouter**
* **Local Persian embedding models**
* **FastAPI**
* **Streaming / non-streaming LLM responses**
* **Microservice-based embedding architecture**
* **Separation of embedding and chat providers**

Architecture allows the chat model and embedding model to be independently configured.

For example:

```text
                ┌─────────────────────┐
                │     Client / App    │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │       RAG API       │
                │      FastAPI        │
                └───────┬─────┬───────┘
                        │     │
              Retrieval │     │ Generation
                        │     │
                        ▼     ▼
                ┌──────────┐ ┌──────────────┐
                │ ChromaDB │ │ OpenRouter / │
                │  Vector  │ │ OpenAI / LLM │
                │   DB     │ └──────────────┘
                └────┬─────┘
                     │
                     ▼
             ┌──────────────────┐
             │ Local Embedding  │
             │     Service      │
             │ Persian GTE Model│
             └──────────────────┘
```

🔗 **Project:** https://github.com/MassoudKargar/RAG

---

## 🛠️ Tech Stack

### Backend & Architecture

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square\&logo=csharp\&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)
![Entity Framework](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-1A56A0?style=flat-square)

### AI / Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square\&logo=openai\&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square)
![Embeddings](https://img.shields.io/badge/Embeddings-00897B?style=flat-square)
![Vector Search](https://img.shields.io/badge/Vector_Search-0288D1?style=flat-square)
![Semantic Search](https://img.shields.io/badge/Semantic_Search-7B1FA2?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-412991?style=flat-square)

### Architecture Patterns

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-FF6F00?style=flat-square)
![Microservices](https://img.shields.io/badge/Microservices-0288D1?style=flat-square)
![CQRS](https://img.shields.io/badge/CQRS-7B1FA2?style=flat-square)
![DDD](https://img.shields.io/badge/DDD-C62828?style=flat-square)
![Event--Driven](https://img.shields.io/badge/Event--Driven-2E7D32?style=flat-square)

### Messaging & Streaming

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square\&logo=rabbitmq\&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square\&logo=apachekafka\&logoColor=white)

### Databases

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square\&logo=microsoftsqlserver\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)

### Security & Identity

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square\&logo=keycloak\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square\&logo=jsonwebtokens\&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat-square)

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square\&logo=elastic\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_LPIC--1-FCC624?style=flat-square\&logo=linux\&logoColor=black)

### Blockchain

![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square\&logo=solidity\&logoColor=white)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=flat-square\&logo=web3dotjs\&logoColor=white)

### Also Exploring

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=black)

---

## 📌 Featured Projects

| Project                                                           | Description                                                                                                                                   | Tech                                |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| [**RAG**](https://github.com/MassoudKargar/RAG)                   | Retrieval-Augmented Generation API with vector search, ChromaDB, embeddings, OpenAI-compatible APIs, OpenRouter, and local Persian embeddings | Python, FastAPI, RAG, ChromaDB, LLM |
| [**Base**](https://github.com/MassoudKargar/Base)                 | Reusable base framework for building clean, layered .NET applications                                                                         | C#, .NET, Clean Architecture        |
| [**Microservice**](https://github.com/MassoudKargar/Microservice) | Production-ready microservices reference with service decomposition, messaging, and Docker support                                            | C#, Docker, Messaging               |
| [**PollyNET**](https://github.com/MassoudKargar/PollyNET)         | Resilience patterns with retry, circuit breaker, and timeout                                                                                  | C#, Polly, .NET                     |
| [**WebApi**](https://github.com/MassoudKargar/WebApi)             | Professional REST API design with versioning, error handling, and Swagger                                                                     | ASP.NET Core, REST                  |
| [**Architecture**](https://github.com/MassoudKargar/Architecture) | Reference implementation for layered and clean architecture patterns                                                                          | C#, Clean Architecture              |

---

## 📈 GitHub Stats

<div align="center">

![Massoud's GitHub Stats](https://github-readme-stats.vercel.app/api?username=MassoudKargar\&show_icons=true\&theme=tokyonight\&hide_border=true\&count_private=true)
  
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MassoudKargar\&layout=compact\&theme=tokyonight\&hide_border=true)

</div>

---

## 💼 Work Experience Snapshot

```text
Senior .NET Backend Developer  │  Rasta Novin Aria       │  Apr 2025 – May 2026
Senior Backend Developer       │  Setigh Fara Ofogh      │  Oct 2024 – Mar 2025
Senior Backend Developer       │  Freelance / Remote     │  Jul 2023 – Oct 2024
.NET Backend Developer         │  Behineh Kavan Keyfiat  │  Jul 2021 – Jul 2023
Back-End Developer             │  Freelance              │  Mar 2020 – Jul 2021
```

---

## 📫 Let's Connect

I'm always open to interesting projects, remote opportunities, AI engineering challenges, backend architecture discussions, or collaboration on AI-powered systems.

> **Email:** [massoudkargar.web@gmail.com](mailto:massoudkargar.web@gmail.com)
> **LinkedIn:** [linkedin.com/in/masoudkargar](https://www.linkedin.com/in/masoudkargar/)
> **Resume:** [Download PDF](https://github.com/MassoudKargar/MassoudKargar/blob/main/Masoud_Kargar_Resume.pdf)
> **Website:** [masoudkargar.com](https://masoudkargar.com)
> **RAG Project:** [github.com/MassoudKargar/RAG](https://github.com/MassoudKargar/RAG)

---

<div align="center">

⭐ *If you find any of my repositories useful, a star goes a long way!*

</div>
