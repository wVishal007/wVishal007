# Vishal Singh — Resume Data Source of Truth

> Canonical data for all 16 resume variants in `document/resumes/`.
> Master CV (`complete_cv.tex`) is the most comprehensive. All role-specific resumes derive from this.

---

## 1. Personal Information

| Field | Value |
|-------|-------|
| Name | Vishal |
| Email | vishalsingh31879@gmail.com |
| Phone | +91 7290908461 |
| GitHub | github.com/wVishal007 |
| LinkedIn | linkedin.com/in/vishal-singh-188013324 |
| Portfolio | vishal4u.vercel.app |

---

## 2. Education

### Bachelor of Computer Applications (BCA)
- **University:** Delhi Skill and Entrepreneurship University (DSEU)
- **Duration:** 2023 -- 2026
- **Status:** Completed

### Master of Computer Applications (MCA)
- **University:** Indira Gandhi National Open University (IGNOU)
- **Duration:** 2026 -- Present
- **Status:** Pursuing

---

## 3. Experience

### 3.1 TechEra Community — Technical Lead
- **Duration:** Sept 2025 -- Mar 2026

**Canonical bullets (Master CV):**
1. Led technical team building 15+ web and AI projects using MERN stack, Next.js, and Python-based AI systems
2. Mentored 20+ developers in full-stack development, Python, and AI concepts through code reviews and structured sessions
3. Designed system architectures, established code quality standards, and managed cross-team delivery
4. Coordinated technical planning, sprint workflows, and documentation for concurrent projects

**Trimmed bullets (role-specific, 2 bullets):**
- SWE: Led architecture and development of 15+ web applications across the full stack, establishing code review processes and deployment pipelines / Mentored 20+ developers in system design, clean code practices, and version control workflows
- Backend: Led backend architecture decisions across 15+ projects, establishing API design standards and database optimization practices / Mentored developers in Node.js, API development, authentication flows, and real-time communication patterns
- AI Engineer: Led AI/ML development initiatives, building LLM-powered applications, RAG systems, and autonomous agent pipelines / Mentored developers in AI integration, prompt engineering, and production deployment of ML models
- AI + Full Stack: Led end-to-end development of AI-powered applications from concept to deployment across the full stack / Mentored developers in full-stack development, AI integration, and production deployment practices
- Python: Mentored 20+ student developers in Python, backend development, and machine learning through code reviews and training sessions / Led architecture discussions for API design and data processing pipelines across student projects
- Full Stack Web: Led full-stack development of 15+ web applications, establishing architecture patterns from frontend components to database schemas / Mentored developers across the stack in React, Node.js, API design, and deployment workflows
- Frontend: Led frontend development for 15+ web applications, establishing component architecture and state management patterns / Mentored developers in React, Next.js, and UI development best practices through code reviews
- ML Engineer: Led ML/AI development initiatives, guiding teams in building ML models, NLP systems, and RAG pipelines / Mentored developers in machine learning concepts, data preprocessing, and model deployment
- Agentic AI: Led development of multi-agent AI systems and LLM-powered applications using LangChain and Mistral AI / Mentored developers in agentic AI concepts, prompt engineering, and RAG pipeline design
- AI (extra): Led AI development initiatives building RAG systems, LLM-powered applications, and AI agents / Mentored student developers in LangChain, prompt engineering, and vector database concepts
- Backend (extra): Led backend architecture decisions across 15+ projects, establishing API design standards and database optimization (1 bullet)
- Fullstack (extra): Led full-stack development of 15+ web applications, establishing architecture patterns and code quality standards (1 bullet)
- Web (extra): Led web development projects, establishing frontend component architecture and backend API patterns (1 bullet)
- Data Science: Led data science and ML initiatives, mentoring developers in model building and data analysis (1 bullet)
- Machine Learning (extra): Led ML/AI projects, guiding teams in building models, data pipelines, and deployment workflows (1 bullet)

### 3.2 Freelance E-Commerce Developer — Client Project
- **Duration:** Oct 2025 -- Jan 2026

