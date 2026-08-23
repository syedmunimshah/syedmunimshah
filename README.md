<h1 align="center">Syed Abdul Munim Ali Shah</h1>
<h3 align="center">AI Engineer · Generative AI · .NET &amp; SQL Backend Engineer</h3>
<p align="center">LangChain · LangGraph · RAG · MCP · Playwright · FastAPI · C# · ASP.NET Core · SQL Server</p>

<p align="center">
  <a href="https://www.linkedin.com/in/syedabdulmunimalishah/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://abdulmunim.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:syedmuunim@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Claude_101-Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude 101 — Anthropic" />
</p>

---

### About

🤖 **AI Engineer** with hands-on experience building production **LLM applications**, **RAG pipelines**, and large-scale **data extraction systems**. Proficient in **LangChain**, **LangGraph**, and **MCP**-based AI tooling, with web scraping in **Playwright** and **FastAPI** microservices. I use **Claude Code** and **Cursor** daily, and review everything they produce. Certified **Claude 101** (Anthropic).

Backend engineering base in **C#**, **ASP.NET Core** and **SQL Server** — REST API design, JWT authentication and SQL query optimization. I started out in front-end development and moved into backend, which means I design APIs with a clear picture of how they'll actually be consumed.

Most of my professional work has been in **ERP / HCM systems** — the kind of domain where data integrity, transactional correctness, and query performance genuinely matter. I care about clean layered architecture, writing code that's straightforward to test, and not leaving landmines for whoever maintains it next.

I ship what I build: my projects run in CI, build as Docker images, and deploy to **Azure App Service** from GitHub Actions — not just `dotnet run` on a laptop.

💼 **Open to .NET backend roles** — Karachi, remote (Pakistan), or remote international.

---

### 🚀 Featured Project

#### [EdgeCart](https://github.com/syedmunimshah/Ecommerece-Backend-Dotnet-and-Fronted-React) — Full-Stack E-Commerce Marketplace

A multi-role marketplace (Customer / Seller / Admin) built end-to-end with ASP.NET Core 8 and Next.js 16, deployed to Azure.

- **Clean 3-layer architecture** — Controllers → Services → Repositories, with a generic repository and unit-of-work abstraction
- **Transaction-safe checkout** — order creation, stock validation, and stock decrement commit atomically or roll back together
- **Stripe payment integration** — hosted Checkout with a server-authoritative charge amount and signed webhook confirmation, so the client can never influence what gets charged
- **Role-based authorization** — JWT auth with distinct Admin / Seller / Customer permissions, plus OTP-based password reset
- **Full CI/CD pipeline** — GitHub Actions builds and tests the API, lints and typechecks the frontend, validates the Docker images, then deploys both apps to **Azure App Service**. Deploy jobs skip cleanly when the publish-profile secrets are absent, so a fork still gets working CI with zero configuration.
- **Production concerns handled** — structured logging with Serilog, a global exception handler returning RFC-7807 ProblemDetails, and a health endpoint

`C#` · `ASP.NET Core 8` · `EF Core` · `SQL Server` · `Stripe` · `Next.js 16` · `React 19` · `TypeScript` · `Docker` · `Azure` · `GitHub Actions`

---

### 📁 Other Projects

