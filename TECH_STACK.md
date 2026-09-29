# Tech Stack

A consolidated, evidence-based overview of the technologies used across the repositories under [**@mustafaabdullahai-dev**](https://github.com/mustafaabdullahai-dev). It was compiled by analyzing the source, manifests (`package.json`, `requirements.txt`, `pyproject.toml`, `docker-compose.yml`) and languages of every repository.

Focus: **AI / LLM engineering, agentic systems, and full-stack product development.**

---

## Summary

| Area | Primary choices |
|------|-----------------|
| Languages | Python, TypeScript, JavaScript, HTML/CSS, Shell |
| AI / Agents | LangChain, LangGraph, OpenAI, Anthropic, Google Gemini, Groq, Hugging Face, Ollama, Qwen |
| Backend | FastAPI, Uvicorn, Pydantic, Celery, Redis, APScheduler |
| Frontend | React, Next.js, Vite, TypeScript, Tailwind CSS, Zustand, Three.js |
| Data | PostgreSQL + pgvector, SQLite, SQLAlchemy, FAISS, ChromaDB, Google Sheets/Drive |
| Automation | n8n, Playwright, BeautifulSoup, Trafilatura, Apify, Serper, MCP |
| DevOps | Docker, Docker Compose, Caddy, Netlify, systemd, GitHub Actions |

---

## Languages

- **Python** — primary language across backend, AI, and automation projects.
- **TypeScript** — primary frontend language (React, Next.js, Vite apps).
- **JavaScript** — tooling, MCP configuration, DNS scripts.
- **HTML / CSS** — landing pages and static sites.
- **Shell / Bash** — system utilities and install scripts.
- **SQL** — relational data access via SQLAlchemy.

## AI, LLMs & Agent Engineering

- **Orchestration:** LangChain, LangGraph (stateful agents, checkpointing).
- **Model providers:** OpenAI, Anthropic (Claude), Google Gemini, Groq, Hugging Face Inference, Ollama (local), Alibaba Qwen.
- **RAG & retrieval:** FAISS, ChromaDB, pgvector, `fastembed`, `langchain-text-splitters`.
- **Web-connected agents:** DuckDuckGo search (`ddgs`), Trafilatura, BeautifulSoup, Playwright.
- **Document ingestion:** `pypdf`, `python-docx`.
- **Protocols & tooling:** Model Context Protocol (MCP), prompt engineering, structured JSON output, LLM chains.
- **Low-code automation:** n8n (AI agent + workflow automations).

## Backend & APIs

- **Frameworks:** FastAPI, Uvicorn; Flask.
- **Validation & config:** Pydantic, Pydantic Settings, python-dotenv.
- **Async & HTTP:** `httpx`, `asyncpg`, `requests`.
- **Task processing:** Celery + Redis, APScheduler.
- **Auth & security:** OAuth2, `cryptography`, `itsdangerous`, HTTP header/bearer auth.
- **Google integrations:** `google-api-python-client`, `google-auth`, `gspread`.

## Frontend Development

- **Frameworks:** React 18/19, Next.js 16.
- **Build tooling:** Vite, TypeScript.
- **Styling:** Tailwind CSS (v3 & v4), PostCSS, Autoprefixer.
- **State management:** Zustand.
- **Animation & 3D:** Framer Motion, GSAP, Three.js, `@react-three/fiber`, `@react-three/drei`.
- **Content rendering:** `react-markdown`, `remark-gfm`, `rehype-highlight`, `highlight.js`.
- **Other libraries:** `lucide-react` (icons), `react-router-dom` (routing), `qrcode`, `gifenc`.

## Databases & Storage

- **Relational:** PostgreSQL (with **pgvector**), SQLite.
- **ORM:** SQLAlchemy.
- **Vector stores:** FAISS, ChromaDB, pgvector.
- **Cloud storage & data:** Google Sheets, Google Drive, Netlify Blobs.

## DevOps, Testing & Tooling

- **Containers & deployment:** Docker, Docker Compose, Caddy (TLS/reverse proxy), Netlify.
- **Operating system:** Linux, systemd services.
- **Version control:** Git, GitHub, GitHub Actions.
- **Python quality:** pytest, pytest-asyncio, Ruff.
- **JS quality & testing:** ESLint, Prettier, oxlint, Vitest, Playwright, Lighthouse CI.
- **Package management:** pip, npm.

## APIs & Third-Party Integrations

LinkedIn API · Gmail · Google Sheets · Google Drive · Google PageSpeed Insights · Google Gemini · OpenAI · Anthropic · Groq · Hugging Face · Apify · Serper.dev · APITemplate.io · WhatsApp

---

## Technology Stack by Repository

| Repository | Language(s) | Key technologies |
|------------|-------------|------------------|
| [mustafaabdullahai-dev](https://github.com/mustafaabdullahai-dev/mustafaabdullahai-dev) | Markdown | GitHub profile, shields.io badges, GitHub Readme Stats |
| [n8n-workflows](https://github.com/mustafaabdullahai-dev/n8n-workflows) | JSON (n8n) | n8n, Google Gemini, Alibaba Qwen, Apify, Serper, PageSpeed Insights, APITemplate.io, LinkedIn, Gmail, Google Sheets/Drive |
| [postcraft-linkedin](https://github.com/mustafaabdullahai-dev/postcraft-linkedin) | Python, TypeScript | FastAPI, LangChain/LangGraph, OpenAI, Anthropic, Google APIs, React, Vite, Tailwind |
| [abdullah-portfolio](https://github.com/mustafaabdullahai-dev/abdullah-portfolio) | TypeScript | Next.js 16, React 19, Tailwind v4, Three.js / R3F, Framer Motion, GSAP, Netlify |
| [migpt-chat](https://github.com/mustafaabdullahai-dev/migpt-chat) | Python, TypeScript | FastAPI, LangGraph, Groq, FAISS, fastembed, SQLAlchemy, React, Vite, Zustand, Docker |
| [ecom-intel](https://github.com/mustafaabdullahai-dev/ecom-intel) | Python, TypeScript | FastAPI, Streamlit, LangGraph, Ollama/OpenAI, Playwright, PostgreSQL + pgvector, Celery, Redis, Docker, Caddy |
| [whatsapp-agent](https://github.com/mustafaabdullahai-dev/whatsapp-agent) | Python | LangGraph, FastAPI, OpenAI, asyncpg/PostgreSQL, Docker, pytest, Ruff |
| [wa-mcp-setup](https://github.com/mustafaabdullahai-dev/wa-mcp-setup) | JavaScript | Node.js (ESM), MCP server, WhatsApp API |
| [openresearch-langgraph](https://github.com/mustafaabdullahai-dev/openresearch-langgraph) | Python, TypeScript | FastAPI, LangGraph, Hugging Face, ChromaDB, RAG, React, Vite, Tailwind, Docker |
| [birthday-wish-website](https://github.com/mustafaabdullahai-dev/birthday-wish-website) | TypeScript, CSS | React 19, Vite, Three.js / R3F, Framer Motion, Zustand, Netlify Blobs, Vitest, Playwright |
| [wifi-hotspot](https://github.com/mustafaabdullahai-dev/wifi-hotspot) | Shell | Bash, systemd |
| [Python-Functions](https://github.com/mustafaabdullahai-dev/Python-Functions) | Python | Python fundamentals (functions, `map`/`filter`/`lambda`) |
| [Catchhub-landing-page](https://github.com/mustafaabdullahai-dev/Catchhub-landing-page) | HTML, CSS | Static landing page |
| [register](https://github.com/mustafaabdullahai-dev/register) *(fork)* | JavaScript | is-a.dev DNS registration tooling |
| [is-a-dev.github.io](https://github.com/mustafaabdullahai-dev/is-a-dev.github.io) *(fork)* | HTML, CSS, JS | is-a.dev website |

---

## Highlights

- **Agentic AI foundations:** multiple projects built on **LangGraph** and **LangChain** with tool use, retrieval, and persistent state.
- **Multi-provider LLM experience:** OpenAI, Anthropic, Gemini, Groq, Hugging Face, and local **Ollama** models.
- **Production-oriented delivery:** containerized services, reverse-proxy/TLS, background workers, and automated tests.
- **End-to-end ownership:** from data ingestion and model orchestration to REST APIs and polished React frontends.