**Canonical bullets (Master CV):**
1. Delivered production e-commerce platform using MERN stack with product catalog, cart, wishlist, filters, checkout, and admin dashboard
2. Integrated Razorpay payment gateway with real-time verification and automated PDF invoice generation via Nodemailer
3. Implemented OTP-based authentication and automated email notification system for order confirmations
4. Optimized media delivery with Cloudinary image optimization and responsive loading

**Trimmed variants:**
- SWE (2 bullets): Delivered production e-commerce platform using MERN stack with product catalog, cart, checkout, and admin dashboard / Integrated Razorpay payments, OTP authentication, and Cloudinary media optimization
- Backend Engineer (2 bullets): Built RESTful APIs for product catalog, cart, checkout, and order management with admin dashboard / Integrated Razorpay payment gateway with webhook verification and OTP-based authentication
- Full Stack Web (2 bullets): Delivered production e-commerce platform using MERN Stack with product catalog, cart, checkout, and admin dashboard / Integrated Razorpay payments, OTP authentication, and Cloudinary media optimization
- Backend (extra, 1 bullet): Built production backend with RESTful APIs for product catalog, cart, checkout, order management, and admin dashboard

**Not included in:** ai_engineer, ai_fullstack, python_engineer, frontend_engineer, ml_engineer, agentic_ai, ai, fullstack, web, data_science, machine_learning

### 3.3 SevaHetu — SDE Intern
- **Duration:** July 2026 -- Present

**Canonical bullets (Master CV):**
1. Developing backend services for a real-time healthcare emergency response platform using Node.js, Express.js, and PostgreSQL
2. Building and maintaining scalable REST APIs for core platform functionality
3. Working on performance optimization, database design, and backend architecture
4. Exploring AI-powered capabilities for future platform enhancements

**Per-variant bullets:**

| Variant | Bullet 1 | Bullet 2 | Bullet 3 |
|---------|----------|----------|----------|
| SWE | backend services, Node.js/Express/PostgreSQL | REST APIs | — |
| Backend Engineer | backend services, Node.js/Express/PostgreSQL | REST APIs | perf opt + DB design |
| AI Engineer | backend services, Node.js/Express/PostgreSQL | LLM eval for triage | — |
| AI + Full Stack | backend services, healthcare | REST APIs | — |
| Python | backend services, Node.js/Express/PostgreSQL | LLM eval for triage | — |
| Full Stack Web | backend services, healthcare | REST APIs | — |
| Frontend | backend services, Node.js/Express/PostgreSQL | REST APIs | — |
| ML Engineer | perf opt + DB design | LLM eval for triage | — |
| Agentic AI | backend services, Node.js/Express/PostgreSQL | LLM eval for triage | — |
| AI (extra) | backend services, Node.js/Express/PostgreSQL | LLM eval for triage | — |
| Backend (extra) | backend services, healthcare | REST APIs | — |
| Fullstack (extra) | backend services, healthcare | REST APIs | — |
| Web (extra) | backend services, healthcare | REST APIs | — |
| Data Science | perf opt + DB design | LLM eval for triage | — |
| ML (extra) | perf opt + DB design | LLM eval for triage | — |

---

## 4. Projects

### 4.1 ResearchOS — Autonomous AI Research Platform
- **Category:** AI/ML
- **Live Demo:** https://research-os-three.vercel.app/
- **Source Code:** Not public
- **Tech Stack:** Next.js 14, TypeScript, LangChain, Mistral AI, ChromaDB, MongoDB, React Flow, SSE, NextAuth.js, Tavily API

**Canonical bullets:**
1. Architected 13-agent autonomous research pipeline (Planner → Researcher → FactChecker → Synthesis → Report → Validator → Debate) with PipelineGuard enforcement preventing unauthorized AI calls outside the pipeline
2. Built RAG system using LangChain with Mistral AI embeddings, ChromaDB vector store, cosine similarity search, recursive text chunking, and multi-hop retrieval
3. Engineered real-time SSE streaming delivering pipeline stage updates, trust scores, and graph node statuses to React Flow visualization interface
4. Integrated plagiarism detection with auto-rewrite, auto-correction on low-trust outputs, CSV data insights with automated scikit-learn code generation, PDF chat, web scraping, and multi-language translation

