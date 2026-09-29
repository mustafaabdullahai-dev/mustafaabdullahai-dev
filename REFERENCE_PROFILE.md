<!--
  REFERENCE PROFILE TEMPLATE
  A reusable copy of the profile layout used in README.md.
  The style is adapted from the GenAIwithMS profile: a theme-aware SVG header,
  social badges, a short quote, a "how I build" pipeline, a categorized tech-stack
  table, theme-aware GitHub stats, and an SVG footer.

  To reuse this for another account:
  1. Replace the username mustafaabdullahai-dev everywhere (asset URLs + widgets).
  2. Swap the SVG assets in /assets for your own.
  3. Update the badges, the quote and the three feature columns.
  HTML comments like this one are invisible when the file is rendered.
-->

<div align="center">

<!-- Theme-aware header banner. Provide a dark and a light SVG in /assets. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/header-light.svg">
  <img src="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/header-dark.svg" alt="Abdullah Mustafa — AI Engineer, Full-Stack Developer, AI Automation">
</picture>

<br/>

<!-- Primary links. Keep these short and high-signal. -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ab-mustafa5843/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mustafaabdullahai-dev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)

</div>

<!-- One-line positioning quote. Keep it specific to how you work. -->
> *"The future belongs to those who can master the art of turning complex models into simple, working products."*  **Abdullah Mustafa**

<br/>

## 🧬 How I Build AI Systems

<!-- A visual pipeline. Nodes move left to right; the bottom banner states the
     operating principle. Replace the SVG when your workflow changes. -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/pipeline-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/pipeline-light.svg">
  <img src="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/pipeline-dark.svg" alt="Pipeline: ingest → embed and retrieve → agents → ship → deploy, with automation running the same pipelines unattended">
</picture>

</div>

<br/>

<!-- Three concise pillars. Each column: an emoji title + one tight paragraph. -->
<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">📚 Retrieval that earns its context</h3>
      <p align="center">Domain-matched embeddings, structure-aware chunking into FAISS, Chroma or pgvector, and search narrowed before generation so answers stay grounded or abstain instead of guessing.</p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🤖 Agents that ship to production</h3>
      <p align="center">Stateful, tool-using agents orchestrated as LangGraph graphs and connected to real systems through MCP servers, APIs and databases, served behind FastAPI with memory, retries and background work.</p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">⚡ Automation that removes manual work</h3>
      <p align="center">The same pipelines run headless on a schedule through n8n workflows and workers, scraping, enriching and publishing data automatically so humans only handle the hard parts.</p>
    </td>
  </tr>
</table>

<br/>

## 🛠️ Tech Stack

<!-- Two-column table: category label + a row of shields.io badges.
     Add or remove rows as your stack evolves. -->
<table>
  <tr>
    <td><b>🧠 Agents &amp; Frameworks</b></td>
    <td>

![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)

  </td>
  </tr>
  <tr>
    <td><b>🔮 Models &amp; Providers</b></td>
    <td>

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![Alibaba Qwen](https://img.shields.io/badge/Alibaba%20Qwen-615CED?style=for-the-badge)

  </td>
  </tr>
  <tr>
    <td><b>📚 RAG &amp; Vector Stores</b></td>
    <td>

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge) ![fastembed](https://img.shields.io/badge/fastembed-005571?style=for-the-badge)

  </td>
  </tr>
  <tr>
    <td><b>⚙️ Backend &amp; APIs</b></td>
    <td>

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

  </td>
  </tr>
  <tr>
    <td><b>🎨 Frontend</b></td>
    <td>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-2D3748?style=for-the-badge)

  </td>
  </tr>
  <tr>
    <td><b>🗄️ Data</b></td>
    <td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)

  </td>
  </tr>
  <tr>
    <td><b>🌐 Automation &amp; Scraping</b></td>
    <td>

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-3776AB?style=for-the-badge) ![Trafilatura](https://img.shields.io/badge/Trafilatura-1F6FEB?style=for-the-badge) ![Apify](https://img.shields.io/badge/Apify-FF7A00?style=for-the-badge) ![Serper](https://img.shields.io/badge/Serper-4285F4?style=for-the-badge)

  </td>
  </tr>
  <tr>
    <td><b>☁️ Cloud &amp; DevOps</b></td>
    <td>

![Docker](https://img.shields.io/badge/Docker-0DB7ED?style=for-the-badge&logo=docker&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white) ![Linux VPS](https://img.shields.io/badge/Linux%20VPS-FCC624?style=for-the-badge&logo=linux&logoColor=000000) ![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

  </td>
  </tr>
</table>

<br/>

## 📊 GitHub Activity

<!-- Theme-aware widgets: each <picture> swaps the dark/light colour params.
     Any github-readme-stats compatible host works here. -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-theta-rust-54.vercel.app/api?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&show_icons=true&bg_color=0d1117&title_color=5ee6b0&text_color=c9d1d9&icon_color=79c0ff&border_color=30363d">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-theta-rust-54.vercel.app/api?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&show_icons=true&bg_color=ffffff&title_color=0969da&text_color=24292f&icon_color=8250df&border_color=d0d7de">
  <img height="170" src="https://github-readme-stats-theta-rust-54.vercel.app/api?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&show_icons=true&bg_color=0d1117&title_color=5ee6b0&text_color=c9d1d9&icon_color=79c0ff&border_color=30363d" alt="GitHub stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-theta-rust-54.vercel.app/api/top-langs/?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&layout=compact&bg_color=0d1117&title_color=5ee6b0&text_color=c9d1d9&border_color=30363d">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-theta-rust-54.vercel.app/api/top-langs/?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&layout=compact&bg_color=ffffff&title_color=0969da&text_color=24292f&border_color=d0d7de">
  <img height="170" src="https://github-readme-stats-theta-rust-54.vercel.app/api/top-langs/?username=mustafaabdullahai-dev&include_all_commits=true&count_private=true&layout=compact&bg_color=0d1117&title_color=5ee6b0&text_color=c9d1d9&border_color=30363d" alt="Top languages">
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=mustafaabdullahai-dev&background=0d1117&border=30363d&stroke=30363d&ring=5ee6b0&fire=5ee6b0&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=5ee6b0&sideLabels=79c0ff&dates=6e7681">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=mustafaabdullahai-dev&background=ffffff&border=d0d7de&stroke=d0d7de&ring=0969da&fire=0969da&currStreakNum=24292f&sideNums=24292f&currStreakLabel=0969da&sideLabels=8250df&dates=57606a">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mustafaabdullahai-dev&background=0d1117&border=30363d&stroke=30363d&ring=5ee6b0&fire=5ee6b0&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=5ee6b0&sideLabels=79c0ff&dates=6e7681" alt="GitHub streak">
</picture>

</div>

<br/>

<!-- Footer banner. Match the palette of the header. -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/footer-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/footer-light.svg">
  <img src="https://raw.githubusercontent.com/mustafaabdullahai-dev/mustafaabdullahai-dev/main/assets/footer-dark.svg" alt="exit 0 — thanks for stopping by">
</picture>

</div>
