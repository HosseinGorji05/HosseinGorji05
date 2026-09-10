<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=4000&pause=1500&color=2563EB&center=true&vCenter=true&width=700&lines=Hossein+Gorji;Full-Stack+Developer;Computer+Science+%40+York+University;Applied+AI+with+real+guardrails)

<p>
  <a href="https://hosseingorji05.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-hosseingorji05.github.io-0aa?style=flat-square" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/hossein-gorji-745488281"><img src="https://img.shields.io/badge/LinkedIn-Hossein-0077b5?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:hoseingorji1383@gmail.com"><img src="https://img.shields.io/badge/Gmail-hoseingorji1383@gmail.com-ea4335?style=flat-square&logo=gmail" alt="Gmail" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Open%20to%20co--op%20%26%20internship-2027-2563EB?style=flat-square" alt="Open to co-op 2027" />
</p>

</div>

---

### About

Full-stack developer and **3rd-year Computer Science student** at **York University** (Co-op Program), Toronto. I ship tested, production-shaped software for real clients, and build applied-AI systems with real guardrails around model output.

- 🎓 **B.Sc. Honours Computer Science**, York University — expected **May 2028**, enrolled in the Co-op Program
- 🤖 **Executo** — self-correcting coding agent passing **80%** of the HumanEval benchmark
- ✅ **Expense Tracker API** — Java Spring Boot API at **91% line coverage** across 27 tests
- 🏆 **3rd of 20+ teams** (296 participants) at Cursor Hackathon Toronto
- 💼 Freelance developer — comfortable owning a feature end-to-end and translating technical decisions for non-technical stakeholders
- 📫 **Reach me:** hoseingorji1383@gmail.com
- 🌐 **Languages:** English (full proficiency) · Persian (fluent)

---

### Experience