**Featured in:** complete_cv, software_engineer, ai_engineer, ai_fullstack, frontend_engineer, agentic_ai, ai, backend, backend_engineer

**Trimmed for role-specific (3 bullets):**
- SWE: Architected 13-agent pipeline with PipelineGuard, RAG with ChromaDB / SSE streaming / pub/sub event bus + auto-correction
- AI Engineer: 13-agent pipeline with PipelineGuard + React Flow / RAG with ChromaDB, multi-hop / pub/sub event bus + SSE
- AI + Full Stack: End-to-end with Next.js 14 + LangChain/Mistral / RAG + multi-hop + SSE / CSV insights + ML code gen + PDF chat
- Frontend: React Flow pipeline viz / interactive dashboard + Recharts / data insights interface
- Agentic AI: 13-agent pipeline + PipelineGuard / RAG + ChromaDB + SSE + auto-correction / trust scoring + plagiarism + debate + translation
- AI (extra): 13-agent pipeline + PipelineGuard / RAG + ChromaDB + cosine + multi-hop / SSE + trust scoring + auto-correction
- Backend (extra): PipelineGuard + Event Bus pub/sub / SSE streaming + translation
- Backend Engineer: PipelineGuard / Event Bus pub/sub + SSE / translation layer

**Not featured in:** python_engineer, fullstack_web, ml_engineer, data_science, machine_learning

### 4.2 YT Intelligence Engine — Hybrid RAG with Citation
- **Category:** AI/ML
- **Source Code:** https://github.com/wVishal007/yt-rag-chatbot-extension
- **Tech Stack:** LangChain, ChromaDB, Mistral AI, Sentence Transformers, Chrome Extension, Python

**Canonical bullets:**
1. Built conversational Hybrid RAG system transforming YouTube video transcripts into a queryable knowledge base using LangChain, ChromaDB, and Mistral AI embeddings
2. Implemented hybrid retrieval combining dense semantic search with BM25 keyword scoring and cross-encoder reranking using Sentence Transformers
3. Developed Chrome Extension for automatic transcript extraction with multi-turn conversation memory, context-aware question rewriting, and hallucination control via grounded prompting
4. Built evaluation framework with Precision@K and Recall@K metrics, timestamped citation enforcement, and automated PDF study notes generation

**Featured in:** complete_cv, ai_engineer, python_engineer, ml_engineer, agentic_ai, ai

### 4.3 Content Generator Platform — Agentic AI Content System
- **Category:** AI/ML
- **Live Demo:** https://content-generator-agent-pi.vercel.app/
- **Source Code:** https://github.com/wVishal007/content_generator_agent
- **Tech Stack:** LangGraph, FastAPI, PostgreSQL, Redis, React, Docker Compose, Groq, Mistral, Gemini, NVIDIA, DuckDuckGo

**Canonical bullets:**
1. Built LangGraph StateGraph workflow with conditional routing: generates content, evaluates 0-10, and iteratively optimizes via score-based loops with fallback chain across 4 LLM providers (Groq → Mistral → Gemini → NVIDIA)
2. Implemented human-in-the-loop approval queue using asyncio.Event with configurable timeout, and A/B testing engine generating 2-5 variants with score comparison and winner determination
3. Integrated multi-platform generation (LinkedIn, Twitter/X, Instagram) with platform-specific format enforcement, 20+ language translation with cultural adaptation, and real-time trend integration via DuckDuckGo search
4. Deployed FastAPI backend with PostgreSQL and Redis, React frontend on Vercel, and Docker Compose multi-service orchestration

**Per-variant emphasis:**

| Variant | Emphasis | Bullets |
|---------|----------|---------|
| SWE | System design, state machines, Docker | StateGraph + 4 LLM fallback / approval queue + A/B / FastAPI + PostgreSQL + Docker |
| Backend Engineer | Backend infrastructure | FastAPI + PostgreSQL + Redis / StateGraph workflow engine / A/B testing API |
| AI Engineer | LangGraph agentic workflow | StateGraph + conditional routing + 0-10 eval / HITL approval + A/B / multi-platform |
| AI + Full Stack | Full-stack AI product | Full-stack LangGraph + FastAPI + React / agentic workflow + HITL / multi-platform + translation |
| Python | Python/LangGraph/FastAPI | LangGraph StateGraph in Python / HITL + A/B / FastAPI + PostgreSQL + Redis |
| Full Stack Web | Full-stack with React frontend | React + FastAPI + LangGraph / multi-platform + A/B + approval / trend data + translation + Docker |
| Master CV | Balanced AI + eng (4 bullets) | All 4 canonical bullets |

