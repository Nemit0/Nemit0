<!--
README for GitHub profile
Author: Nemit
Notes:
1) Replace placeholders like YOUR_GH_USERNAME, YOUR_EMAIL, YOUR_LINKEDIN, and YOUR_BLOG if you want.
2) To enable the GitHub Stats widgets, search for "Optional: GitHub Widgets" below and replace YOUR_GH_USERNAME.
3) This README is designed to be readable in both light and dark mode.
-->

<h1 align="center">Hi, I am Nemit 👋</h1>

<p align="center">
  <b>Data Science · Machine Learning · Deep Learning · LLM</b><br/>
  Mathematics major | Python-first | Building reliable, explainable, and fast data products
</p>

<p align="center">
  <a href="mailto:YOUR_EMAIL">Email</a> •
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN">LinkedIn</a> •
  <a href="https://YOUR_BLOG">Blog</a>
</p>

---

### 👨‍💻 About me

- I craft end‑to‑end systems: data pipelines → models → APIs → UX.
- Comfortable across backend and frontend, with a strong math foundation.
- Daily driver: Ubuntu on laptop; additional Ubuntu GPU server (RTX 3080 with CUDA) reachable over ZeroTier.
- Primary editor: Vim; also use VS Code when it makes sense.
- Timezone: Asia/Seoul (UTC+9).

---

### 🚀 What I am building

**MangoBerry — restaurant review and recommendation platform**
- Backend: FastAPI with JWT auth, Nginx reverse proxy, and Dockerized deployment.
- Search: Elasticsearch for restaurant, review, and keyword retrieval with tuned analyzers and scoring.
- Data: MySQL for relational entities, MongoDB for documents and media.
- Personalization: Preference‑aware scoring that blends user signals with keyword analysis.
- Frontend: React with a map‑based UI (Kakao Maps), word clouds, and profile features (follows, compatibility ratings).
- Infra: AWS EC2 (service and database instances), containerized services, SSL termination, and CI‑ready layout.
- Recent experiments: Python 3.13‑t (nogil) Docker builds to test throughput under concurrency.

> I enjoy turning messy, real‑world requirements into clear interfaces and measurable outcomes.

---

### 🧰 Tech I use

- **Languages:** Python, TypeScript/JavaScript, a bit of C
- **ML / DL / LLM:** PyTorch, Transformers, scikit‑learn, evaluation and prompt engineering workflows
- **Backend:** FastAPI, Uvicorn, Pydantic, SQLAlchemy
- **Data Stores:** MySQL, MongoDB, Elasticsearch
- **Frontend:** React, Vite/CRA, modern CSS tooling
- **DevOps / Infra:** Docker, Docker Compose, Nginx, AWS EC2, ZeroTier
- **OS / Tools:** Ubuntu, Vim, VS Code, Graphviz (for diagrams)

---

### 🗺️ Selected architecture highlights

- **Service boundary:** React SPA served by Nginx; `/api/*` requests proxied to FastAPI.
- **Data boundary:** OLTP in MySQL, document storage and media in MongoDB, search and analytics in Elasticsearch.
- **Observability:** Structured logs at the API boundary; query timing and search diagnostics to iterate on relevance.
- **Deployment:** Docker images per service; environment‑driven configuration; production Nginx with request size caps aligned to API.

---

### 📌 Featured work

- **MangoBerry (full‑stack)**  
  Map‑centric restaurant discovery with personalized ranking, ES‑powered search, and social features.  
  *Stack:* React, FastAPI, Elasticsearch, MongoDB, MySQL, Docker, Nginx, AWS, Kakao Maps.  
  Repos:  
  - Backend: `https://github.com/YOUR_GH_USERNAME/mangoberry-backend`  
  - Frontend: `https://github.com/YOUR_GH_USERNAME/mangoberry-frontend`  

- **Dev environment scripts (Linux)**  
  Bootstrap scripts for fresh Debian/Ubuntu to install Docker, Docker Compose, Git; convenience utilities for EC2 networking, Nginx proxy templates, and APT source fixes.  
  Repo: `https://github.com/YOUR_GH_USERNAME/dev-scripts`

> If you would like a demo or architecture graph, I usually render diagrams with Graphviz for precision and repeatability.

---

### 🧪 Interests

- Retrieval‑augmented generation (RAG) with robust indexing and evaluation loops  
- Search relevance: analyzers, scoring, and user modeling  
- Fast Python in production: asyncio, multiprocess strategies, and (selectively) nogil builds  
- Practical MLOps: data contracts, regression tests for models and prompts, and reproducible deployments

---

### 🤝 I am open to

- Collaborations on search, recommendations, or LLM evaluation tooling  
- Consulting on FastAPI backends, Elasticsearch integration, and Dockerized deployments  
- Performance tuning for Python services and query optimization

---

### 📬 Contact

- The fastest way to reach me is by email: **YOUR_EMAIL**  
- I also check **LinkedIn**: `https://www.linkedin.com/in/YOUR_LINKEDIN`  
- Optional: personal blog or notes: `https://YOUR_BLOG`

---

### 🧩 Optional: GitHub widgets (uncomment and replace YOUR_GH_USERNAME)

<!--
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GH_USERNAME&show_icons=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GH_USERNAME" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GH_USERNAME&layout=compact" alt="Top languages" />
</p>
-->

---

<sub>Thanks for stopping by. I build, measure, and iterate — and I document decisions so others can pick up where I left off.</sub>
