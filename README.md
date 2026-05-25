<h1 align="center">Selman Güneş</h1>

<p align="center">
  <i>Software & systems builder </i><br/>
  <sub>Istanbul · MS Software Engineering @ Boğaziçi · BS Management Engineering @ ITU</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Building-things%20that%20ship-7C3AED?style=for-the-badge&logo=rocket&logoColor=white" />
  <img src="https://img.shields.io/badge/Istanbul-🇹🇷-EF4444?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Public-12%20repos-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Private-42%20repos-6B7280?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

### 👋 About

I came into software from a management engineering background. Started learning **Python and C# in 2018** during undergrad, did my first real ML work in 2020 (electricity price prediction and energy time-series forecasting for a biogas plant pre-feasibility study), and have been compounding from there. Over the years that turned into Unity, then Web3 indexers, then Go backends and Next.js fullstack, and lately agent evaluation. The connecting thread is that I'd rather understand the whole vertical of a system than only its middle.

At **Ford Otosan** I spent nearly two years on the constraint management and vehicle scheduling side — BI dashboards on **Tableau + Oracle SQL**, **Python and Selenium** for the things people used to do by hand, plus a healthy amount of **Excel/VBA** where it earned its keep. Working with data inside a manufacturing org teaches you fast that the hard part is almost never the model.

Right now I'm an **Assistant Enterprise Architect** at Anadolu Hayat Emeklilik (BPMN, ISO 9001, enterprise process design), building **Frameval** as a side research project on how to actually evaluate agentic coding harnesses, and wrapping the MS at Boğaziçi.

---

### 🗺️ Timeline

```
2018 ─┬─ 📚  Started learning Python and C# during undergrad — first
      │       scripts, first OOP, the usual mix of pain and curiosity.
      │
2020 ─┼─ 🔬  First real ML work: electricity price prediction and energy
      │       time-series forecasting in Python for a biogas plant
      │       pre-feasibility study.
      │
2022 ─┼─ 🎮  Graduated ITU Management Engineering. Unity / C# game
      │       projects on the side, data science internship at Ford Otosan.
      │
2023 ─┼─ ⛓️  Year of Web3: DeFi swap bots, NFT holder analytics, subgraph
      │       indexers, on-chain campaign apps. Joined Ford Otosan full-time
      │       end of the year for constraint management & vehicle scheduling.
      │
2024 ─┼─ 🧱  Ford Otosan in full swing: BI dashboards on Tableau + Oracle
      │       SQL, Python/Selenium automations, Excel VBA. Started the MS
      │       at Boğaziçi. Backend craft on the side — auth services,
      │       Merkle trees in Go. Shipped SUNTON CRM app for Sunton Makina.
      │
2025 ─┼─ 🚀  Co-founded citizen.team as CTO — Go backend, Next.js apps,
      │       k8s/Docker infra, bootstrap agent. Designed The Hive from
      │       scratch for SWE 573 — concept, SRS, solo prototype.
      │
2026 ─┴─ 🤖  Joined Anadolu Hayat Emeklilik as Assistant Enterprise
              Architect — BPMN, ISO 9001, process design. The Hive grew
              into Apiary for SWE 574 — five people, owned CI/CD, backend,
              and PM. Building Frameval on the side. Wrapping the MS.
```

---

### 🛠️ What I'm building

<table>
<tr>
<td width="50%" valign="top">

**🤖 Agents & evaluation**