**Featured in:** complete_cv, software_engineer, ai_engineer, ai_fullstack, backend_engineer, python_engineer, fullstack_web

### 4.4 AI Interview Copilot
- **Category:** AI/ML
- **Live Demo:** https://ai-job-copilot-one.vercel.app
- **Source Code:** Not public
- **Tech Stack:** Next.js 16, Turbopack, MongoDB, OpenAI GPT, Gemini, Zod, bcrypt

**Canonical bullets:**
1. Built full-stack AI interview platform using Next.js 16 with Turbopack, MongoDB with 12 data models, and dual LLM integration (OpenAI GPT + Gemini) with fallback logic
2. Implemented AI-driven interview system with dynamic question generation across technical, behavioral, and system design domains, real-time answer evaluation, confidence scoring, and anti-cheat monitoring
3. Developed dual-role architecture (student/recruiter) with role-based access control, recruiter dashboards for job posting and applicant tracking, and student dashboards with application tracking
4. Built authentication with bcrypt password hashing, OTP-based email verification, and Zod validation schemas for all API inputs

**Featured in:** complete_cv, ai_fullstack, agentic_ai, fullstack, web

**Not featured in (swapped out for Content Generator):** software_engineer, ai_engineer, fullstack_web

### 4.5 Freelancer Income Prediction — Deep Learning Regression
- **Category:** AI/ML
- **Live Demo:** https://incomeprediction-hwtw.onrender.com/
- **Tech Stack:** PyTorch, Flask, Pandas, Scikit-learn, React

**Canonical bullets:**
1. Designed and trained three-layer feed-forward neural network (128 → 64 → 1) using PyTorch with ReLU activation and MSELoss, optimized with Adam optimizer over 350 epochs
2. Built preprocessing pipeline using Pandas for data cleaning, StandardScaler for normalization, and One-Hot Encoding for categorical variables producing 433-dimensional feature space
3. Engineered dynamic feature reindexing system for consistent inference regardless of missing or extra fields in request payload using serialized feature column mapping
4. Deployed Flask API serving trained model with real-time predictions through React frontend; implemented model serialization and scaler persistence

**Featured in:** complete_cv, python_engineer, ml_engineer, data_science, machine_learning

### 4.6 Anime Recommendation System — NLP Engine
- **Category:** AI/ML
- **Live Demo:** https://anime-recommendations-lime.vercel.app/
- **Tech Stack:** Python, Flask, Scikit-learn, CountVectorizer, Cosine Similarity, NumPy

**Canonical bullets:**
1. Built content-based recommendation engine using CountVectorizer for anime feature vectorization and cosine similarity for pairwise content matching across 1000+ records
2. Optimized API response time through pre-computed similarity matrices and NumPy vectorized operations
3. Deployed on Vercel with Flask backend serving RESTful recommendation API with modular architecture separating vectorization, data processing, and API routing

**Featured in:** complete_cv, ml_engineer, data_science, machine_learning

**Not featured in (swapped for Content Generator):** python_engineer

### 4.7 Sentiment Analysis on IMDB Dataset — NLP Classification
- **Category:** AI/ML
- **Tech Stack:** Python, Scikit-learn, TF-IDF, Logistic Regression, Naive Bayes, NLTK

**Bullets:**
1. Built NLP pipeline for binary sentiment classification on 50,000 movie reviews with text preprocessing including tokenization, stopword removal, and lemmatization
2. Implemented TF-IDF vectorization with Logistic Regression and Naive Bayes classifiers
3. Optimized tokenization pipeline for efficient large-scale text classification

**Featured in:** complete_cv, data_science, machine_learning