**Freelance Frontend Developer** · [Grano](https://github.com/HosseinGorji05/grano) &nbsp;·&nbsp; <sub>Aug 2026 – Present · Remote, client in Toronto</sub>

Shipped a production-ready frontend for a non-technical client, passing full cross-browser and **WCAG AA** accessibility QA before launch — translating client requirements into HTML/CSS/vanilla JavaScript bundled via esbuild for a zero-build-step deploy.

<br>

**Freelance Web Developer** · [Kolbeh Restaurant](https://hosseingorji05.github.io/Kolbeh/) <img src="https://img.shields.io/badge/live-2563EB?style=flat-square" align="top" /> &nbsp;·&nbsp; <sub>May 2025 – Jun 2026 · Remote, client in Iran</sub>

Became the client's primary digital storefront — **36 active users and 529 tracked events in a single week** (+80% and +61.3% week-over-week per Google Analytics) — by gathering requirements from a non-technical owner and designing, building, and deploying a fully responsive, QR-code-accessible restaurant website. Eliminated SQL-injection and unauthorized-access vectors in the live backend with parameterized queries across every database call, input sanitization, and CORS policies.

<sub>Node.js · Express · SQLite3 · bcrypt</sub>

---

### Projects

**[Expense Tracker API](https://github.com/HosseinGorji05/Expense-Tracker)** &nbsp;·&nbsp; <sub>Sep 2026 · Solo</sub>

Containerized **Java Spring Boot** REST API (7 endpoints: 5 CRUD, 2 Groq LLM-backed) for expense tracking and AI-assisted budgeting. A 27-test JUnit 5 + Spring MockMvc suite passes at **91% line coverage** in GitHub Actions CI, with all 8 AI-endpoint tests running fully offline via mocked HTTP. Every LLM response is validated against an allow-list, AI-suggested cuts are clamped to real category spend, and a deterministic heuristic takes over when the model errs.

<sub>Java · Spring Boot · Spring Data JPA · JUnit 5 · Groq · Docker</sub>

<br>

**Synergo** &nbsp;·&nbsp; <sub>Jul 2026 · Hack the Valley</sub>

A shared, live conflict-detection dashboard for teammates *and* AI agents editing the same codebase — conflict banners fire **before git does** when two watchers touch the same file. Built as a FastAPI + WebSockets relay with in-memory rooms and broadcast, plus Gemini-backed caption/conflict classification with heuristic fallbacks.

<sub>Python · FastAPI · WebSockets · Gemini</sub>

<br>

**[Executo](https://github.com/HosseinGorji05/Executo)** &nbsp;·&nbsp; <sub>Jun 2026 · Solo</sub>

Self-correcting Python AI agent achieving an **80% strict pass rate** on the HumanEval coding benchmark, verified by a 35-test automated regression suite run on every push/PR across two GitHub Actions workflows. LangGraph orchestrates Llama 3.1 8B via Groq to diagnose and fix failing solutions across up to 4 attempts inside an isolated, network-disabled Docker sandbox — validating every change against the test suite before accepting it.

<sub>Python · LangGraph · Llama 3.1 8B · Groq · Docker</sub>

<br>

**Lens & Love** &nbsp;·&nbsp; <sub>Jun 2026 · Cursor Hackathon Toronto — 3rd of 20+ teams</sub>

Built the invoicing, payments, and voice-command systems for a wedding-photography SaaS MVP — working core product in **30 minutes**, full dashboard by deadline. Live hands-free voice commands ("create invoice," "add overtime," "what's my revenue") drive real-time calculations over custom package tiers, automatic deposit scheduling, and overtime line items.

<sub>React · TypeScript · Tailwind</sub>

<br>

**[Delatio](https://github.com/AdrianShah/NVIDIA-SparkHacks)** &nbsp;·&nbsp; <sub>May 2026 · NVIDIA Spark Hack Toronto · 5-person team</sub>

Enabled **sub-20 ms spatial queries** for the team's autonomous agent by owning the data layer end-to-end — a Python pipeline that ingested, cleaned, and structured raw Toronto Open Data across multiple civic datasets into a queryable in-memory structure.

<sub>Python · pandas · GeoPandas</sub>

---

### Tech Stack

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=python&theme=dark" width="48" height="48" alt="Python" />
      <br>Python
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=ts&theme=dark" width="48" height="48" alt="TypeScript" />
      <br>TypeScript
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=js&theme=dark" width="48" height="48" alt="JavaScript" />
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=java&theme=dark" width="48" height="48" alt="Java" />
      <br>Java
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=c&theme=dark" width="48" height="48" alt="C" />
      <br>C
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=bash&theme=dark" width="48" height="48" alt="Bash" />
      <br>Bash
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=html&theme=dark" width="48" height="48" alt="HTML5" />
      <br>HTML5
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=css&theme=dark" width="48" height="48" alt="CSS3" />
      <br>CSS3
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=react&theme=dark" width="48" height="48" alt="React" />
      <br>React
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=tailwind&theme=dark" width="48" height="48" alt="Tailwind" />
      <br>Tailwind
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=spring&theme=dark" width="48" height="48" alt="Spring Boot" />
      <br>Spring Boot
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=nodejs&theme=dark" width="48" height="48" alt="Node.js" />
      <br>Node.js
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=express&theme=dark" width="48" height="48" alt="Express" />
      <br>Express
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=fastapi&theme=dark" width="48" height="48" alt="FastAPI" />
      <br>FastAPI
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=postgres&theme=dark" width="48" height="48" alt="PostgreSQL" />
      <br>PostgreSQL
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=supabase&theme=dark" width="48" height="48" alt="Supabase" />
      <br>Supabase
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="48" height="48" alt="MySQL" />
      <br>MySQL
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="48" height="48" alt="SQLite3" />
      <br>SQLite3
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=firebase&theme=dark" width="48" height="48" alt="Firestore" />
      <br>Firestore
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=docker&theme=dark" width="48" height="48" alt="Docker" />
      <br>Docker
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="48" height="48" alt="GitHub Actions" />
      <br>Actions
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=maven&theme=dark" width="48" height="48" alt="Maven" />
      <br>Maven
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=git&theme=dark" width="48" height="48" alt="Git" />
      <br>Git
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=github&theme=dark" width="48" height="48" alt="GitHub" />
      <br>GitHub
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=linux&theme=dark" width="48" height="48" alt="Linux" />
      <br>Linux
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=vscode&theme=dark" width="48" height="48" alt="VS Code" />
      <br>VS Code
    </td>
  </tr>
</table>

**AI & GenAI** &nbsp;
<img src="https://img.shields.io/badge/LLM%20Integration-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Prompt%20Engineering-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/LangGraph-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Guardrails%20%26%20Allow--Listing-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Multi--Agent%20Workflows-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Model%20Evaluation-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Groq-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/Gemini-1F2328?style=flat-square&logo=googlegemini&logoColor=white" />

**Testing** &nbsp;
<img src="https://img.shields.io/badge/JUnit%205-1F2328?style=flat-square&logo=junit5&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20MockMvc-1F2328?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Regression%20Suites-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/CI%2FCD%20Test%20Automation-1F2328?style=flat-square" />

**Frontend & data** &nbsp;
<img src="https://img.shields.io/badge/Accessibility%20WCAG%20AA-1F2328?style=flat-square&logo=accessibleicon&logoColor=white" />
<img src="https://img.shields.io/badge/Responsive%20Design-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/pandas-1F2328?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/GeoPandas-1F2328?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Cursor-1F2328?style=flat-square" />
<img src="https://img.shields.io/badge/esbuild-1F2328?style=flat-square&logo=esbuild&logoColor=white" />

---

### Activity

<div align="center">

<a href="https://github.com/HosseinGorji05">
<img height="165" alt="Contribution streak" src="https://streak-stats.demolab.com/?user=HosseinGorji05&hide_border=true&background=00000000&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&sideLabels=808080&dates=808080&stroke=808080&sideNums=808080&currStreakNum=2563EB" />
</a>
<a href="https://github.com/HosseinGorji05">
<img height="165" alt="Most used languages" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=HosseinGorji05&layout=compact&hide_border=true&bg_color=00000000&title_color=2563EB&text_color=808080&langs_count=6" />
</a>

<img alt="Contribution graph" src="https://ghchart.rshah.org/2563EB/HosseinGorji05" width="90%" />

</div>

---

<div align="center">

<sub>Currently looking for a **co-op or internship in 2027**.<br />
If you're building something where the backend has to hold up and the front-end has to feel right, I'd like to hear about it.</sub>

<br /><br />

<details>
<summary>Profile stats</summary>
<br />

![Profile views](https://komarev.com/ghpvc/?username=HosseinGorji05&style=flat-square&color=2563eb)

</details>

</div>