- **RAG Knowledge Assistant** — document assistant with pgvector semantic search and LangGraph multi-step reasoning pipelines; prompt and context engineering to improve retrieval accuracy over large knowledge bases. `Python` · `LangChain` · `LangGraph` · `pgvector`
- **Deep Research Agent System** — autonomous deep agents with LangGraph for multi-step planning, tool use and self-correcting reasoning loops; specialised sub-agents with task decomposition, long-horizon memory and RAG-backed retrieval. `Python` · `LangGraph` · `Deep Agents` · `RAG`
- **[EdgeCart](https://github.com/syedmunimshah/Ecommerece-Backend-Dotnet-and-Fronted-React)** — full-stack ecommerce marketplace with a layered API / Service / Repository architecture, JWT auth with role-based authorization, and Stripe Checkout with webhook confirmation. `C#` · `ASP.NET Core` · `Next.js` · `SQL Server`
- **Enterprise Data Warehouse & Analytics** — 3-layer warehouse (bronze, silver, gold) integrating ERP and CRM sources, with automated ETL and star/snowflake schemas. `SQL Server` · `SSIS` · `T-SQL` · `Git`
- **[Spendly](https://github.com/syedmunimshah/spendly)** — expense tracker: log spending, group it by category, and filter by date range. Built spec-first, one feature at a time, with a test suite covering every route. Four dependencies, no ORM, no CSS framework, no build step. `Python` · `Flask` · `SQLite` · `pytest`
- **[Portfolio](https://abdulmunim.netlify.app/)** — my personal site, hand-built as a static page with no framework and no build step. `HTML` · `CSS` · `Vanilla JS` · `Netlify`

---

### 💼 Experience

**AI Engineer / Software Engineer** — *Abic Partners* · 2025 – Present
LLM-powered review-intelligence pipelines pulling brand name, star rating and full review detail from Google, Trustpilot and Clutch with Playwright; an executive lead-extraction system over LinkedIn; both served as FastAPI microservices. Claude Code automations, agents and MCP servers. Alongside that, ERP and HCM modules in ASP.NET Core, SQL Server query optimisation, Kendo UI, and Jenkins release deployments.

**Software Engineer** — *Syscrowd* · 2023 – 2025
Secure REST APIs with ASP.NET Core and EF Core. JWT authentication with role-based authorization, stored-procedure tuning in SQL Server, automated Excel import / PDF generation / email workflows, and IIS deployments.

**Frontend Developer** — *Adroit Global Technology Services · The Next Rex* · 2021 – 2023
Converted PSD designs into mobile-responsive, cross-browser client websites with HTML, CSS, Bootstrap, JavaScript, React and jQuery.

**B.Sc. Computer Science** — Iqra University, Karachi · 2017 – 2021

---

### 🛠 Tech Stack

**Backend**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-02569B?style=flat-square&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Database**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**AI Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-000000?style=flat-square&logo=databricks&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_%26_Context_Engineering-4B32C3?style=flat-square)

**Cloud & DevOps**

![Azure](https://img.shields.io/badge/Azure_App_Service-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![IIS](https://img.shields.io/badge/IIS_Deployment-0078D6?style=flat-square&logo=microsoft&logoColor=white)

**Tools & Practices**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Repository Pattern](https://img.shields.io/badge/Repository_Pattern-6DB33F?style=flat-square)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)

---

### ☁️ Shipping & Deployment

Building the feature is half the job. The other half is getting it to production and keeping it there.

- **CI on every push and pull request** — GitHub Actions restores, builds and tests the .NET solution, and lints, typechecks and builds the Next.js frontend, so a broken commit is caught before review rather than after merge
- **Azure App Service deployment** — API and frontend deploy as separate apps straight from the pipeline, using publish profiles held as repository secrets
- **Containerised** — Dockerfiles for both apps plus a `docker-compose.yml`, with the pipeline building the images on every run so the local setup can't silently rot
- **Configuration that survives the move** — build-time versus runtime environment variables handled deliberately, so a production build never bakes in a localhost URL
- Earlier work: **Jenkins** build/release pipelines and **IIS** deployments for enterprise clients

---

### 🤖 Working with AI Tools

I use **Claude Code** and **Cursor** as part of my normal workflow — and I review everything they produce before it lands.

- **AI-assisted delivery, human-owned decisions** — the architecture, the trade-offs and the final review are mine; the tooling speeds up the typing, not the thinking
- **Spec-first workflow** — [Spendly](https://github.com/syedmunimshah/spendly) is built one written spec at a time: define the behaviour, generate tests from the spec rather than the implementation, then implement against them
- **Automated review passes** — separate security and code-quality review agents run over each change before it's merged, on top of my own reading of the diff
- Comfortable judging where these tools help and where they don't — which is increasingly part of the job rather than a novelty

**Building with AI, not just coding with it** — alongside using AI tooling, I build AI features into .NET applications:

- **RAG pipelines** — document ingestion with chunking and embedding generation, **pgvector** semantic search, and re-ranking before answer synthesis, with **LangGraph** multi-step reasoning
- **Deep agents** — multi-step planning, tool use and self-correcting reasoning loops, with specialised sub-agents, task decomposition and long-horizon memory
- **Review-intelligence pipelines** — brand name, star rating and full review detail pulled from Google, Trustpilot and Clutch with **Playwright**, served as **FastAPI** microservices with async workers, retry/backoff and anti-bot handling
- **MCP servers** — exposing semantic search over enterprise documents to AI clients like Claude Code and Cursor

📜 **Certified:** Claude 101 — Anthropic

---

### 💡 What I Work On

- Designing and building **RESTful APIs** with ASP.NET Core
- **Database design and query optimization** in SQL Server — indexing, execution plans, cutting down slow reports
- **Authentication and authorization** — JWT, role-based access control, secure password handling
- Applying patterns that keep codebases maintainable: **Repository**, **Unit of Work**, **Dependency Injection**, **DTO mapping**
- **Integrating third-party services** — payment gateways, email/SMTP, file storage
- **CI/CD and cloud deployment** — GitHub Actions, Docker, Azure App Service

---

### 📊 GitHub

<p align="left">
  <img src="https://img.shields.io/github/followers/syedmunimshah?style=for-the-badge&logo=github&label=Followers&labelColor=181717&color=0A66C2" alt="Followers" />
  <img src="https://img.shields.io/github/stars/syedmunimshah?affiliations=OWNER&style=for-the-badge&logo=github&label=Stars&labelColor=181717&color=0A66C2" alt="Stars" />
  <img src="https://img.shields.io/github/last-commit/syedmunimshah/Ecommerece-Backend-Dotnet-and-Fronted-React?style=for-the-badge&logo=git&label=Last%20commit&labelColor=181717&color=0A66C2" alt="Last commit" />
</p>

---

<p align="center">
  📫 Reach me at <a href="mailto:syedmuunim@gmail.com"><b>syedmuunim@gmail.com</b></a>
</p>