### 4.8 Ethereal Commerce — Luxury E-Commerce Platform
- **Category:** Full Stack
- **Live Demo:** https://ethix-nine.vercel.app/
- **Tech Stack:** Next.js 15 App Router, React 19, MongoDB, Razorpay, Cloudinary, Redux Persist, Tailwind CSS

**Canonical bullets:**
1. Architected luxury e-commerce platform with Next.js 15 App Router, React 19, and MongoDB featuring curated product discovery, Razorpay payment gateway with real-time verification, and JWT + OTP authentication
2. Built admin curation suite with Lookbook management, dynamic size guide system with category-specific measurements supporting cm/in unit conversion, and per-color-size inventory control
3. Engineered personalized shopping through Style Quiz aesthetic onboarding with tag-based regex filtering for dynamic home page curation and Quick View modals
4. Configured Cloudinary-optimized media delivery and implemented Redux Persist for session state management

**Featured in:** complete_cv, fullstack_web, frontend_engineer, fullstack, web, backend, backend_engineer

### 4.9 Blaze — Social Media Platform
- **Category:** Full Stack
- **Live Demo:** https://blaze-social-zeta.vercel.app/
- **Tech Stack:** Next.js, TypeScript, MongoDB, Ably WebSockets, NextAuth.js, Cloudinary, Tailwind CSS

**Canonical bullets:**
1. Developed social media platform with Next.js App Router, TypeScript, MongoDB, and Ably WebSockets supporting posts, stories, reels, chat, notifications, follow requests, blocking, and muting
2. Designed and implemented 15+ MongoDB schemas supporting social graph and engagement systems; built REST APIs for posts, stories, reels, conversations, and user interactions
3. Implemented real-time chat and notification system using WebSockets (Ably) with live messaging, online presence tracking, and explore feed
4. Integrated authentication using NextAuth with Google OAuth and JWT sessions; optimized media handling with Cloudinary and client-side compression

**Featured in:** complete_cv, software_engineer, backend_engineer, fullstack_web, frontend_engineer, fullstack, web, backend

### 4.10 Real-Time Chat Application
- **Category:** Full Stack
- **Source Code:** https://github.com/wVishal007
- **Tech Stack:** React, Node.js, Socket.io, MongoDB

**Bullets:**
1. Developed real-time chat application with private and group messaging using React, Node.js, Socket.io, and MongoDB
2. Implemented message read receipts, online status tracking, and message encryption
3. Designed backend architecture handling multiple concurrent connections with optimized database queries

**Featured in:** complete_cv only

---

## 5. Skills — Master List

| Category | Technologies |
|----------|-------------|
| Languages | Python, JavaScript, TypeScript, Java, C, SQL |
| Frontend | Next.js, React, TypeScript, HTML/CSS, Tailwind CSS, Redux Toolkit, Zustand, Framer Motion, Shadcn/UI |
| Backend | Node.js, Express.js, FastAPI, Flask, REST APIs, GraphQL, Socket.io, Ably, WebSockets |
| Databases | MongoDB, Mongoose ODM, MySQL, PostgreSQL, Redis, Firebase, ChromaDB |
| Machine Learning | PyTorch, Scikit-learn, XGBoost, Neural Networks, Regression, Classification, Clustering, Feature Engineering |
| NLP & AI | LangChain, LangGraph, Mistral AI, OpenAI, Gemini, RAG Pipelines, ChromaDB, Vector Embeddings, Semantic Search, Prompt Engineering, LLM Agents, NLP, NVIDIA |
| Auth & Payments | JWT, NextAuth.js, OTP Authentication, OAuth, bcrypt, Razorpay |
| Tools & DevOps | Git, GitHub, Docker, CI/CD, Vercel, Render, Cloudinary, Postman, Jupyter |
| Problem Solving | Data Structures & Algorithms, OOP, Complexity Analysis, System Design, Distributed Systems, Microservices, Pub/Sub, Caching, Load Balancing |

---

## 6. Achievements

1. **Winner — IIT Delhi Hackathon (TechGyan)** — Led team to 1st place designing and developing a technical solution under time constraints
2. **3rd Place — Infronix Hackathon, IIIT Delhi** — Built JanSaathi, an AI-powered government scheme recommendation platform; contributed to backend development and system integration
3. **Sponsor Track Winner — Hackemon Hackathon (She Builds Community)** — Recognized for innovation and execution as part of Team Dcoders