- **[Frameval](https://github.com/sgunes16/Frameval)** — instead of reducing an agentic coding harness to a single benchmark number, it builds a behavioral profile across multiple dimensions and classifies how each one fails. The goal is to make *"which harness should I use"* a real engineering question instead of a leaderboard click.
- Internal MCP and agent tooling (`citizenteam/mcp`).

**🌐 Product & full-stack**

- **citizen.team** — co-founded as CTO (Oct 2025 – Mar 2026). A full SaaS surface: Go backend with custom Traefik middleware, k8s/Docker infra, a bootstrap agent, Next.js apps for the dashboard, blog, and landing, plus a separate auth service. Core repo (`citizenteam/citizen`) is archived now — but it was a real production build, not a weekend prototype.
- **SUNTON CRM** ([`sunton`](https://github.com/sgunes16/sunton)) — small CRM for Sunton Makina, shipped 2024. Capacitor app — one JS codebase running on web, iOS, and Android, deployed via Netlify. Orders, customers, the stuff they used to track in spreadsheets.

**🐝 The Hive — a community time-bank**

A two-semester arc at Boğaziçi that started as my solo design and ended up a five-person product across web, mobile, and backend.

- **[Solo prototype — SWE 573](https://github.com/sgunes16/573repo)** — I designed the whole thing and authored the SRS: a non-profit time-bank where neighbors trade services valued in hours, not money. You post what you can offer or what you need, agree on a handshake, then rate each other after. A lot of the work was the unsexy stuff — fuzzy locations so people don't dox each other, anonymous vs registered vs admin roles, GDPR-aware data handling, a forum, uptime constraints. First build on Django + PostgreSQL + React + TS.
- **[Apiary — SWE 574 team build](https://github.com/SWE-574/SWE-574-3)** — same idea, scaled to a real product with five people across a web client, a React Native mobile app, and a Django/DRF backend tying it together. I owned CI/CD, backend, and project management — which meant I was equally responsible for the things that shipped and the things that didn't get merged because they failed the pipeline. We ran locally on Docker Compose (Postgres/PostGIS, Redis, MinIO, Nginx), worked feature-branch with required CI gates and PR reviews, and built the social layer end-to-end: offer/request/event lifecycle, search, ratings, badges, push notifications, admin moderation. Most of what I learned this semester wasn't about Django — it was about getting five different schedules and skill levels to converge on a working build.

</td>
<td width="50%" valign="top">

**📊 Data & intelligence**

- **Ford Otosan** — Tableau + Oracle SQL for production scheduling BI, Python and Selenium for automating reports and manual workflows, Excel/VBA where it actually paid off.
- **Energy forecasting (2020)** — Python ML for electricity price prediction and consumption/production time series, used in a biogas plant pre-feasibility report.
- Smaller things in the same family — currency trackers, a vocabulary app, term ML projects.

**⛓️ Web3 & on-chain data**

- USDC cross-chain transfer flows, an EVM indexer on top of reth, subgraph-based marketplace analytics, NFT holder tooling, on-chain campaign integrations. Earlier DeFi swap-bot prototypes live in the same corner.

**🎮 Games & graphics**

- Where I started — small Unity / C# projects, finished and shipped. Followed up with CMPE 485 game programming (shaders included).

</td>
</tr>
</table>

---

### 🎓 Academic

**MS, Software Engineering — Boğaziçi University**

- The Hive — two-semester project arc with Suzan Üsküdarlı: `SWE 573` (solo prototype) → `SWE 574-3 / Apiary` (5-person team build). The full story lives under What I'm building above.
- Other coursework: SWE 580 (`580-HW`, `swe580_term_project_spring26`), SWE 599, CMPE 485.

**BS, Management Engineering — Istanbul Technical University**

**Certifications** — Kanban Master I (Ford Otosan, 2025) · Big Data and Business Analytics (ITU, 2024–2026)

---

### 🧰 Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat&logo=capacitor&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefik-mesh&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white" />
  <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=flat&logo=ethereum&logoColor=white" />
  <img src="https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/VBA-217346?style=flat&logo=microsoft-excel&logoColor=white" />
</p>

---

### 📊 GitHub

> 12 public repos here. The 42 private ones are where the day-to-day, client, and pre-production work actually lives.

---

### 📫 Reach me

<p>
  <a href="mailto:mustafaselmangunes@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
</p>
