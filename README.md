# Awesome UNIPDS Projects 🎓

A curated list of original projects built by students of the **[UNIPDS Software engineering with Applied AI](https://unipds.com.br/org-erick-wendel/?utm_source=awesomeunipdsprojects&utm_medium=github&utm_term=&utm_content=awesomeunipdsprojects)** postgrad course.

> [!IMPORTANT]
> This is a showcase of **original student work**. Projects inspired by course concepts are welcome, but must be brand new creations — not copies of exercises demonstrated in class.

Want to add your own? See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Table of Contents

- [Legend](#legend)
- [Projects](#projects)
  - [🔌 MCP Servers](#-mcp-servers)
  - [🤖 AI Agents](#-ai-agents)
  - [🌐 Web Apps & Games](#-web-apps--games)
  - [⚡ Integrations & Automations](#-integrations--automations)
  - [🛠️ Tools & Utilities](#-tools--utilities)
  - [📦 Other](#-other)

---

## Legend

**Language / runtime**
- `🐍` – Python
- `📇` – TypeScript / JavaScript
- `🏎️` – Go
- `🦀` – Rust
- `#️⃣` – C#
- `☕` – Java

**Scope**
- `☁️` – Calls external / cloud APIs
- `🏠` – Runs fully locally
- `🔗` – Integrates two or more services

---

## Projects

> [!NOTE]
> Projects are listed alphabetically within each category.

### 🔌 MCP Servers

MCP servers that extend AI assistants with new tools and capabilities.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [alvesribeirof/architecture-analysis-mcp](https://github.com/alvesribeirof/architecture-analysis-mcp) `#️⃣` `🔗` – MCP server for architectural code analysis focusing on SOLID principles, Design Patterns, and immediate feedback to the developer. **by [@alvesribeirof](https://github.com/alvesribeirof)**

- [JeisonSilva/mcp-OmniMatch](https://github.com/JeisonSilva/mcp-OmniMatch) `📇` `🏠` – MCP server that maps Angular screens to .NET Web API endpoints, accumulates extracted schemas in SQLite across multiple tool calls, and evaluates frontend–backend field and type compatibility — at zero LLM API cost. **by [@JeisonSilva](https://github.com/JeisonSilva)**
- [JeisonSilva/consultor-contas](https://github.com/JeisonSilva/consultor-contas) `📇` `☁️` `🔗` – MCP server that exposes a real estate budget analysis tool: reads property cost CSVs (IPTU, condominium fees, insurance), filters and ranks properties via a LangGraph planner–responder pipeline, and answers natural-language queries via OpenRouter. **by [@JeisonSilva](https://github.com/JeisonSilva)**

- [s3b4hjr/philosophy-mcp](https://github.com/s3b4hjr/philosophy-mcp) `🐍` `☁️` - MCP server for a multilingual philosophy corpus — glossary, syntheses, thinker profiles, and articles in Portuguese, English, and Spanish. **by [@s3b4hjr](https://github.com/s3b4hjr)**

---

### 🤖 AI Agents

Autonomous agents that accomplish multi-step tasks using LLMs.

- [JeisonSilva/AtendimentoConsultasMedicas](https://github.com/JeisonSilva/AtendimentoConsultasMedicas) `📇` `☁️` `🔗` – Multi-agent LangGraph chatbot that guides patients through medical appointment scheduling, lookup, and cancellation, with session and booking persistence via PostgreSQL. **by [@JeisonSilva](https://github.com/JeisonSilva)**
- [SyanCS/pokemon-training-center](https://github.com/SyanCS/pokemon-training-center) `📇` `🔗` – AI scheduling assistant that classifies natural-language intents via LangGraph + OpenRouter to manage Pokemon lesson enrollments, bookings, and recommendations. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/alvorada_real_estate](https://github.com/SyanCS/alvorada_real_estate) `📇` `🔗` – Real estate research platform with three LangGraph pipelines for feature extraction from notes, natural-language property ranking, and Neo4j GraphRAG similarity search. **by [@SyanCS](https://github.com/SyanCS)**
- [matheusmschaffer/entrevistador-implacavel](https://github.com/matheusmschaffer/entrevistador-implacavel) `TypeScript` `AI Agent` – LangGraph agent that conducts job interviews with four distinct personalities, evaluates answers silently, and delivers dramatic feedback. **by [@matheusmschaffer](https://github.com/matheusmschaffer)**
- [MarceloSoiber/credit-card-fraud-detection](https://github.com/MarceloSoiber/credit-card-fraud-detection) `🐍` `🔗` – Local credit card fraud detection platform with FastAPI, PostgreSQL, Docker, a web dashboard, model training workflows, sequence-based ML inference, transaction import, risk scoring, and optional LLM-powered fraud analysis. **by [@MarceloSoiber](https://github.com/MarceloSoiber)**
- [odairmichaelbendotti/code-sheriff](https://github.com/odairmichaelbendotti/code-sheriff) `📇` `☁️` – AI agent that connects to GitHub, automatically fetches open Pull Requests, and analyzes them in real time to detect security vulnerabilities, performance bottlenecks, and technical debt, providing intelligent fix suggestions before they reach production. **by [@odairmichaelbendotti](https://github.com/odairmichaelbendotti)**
  
---

### 🌐 Web Apps & Games

Web applications and browser-based experiences powered by machine learning or AI.

- [Biaginibe/ML-nextjs-board-game](https://github.com/Biaginibe/ML-nextjs-board-game) `📇` `🏠` – Board game recommendation system using TensorFlow.js for server-side machine learning with Next.js. **by [@Biaginibe](https://github.com/Biaginibe)**
- [DiogoOrdine/game-eclipse-ai-agent](https://github.com/DiogoOrdine/game-eclipse-ai-agent) `📇` `🏠` – Adaptation of the Eclipse game integrating a YOLOv5n neural network running with TensorFlow.js inside a Web Worker. **by [@DiogoOrdine](https://github.com/DiogoOrdine)**
- [Douglas-sm/game-flapbird](https://github.com/Douglas-sm/game-flapbird) `📇` `🏠` – Pixel art Flappy Bird game with an AI that trains itself in the browser using Canvas 2D and TensorFlow.js. [Live demo](https://game-flapbird.vercel.app/). **by [@Douglas-sm](https://github.com/Douglas-sm)**
- [ElizioMartins/graphrag-poc](https://github.com/ElizioMartins/graphrag-poc) `📇` `☁️` `🔗` – Intelligent document search system with GraphRAG: reads PDF/XML files, creates knowledge graphs in Neo4j, and answers questions using semantic search + LLMs with automatic fallback across multiple free models. **by [@ElizioMartins](https://github.com/ElizioMartins)**
- [me-wsantos/classificacao-tensorflowjs](https://github.com/me-wsantos/AI-Engineer-UNIPDS/tree/75e2183198175ac8610399b1df2752fdef710f42/001-classificacao-tensorflowjs) `📇` `🏠` – Social class classifier neural network trained and executed entirely in the browser using TensorFlow.js, predicting socioeconomic tiers (A–E) based on user-provided attributes. [🌐 Live demo](https://ai-engineer-unipds.onrender.com/) **by [@me-wsantos](https://github.com/me-wsantos)**
- [rdiegoss/scout](https://github.com/rdiegoss/scout) `📇` `🏠` – AI-powered PWA for local service discovery that uses on-device TensorFlow.js embeddings to rank nearby providers (electricians, plumbers, mechanics) by semantic similarity, geographic proximity, and behavioral compatibility. **by [@rdiegoss](https://github.com/rdiegoss)**
- [SyanCS/dr_nala_breed_recommendation](https://github.com/SyanCS/dr_nala_breed_recommendation) `📇` `🏠` – AI-first dog breed recommendation app that trains a TensorFlow compatibility classifier, persists model artifacts in PostgreSQL, and serves ranked recommendations from a browser web worker with a rule-based fallback. **by [@SyanCS](https://github.com/SyanCS)**
- [SyanCS/the-speakeasy-chatbot](https://github.com/SyanCS/the-speakeasy-chatbot) `📇` `🏠` – 1920s barkeep chatbot that runs fully in-browser on Chrome's on-device Gemini Nano (Prompt API) — multimodal cocktail suggestions, substitutions, scaling, and drink fixes with no backend or API keys. **by [@SyanCS](https://github.com/SyanCS)**
- [thabata-marchi/portuguese-alphabet-game](https://github.com/thabata-marchi/portuguese-alphabet-game) `📇` `🏠` – Pre-literacy educational game for children that teaches the Portuguese alphabet using voice recognition and adaptive AI. **by [@thabata-marchi](https://github.com/thabata-marchi)**
- [wsantos-ai/classificador-socioeconomico](https://github.com/wsantos-ai/Classificador-Socioeconomico) `📇` `🏠` – Social class classifier neural network trained and executed entirely in the browser using TensorFlow.js, predicting socioeconomic tiers (A–E) based on user-provided attributes. [🌐 Live demo](https://ai-engineer-unipds.onrender.com/) **by [@wsantos-ai](https://github.com/wsantos-ai)**
- [wsantos-ai/GitHub-PII-Scanner](https://github.com/wsantos-ai/GitHub-PII-Scanner) `📇` `🏠` – Web tool for static analysis of GitHub repositories to detect exposure of personal data (PII) and sensitive credentials in source code.  [🌐 Live demo](https://git-hub-pii-scanner.vercel.app/) **by [@wsantos-ai](https://github.com/wsantos-ai)**
- [lgfauth/truco-de-malandro](https://github.com/lgfauth/truco-de-malandro) `🐍` & `📇` `🏠` – Online Paulista Truco game against AI. You can play against the AI and watch the AI training in real time. [Line demo](https://truco-malandro.up.railway.app). **by [@lgfauth](https://github.com/lgfauth)**
- [giovaninogueira/agent-railway](https://github.com/giovaninogueira/agent-railway) – Intelligent monitoring agent for Railway-hosted applications using LangGraph, Gemini and Railway GraphQL API. **by [@giovaninogueira](https://github.com/giovaninogueira)**
- [giovaninogueira/fruit-ninja-robot](https://github.com/giovaninogueira/fruit-ninja-robot) – Interactive Fruit Ninja game with real-time fruit classification using YOLOv8 and ONNX running in the browser. **by [@giovaninogueira](https://github.com/giovaninogueira)**
- [giovaninogueira/recommendation-anime](https://github.com/giovaninogueira/recommendation-anime) – Anime recommendation system using neural networks that learns user taste profiles and suggests new titles. Built with NestJS, TensorFlow.js and PostgreSQL. **by [@giovaninogueira](https://github.com/giovaninogueira)**
- [giovaninogueira/doom-rag](https://github.com/giovaninogueira/doom-rag) – RAG system built over the DOOM universe lore, from the classic 1993 trilogy to The Dark Ages. Ask questions in natural language and get answers grounded in official lore using Neo4j graph database and Gemini. **by [@giovaninogueira](https://github.com/giovaninogueira)**
- [kauanevieira/cat-care-recommender](https://github.com/kauanevieira/cat-care-recommender) – A recommendation system for cat care and products that combines a neural network (TensorFlow.js) with vector search (ChromaDB) to generate personalized suggestions based on the pet's profile. **by [@kauanevieira](https://github.com/kauanevieira)**
- [kauanevieira/neuro-pet-ai](https://github.com/kauanevieira/neuro-pet-ai) – An evolutionary smart assistant for pets, built with React and Chrome's experimental Web AI. The project demonstrates advanced artificial intelligence concepts running entirely in the browser, with no backend and no calls to external APIs. **by [@kauanevieira](https://github.com/kauanevieira)**
- [kauanevieira/win-game](https://github.com/kauanevieira/win-game) – This project was developed as part of a graduate program in Software Engineering with a focus on AI applications, specifically exploring single-client architecture, asynchronous processing using Web Workers, and in-browser neural network inference with TensorFlow.js and a YOLO model adapted for web execution. **by [@kauanevieira](https://github.com/kauanevieira)**


---

### ⚡ Integrations & Automations

Projects that connect services, automate workflows, or react to events.

- [mjunior/whatsapp-ai-pix-agent](https://github.com/mjunior/whatsapp-ai-pix-agent) `📇` `🔗` – An AI agent that charges my wife via PIX when she asks for favors on WhatsApp. **by [@mjunior](https://github.com/mjunior)**

- [iran-gregorio/project-aegis](https://github.com/iran-gregorio/project-aegis) `📇` `🔗` - An intelligent chatbot designed to analyze sentiment and handle aggression on WhatsApp. ** by [@iran-gregorio](https://github.com/iran-gregorio)**

- [nogueira-araujo/IReadThis.Recommender](https://github.com/nogueira-araujo/IReadThis.Recommender) `#️⃣` `🏠` – AI recomendation API totally developed in C# using the side-car pattern to acoplish into an existent legacy system. **by [@nogueira-araujo](https://github.com/nogueira-araujo)**

---

### 🛠️ Tools & Utilities

CLIs, libraries, helpers, and developer tools powered by AI.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
- [ElizioMartins/projeto-00-ibge-tensores](https://github.com/ElizioMartins/projeto-00-ibge-tensores) `📇` `🏠` – Population Predictor using IBGE demographic data and Machine Learning. **by [@ElizioMartins](https://github.com/ElizioMartins)**
- [ftonato/auris](https://github.com/ftonato/auris) `📇` `☁️` – Production-grade Node.js RAG system with hybrid retrieval, pluggable adapters, and OpenTelemetry tracing. **by [@ftonato](https://github.com/ftonato)**
- [lucas-figueiredo-m/radar](https://github.com/lucas-figueiredo-m/radar) `📡` `🪲` - An integrated React Native DevTools with console, networking, native metrics and more, powered with an MCP for AI-assisted debugging. **by [@lucas-figueiredo-m](https://github.com/lucas-figueiredo-m)**
- [ftuyama/scroll-closing-your-eyes](https://github.com/ftuyama/scroll-closing-your-eyes) `🐍` `🏠` – Hands-free scrolling driven by eye closure (left eye up, right eye down) using the webcam, MediaPipe Face Landmarker, and PyAutoGUI, with blink filtering and “look straight” gating. **by [@ftuyama](https://github.com/ftuyama)**
- [JeisonSilva/chat-document-response](https://github.com/JeisonSilva/chat-document-response) `📇` `☁️` `🔗` – RAG pipeline that ingests PDFs into Neo4j using local HuggingFace embeddings and answers natural-language questions via OpenRouter LLMs. **by [@JeisonSilva](https://github.com/JeisonSilva)**
- [Brunoolliveira1993/code-review-ai](https://github.com/Brunoolliveira1993/code-review-ai) `📇` `🏠` - Analyzes GitHub Pull Requests,analyzes GitLab and GitLab Merge Requests, collects the PR/MR or commit diff, sends the code to AI via OpenRouter, and displays found issues and suggestions **by [@Brunoolliveira1993](https://github.com/Brunoolliveira1993)**
- [etrapp/youtube-comments-analyzer](https://github.com/etrapp/youtube-comments-analyzer) `🐍` `🔗` – A tool for analyzing YouTube video satisfaction through comments using MCP, RAG, LLM. **by [@etrapp](https://github.com/etrapp)**
---

### 📦 Other

Anything that doesn't fit neatly into the categories above.

<!-- Add your project here. See CONTRIBUTING.md for the entry format. -->
*No projects yet — be the first to submit one!*

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for submission guidelines.  
Questions? Open an issue or reach out on the course community channel.

## Thanks

A special thanks to all our amazing contributors 💚🇧🇷

<a href="https://github.com/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects/graphs/contributors"><img src="https://readme-contribs.as93.net/contributors/unipds-engenharia-de-ia-aplicada/awesome-unipds-projects" /></a>