---

## 7. Certifications

| # | Certification | Issuer | Featured In |
|---|--------------|--------|-------------|
| 1 | Make Agentic AI Work for You | IBM | complete_cv, ai_engineer, ai_fullstack, python_engineer, ml_engineer, agentic_ai, ai, data_science, machine_learning, software_engineer, backend_engineer |
| 2 | Retrieval-Augmented Generation for Enhanced AI Outputs | IBM | complete_cv, ai_engineer, ai_fullstack, python_engineer, ml_engineer, agentic_ai, ai |
| 3 | AI Fundamentals: Foundations for Understanding AI | IBM | complete_cv, ai_engineer, ai_fullstack, python_engineer, ml_engineer, agentic_ai, ai, data_science, machine_learning |
| 4 | Web Development Fundamentals | IBM | complete_cv, software_engineer, backend_engineer, ai_fullstack, fullstack_web, frontend_engineer, backend, fullstack, web |
| 5 | Deep Learning | Simplilearn | complete_cv, ai_engineer, ai_fullstack, python_engineer, ml_engineer, data_science, machine_learning |
| 6 | Machine Learning and Neural Networks | TechGyan Technologies | complete_cv, ai_engineer, python_engineer, ml_engineer, data_science, machine_learning |
| 7 | Data Structures and Algorithms in Python | Simplilearn | complete_cv, software_engineer, backend_engineer, python_engineer, ml_engineer, data_science, machine_learning, backend |
| 8 | Python Programming | TechGyan Technologies | complete_cv, python_engineer, ml_engineer, data_science, machine_learning |
| 9 | TypeScript Basics | Simplilearn | software_engineer, backend_engineer, fullstack_web, frontend_engineer |
| 10 | Introduction to MERN Stack | Simplilearn | fullstack_web, frontend_engineer, fullstack, web |

---

## 8. Resume Variant Matrix

### 8.1 Role-Specific (8 files)

| File | Target Role | Experience | Projects | Skills Focus | Certs Count |
|------|-------------|------------|----------|-------------|-------------|
| `complete_cv.tex` | Full-Stack AI Engineer | TechEra (4) + Freelance (4) + SevaHetu (4) | All 10 | All 9 categories | 8 |
| `software_engineer.tex` | Software Engineer | TechEra (2) + Freelance (2) + SevaHetu (2) | ResearchOS, Blaze, Content Generator | System Design, DSA, TypeScript, Python | 4 |
| `backend_engineer.tex` | Backend Engineer | TechEra (2) + Freelance (2) + SevaHetu (3) | Blaze, ResearchOS, Content Generator | Node.js, FastAPI, MongoDB, Auth | 4 |
| `ai_engineer.tex` | AI Engineer | TechEra (2) + SevaHetu (2) | Content Generator, ResearchOS, YT RAG | LangChain, LangGraph, RAG, ChromaDB | 5 |
| `ai_fullstack.tex` | AI + Full-Stack Engineer | TechEra (2) + SevaHetu (2) | ResearchOS, AI Copilot, Content Generator | Frontend + Backend + AI/ML | 5 |
| `python_engineer.tex` | Python Developer | TechEra (2) + SevaHetu (2) | Income Prediction, YT RAG, Content Generator | Python, PyTorch, FastAPI, Pandas | 7 |
| `fullstack_web.tex` | Full Stack Web Engineer | TechEra (2) + Freelance (2) + SevaHetu (2) | Ethereal, Blaze, Content Generator | Next.js, Node.js, MongoDB, Payments | 4 |
| `frontend_engineer.tex` | Frontend Engineer | TechEra (2) + SevaHetu (2) | Ethereal, Blaze, ResearchOS | React, Next.js, Framer Motion, Recharts | 3 |
| `ml_engineer.tex` | ML Engineer | TechEra (2) + SevaHetu (2) | Income Prediction, Anime Rec, YT RAG | PyTorch, Scikit-learn, NLP, Deployment | 7 |

