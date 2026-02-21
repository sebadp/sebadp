# 👋 Sebastián Dávila
### Backend & AI Engineer | Python Specialist

Results-driven backend developer with **5+ years** building scalable systems and AI-powered applications. Specialized in microservices architecture, distributed systems, and LLM integration.

---

## 🛠️ Tech Stack

**Languages**  
Python • JavaScript • Go • SQL • Bash

**Backend & AI**  
FastAPI • Django • Gin • Flask • Celery  
LangChain • LangGraph • Strands • DSPy • AWS Bedrock

**Data & Storage**  
PostgreSQL • MySQL • MongoDB • ArangoDB  
ChromaDB • Pinecone • Vector Databases

**Cloud & Infrastructure**  
AWS (Lambda, S3, DynamoDB, Bedrock, SQS, ECS) • Azure • Docker • Kubernetes  
OpenTelemetry • Grafana • LangFuse • Jaeger • DataDog

**Architecture & Practices**  
Microservices • REST APIs • Event-Driven (RabbitMQ)  
TDD • SOLID • CI/CD • Distributed Tracing

---

## 💼 Professional Experience

### Backend + Gen AI Developer @ **Trafilea** (2025)
* Led enterprise chatbot migration from AWS Bedrock Agents to the **Strands framework**.
* Designed **multi-agent architectures** with specialized agents branching by business function.
* Built an **LLM-as-Judge evaluation pipeline**: an automated self-improvement loop scoring outputs against a Golden Dataset.
* Integrated **RAG systems** with vector databases for context-aware, highly accurate responses.


### Backend Developer @ **Southern Code** (2023-2024)
* Developed high-performance **microservices** with FastAPI and Aiohttp.
* Migrated a monolithic system to a microservices architecture (Python 3.11).
* Implemented **distributed tracing** (Jaeger/OpenTelemetry), reducing MTTR by 40%.

### Backend Developer @ **Intive** (2021-2023)
* Integrated **15+ third-party APIs**, maintaining 99.9% uptime.
* Optimized complex Django queries, improving search performance by 60%.
* Managed **100GB+/day log pipelines** with SumoLogic at scale.

---

## 🛠️ Featured Personal Projects
---

### 📰 Briefly - AI-Powered News Briefings
**Autonomous research agent for personalized news curation** | [View Repo](https://github.com/sebadp/briefly)

AI-powered platform that creates personalized news briefings from natural language descriptions. Features an autonomous Research Agent that discovers sources, validates content, and keeps you updated.

**What it does:**
- 🧠 **Research Agent v2.0**: ReAct-based autonomous agent that plans searches, reasons about relevance, and validates sources
- 🤖 **AI Code Reviewer**: Internal Gemini-powered agent for automated PR reviews
- 🔍 **Multi-LLM Support**: Claude for validation, Gemini for extraction
- 📚 **Smart Briefings**: Auto-curated articles grouped by source with AI-generated descriptions
- 🎯 **NL Input**: Describe topics in plain language, agent handles the rest

**Technical Highlights:**
- **Autonomous Agent Architecture**: ReAct loop with planning, search, and validation steps
- **Multi-Search Integration**: Tavily API + Google Custom Search + web scraping fallback
- **Dual Database Design**: PostgreSQL (relational) + DynamoDB (NoSQL)
- **Production Infrastructure**: AWS CDK with ECS Fargate, RDS, Amplify
- **Full-Stack**: FastAPI backend + Next.js 14 frontend with glassmorphism UI

**Tech Stack:**  
`Python` `FastAPI` `Strands` `Claude SDK` `Gemini API` `Next.js 14` `TypeScript` `PostgreSQL` `DynamoDB` `AWS CDK` `ECS Fargate` `Tailwind CSS`

**Key Features:**
- ⚡ Streaming UI for Research Agent progress visualization
- 🔄 Auto-refresh keeps briefings updated
- 🎨 Modern glassmorphism design with shadcn/ui
- 🧪 Full CI/CD with GitHub Actions + AI PR reviews
- 📱 Mobile-responsive interface

**Status:** 🚀 Active development • AWS deployment ready

[📖 Documentation](https://github.com/sebadp/briefly/tree/main/docs) • [🏗️ Architecture](https://github.com/sebadp/briefly#-arquitectura)

---

### 🤖 LinkedIn AI Agent
**Intelligent job opportunity analysis and automation** | [View Repo](https://github.com/sebadp/nexton)

Enterprise-grade automation system for LinkedIn job search. Scrapes messages, analyzes opportunities with AI, scores matches, and generates personalized responses.

**What it does:**
- 📥 Daily LinkedIn message scraping with Playwright
- 🧠 AI-powered analysis using DSPy structured prompting
- 📊 Multi-dimensional scoring and A/B/C/D tier classification
- ✍️ Context-aware response generation adapted to job search status
- 📧 Daily summary emails with all opportunities
- 🎨 React dashboard for opportunity management

**Technical Highlights:**
- **Production Observability**: Full monitoring stack (Prometheus, Grafana, Jaeger, Loki)
- **Multi-LLM Support**: Works with Ollama (local), OpenAI, or Anthropic
- **Smart Caching**: Redis-based caching reduces LLM calls by 60%
- **Async Architecture**: FastAPI + Celery + Redis for background jobs
- **85% Test Coverage**: 140+ tests including integration and performance

**Tech Stack:**  
`Python` `FastAPI` `DSPy` `Playwright` `React` `PostgreSQL` `Redis` `Celery` `Docker` `Prometheus` `Grafana`

**Key Features:**
- ⚡ Real-time SSE streaming for analysis progress
- 🎯 Pre-configured Grafana dashboards
- 🔄 Complete CI/CD pipeline
- 📱 Mobile-responsive frontend with Tailwind + shadcn/ui
- 🧪 Mailpit integration for email testing

**Built as:** Technical challenge showcasing enterprise architecture

[📖 Full Documentation](https://github.com/sebadp/nexton/blob/main/docs/USER_GUIDE.md) • [🚀 Quick Start](https://github.com/sebadp/nexton#-quick-start)

---

### 🍺 BrewMaestro - Homebrew Tracking App
**Comprehensive brewing management platform** | In Development

Mobile-first application for homebrewers to manage recipes, track fermentation, and analyze brewing sessions.

**Features:**
- 📝 Recipe builder with grain bills, hop schedules, and calculations
- 📊 Fermentation tracking with temperature/gravity logging
- 🗄️ 400+ ingredient database (malts, hops, yeasts)
- 📈 Brewing analytics and efficiency tracking
- 📱 Offline-first architecture

**Tech Stack:**  
`React Native` `Expo` `TypeScript` `FastAPI` `PostgreSQL` `AWS S3`

**Status:** 🚧 Active development • Beta release Q2 2025

---

## 📚 Certifications

🏆 **Data Structures & Algorithms** - Jovian (2025)  
🏆 **Systems Design Expert** - AlgoExpert (2023)  
🏆 **MITx: CS & Programming with Python** (2022)

---

## 📫 Let's Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=Web&logoColor=white)](https://sebadp.github.io/sebastiandavila.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]((https://www.linkedin.com/in/sebastiandavila/))
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sebastian.davila.personal@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sebadp)

---

💡 *Open to senior backend and AI engineering opportunities*  
🌎 *Based in Argentina • Remote-ready • Spanish & English*
