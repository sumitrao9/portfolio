# Sumit Yadav — Portfolio

**Python Engineer — AI Agent Infrastructure, MCP Tooling & Django APIs**

📍 Gurgaon, India (IST, UTC+5:30)  
📧 sumitrao9991@gmail.com  |  📱 +91 8569901583  
🔗 [github.com/sumitrao9](https://github.com/sumitrao9)  |  [linkedin.com/in/sumit-yadav-97871532b](https://linkedin.com/in/sumit-yadav-97871532b)

---

SUMIT YADAV

Python Engineer — AI Agent Infrastructure, MCP Tooling & Django APIs

Gurgaon, India (IST, UTC+5:30)  ·  +91 8569901583  ·  sumitrao9991@gmail.com

github.com/sumitrao9  ·  linkedin.com/in/sumit-yadav-97871532b

Open to remote contract or internship — 15–20 hrs/week, async-first, comfortable working async with US/EU clients.

SUMMARY

Python engineer building production AI-agent infrastructure and Django APIs. Specialises in the parts of agent tooling that break in practice: runaway context cost, selectors that rot silently, and money bugs in invoicing systems. MCA (Cloud Computing) student with a shipped internship background and multiple self-directed projects spanning browser agents, MCP tooling, desktop apps, and full-stack platforms.

PROJECTS

Hound  Python · MCP · Playwright · SQLite · 59 tests · Docker · CI/CD  ·  Sept 2026

•  Token-budgeted MCP browser automation server achieving 99.2% token reduction ($1,050 → $10.50 per 10-step flow) via delta snapshots and hard token ceilings; 7 focused tools vs 50-90 in alternatives.

•  AdaptiveBudget learns optimal token budgets per site/action from usage; SemanticDiffer returns intent-aware diffs (form_update, interaction, navigation) with agent action hints; PredictiveHealer provides ML-style explainable healing with confidence intervals, feature importance, and cross-site pattern transfer.

•  SessionTokenOptimizer predicts optimal budgets/profiles from cross-action history; CrossSiteKnowledgeBase transfers verified selector patterns across sites; Rate limiting, SSRF protection, configurable timeouts; 59 tests (38 unit + 10 URL validation + 11 live browser), Docker, CI/CD.

ClientFlow  Django 5 · DRF · PostgreSQL · JWT · ReportLab · Docker · 33 tests  ·  Sept 2026

•  Freelance invoicing API where financial invariants are enforced in the model, not left to callers: payments clamp to the outstanding balance so no code path can produce a negative balance, and settled invoices are immutable to prevent re-billing paid work.

•  Invoice numbers allocated per account from the owning user row under row-level locking, so concurrent requests cannot receive the same number and tenants cannot collide.

•  Two-layer multi-tenancy (queryset scoping plus an object-permission re-check), tested against another user's records being unreadable, unwritable and undeletable. Ships with Docker, PostgreSQL, OpenAPI and CI.

Donut OS  Python · 8,400 lines · 24 modules · stdlib-first  ·  2026

•  Autonomous browser agent: persistent anti-detect browser, durable SQLite task queue, cron scheduler and local web dashboard, built almost entirely on the standard library — only cryptography and websockets as hard dependencies.

•  Self-healing scraper layer that repairs broken selectors and writes fixes back to a selector store; 23 pluggable sources, AES-GCM credential vault backed by the OS Keychain, and an append-only audit log on destructive actions.

Arix  Electron · React · TypeScript · Drizzle · Playwright  ·  Jul–Aug 2026

•  Desktop developer workbench: 58 main-process services, 22 renderer modules, ~50 database tables and 155+ typed IPC handlers, with unit and end-to-end test coverage.

Job Hunter OS  FastAPI · React + Vite · TypeScript · SQLite · Docker  ·  2026

•  Local-first job application tracker with multi-source job discovery, intelligent matching, resume tailoring, cover letter generation, and kanban-style application pipeline.

•  Human-in-the-loop apply workflow ensures nothing is submitted automatically. Pluggable LLM service with local Ollama support for privacy-first operation.

JARVIS  Python · macOS · Stdlib only  ·  2026

•  Personal AI assistant controlling macOS (apps, screen, files, shell) with zero external dependencies. Features voice interaction, on-screen UI, autonomous goal planning, and agentic coding capabilities.

•  Uses Accessibility API for UI control and screen perception; supports free web LLMs or local DeepSeek proxy with graceful fallback.

EXPERIENCE

Python Django Developer Intern  SSDN Technologies, Gurgaon  ·  Sept 2023 – Feb 2024

•  Built and maintained RESTful APIs with Django REST Framework for web and mobile frontends, and developed responsive interfaces in React, HTML, CSS and Tailwind.

•  Contributed unit and integration tests, fixed defects, and shipped features on existing and open-source-based projects.

•  Worked in Agile sprints using version control, taking part in code reviews and pairing with senior developers.

TECHNICAL SKILLS

Languages: Python, TypeScript, JavaScript, SQL, HTML5, CSS, C++, R

Backend & AI agents: Django, DRF, FastAPI, REST API design, JWT, Celery, Redis, MCP servers, browser automation, self-healing scrapers, Playwright, token optimization, adaptive budgeting, semantic diffing

Frontend & desktop: React, Tailwind CSS, Bootstrap, Electron, shadcn/ui, Monaco, TanStack Query

Data, cloud & tooling: PostgreSQL, SQLite, Drizzle ORM, Redis, AWS, Docker, Git, GitHub Actions, pytest, Vitest

Additional: Database management, Brand development, Strategic planning and analysis, Testing, Debugging, Agile collaboration

LANGUAGES

Hindi: Bilingual/Native Proficiency (C2)

English: Advanced Proficiency (C1)

Punjabi: Advanced Proficiency (C1)

CERTIFICATIONS

Certified Python Intern  SSDN Technologies  ·  Sept 2023 – Feb 2024

EDUCATION

Master of Computer Applications (MCA) — Cloud Computing  Shoolini University, Solan  ·  Aug 2026 – 2028 (expected)

•  Coursework: Data Structures & Algorithms, Object-Oriented Programming, Web Technologies, Exploratory Data Analysis, Discrete Mathematics, Cloud Computing.

Bachelor of Arts, Economics  Gurgaon University  ·  2020 – 2023


---

*Open to remote contract or internship — 15–20 hrs/week, async-first, comfortable working async with US/EU clients.*