### 8.2 Extra Variants (7 files)

| File | Target Role | Experience | Projects | Skills Focus |
|------|-------------|------------|----------|-------------|
| `agentic_ai.tex` | Agentic AI Engineer | TechEra (2) + SevaHetu (2) | ResearchOS, YT RAG, AI Copilot | Multi-agent, LangChain, RAG, Trust Scoring |
| `ai.tex` | AI Engineer | TechEra (2) + SevaHetu (2) | ResearchOS, YT RAG | LLMs, RAG, ChromaDB, Prompt Engineering |
| `backend.tex` | Backend Developer | TechEra (1) + SevaHetu (2) | Blaze, ResearchOS, Ethereal | Node.js, FastAPI, MongoDB, WebSockets |
| `fullstack.tex` | Full Stack Developer | TechEra (1) + SevaHetu (2) | Ethereal, Blaze, AI Copilot | Next.js, React, Node.js, MongoDB |
| `web.tex` | Web Developer | TechEra (1) + SevaHetu (2) | Ethereal, Blaze, AI Copilot | Next.js, React, MongoDB, REST APIs |
| `data_science.tex` | Data Science Practitioner | TechEra (1) + SevaHetu (2) | Income Prediction, Anime Rec, IMDB Sentiment | PyTorch, Scikit-learn, Pandas, NLP |
| `machine_learning.tex` | ML Practitioner | TechEra (1) + SevaHetu (2) | Income Prediction, Anime Rec, IMDB Sentiment | PyTorch, Scikit-learn, Data Processing |

---

## 9. LaTeX Template Reference

All variants use a standardized clean template:

```
\documentclass[a4paper,8pt]{article}
\usepackage{parskip}
\usepackage{fontspec}
\usepackage[scale=0.9, top=.4in, bottom=.4in]{geometry}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage[hidelinks, unicode]{hyperref}

\setmainfont{Arial}

\titleformat{\section}{\large\bfseries\uppercase}{}{0em}{}[\titlerule]
\titlespacing{\section}{1pt}{2pt}{2pt}

\begin{document}
\pagestyle{empty}

\begin{center}
{\Huge Vishal} \\[4pt]
email $|$ phone \\
github $|$ linkedin $|$ portfolio
\end{center}
```

**Template rules:**
- Arial font only (no fontawesome, no icons)
- No tables, no text boxes, no minipages, no columns
- `\section{}` with uppercase + underline for headings
- `\begin{itemize}[nosep,leftmargin=1.5em]` for bullet lists
- `\textbf{Title} \hfill Date` for experience/project headers
- `$|$` for pipe separators in header
- `---` for em dashes
- `$|$` in header, NOT `\href` wrappers for URLs (all files uniform)
- Section order: Summary → Skills → Experience → Projects → Education → Achievements → Certifications
- Complete_cv adds `\href` around URLs only for linked text; role-specific uses plain URLs

---

## 10. Content Rules & Guidelines

1. **No unverifiable metrics** — Never use 99.9% uptime, "500+ daily requests", percentage improvements, or any metric that cannot be defended in an interview
2. **No buzzwords** — Avoid: world-class, rockstar, cutting-edge, ninja, guru, passionate, obsessed
3. **ATS-friendly** — Clean `\itemize` bullets, standard section names, simple structure, no images/colors/icons
4. **1-page constraint** — All role-specific and extra variants must compile to exactly 1 page at 8pt Arial with 0.9 scale and 0.4in margins
5. **Interview-defendable** — Every bullet must describe work you can explain in detail during an interview
6. **Action verbs** — Start bullets with strong past-tense verbs (Led, Built, Implemented, Architected, Developed, Engineered, Designed) or present-tense for current roles (Developing, Building)
7. **Spell-check** — British English spelling (e.g., Organised, Specialised) consistent across all files

---

## 11. File Locations

- **Canonical source:** `document/resumes/*.tex` (16 files)
- **Root copies:** `professional/*.tex` (synced from canonical, 17 files)
- **updated_resumes/:** `professional/updated_resumes/*.tex` (synced from canonical)
- **Cleanup script:** `clean.py` (removes .aux, .log, .out, .pdf)