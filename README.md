<div align="center">

# Harsh Kumar Singh (HKS)
### Systems, Backend & Applied AI Infrastructure Engineer

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20SDE%20%26%20AI%20INTERNSHIPS-00C853?style=for-the-badge&logo=checkmarx&logoColor=white" />
  <img src="https://img.shields.io/badge/NIT%20RAIPUR-B.Tech%20IT%20'28-0F2027?style=for-the-badge&logo=googlemaps&logoColor=00F7FF" />
  <img src="https://img.shields.io/badge/ThAT%20FELLOW%20'26-TOP%20100%20GLOBAL-6366F1?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/itsmeharshkumarsingh/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:harshkumarsinghofficial@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/itsmeharshkumarsingh"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.youtube.com/@itsmeharshkumarsingh"><img src="https://img.shields.io/badge/YouTube-Tech%20Vault-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</p>

<p align="center">
    <a href="https://codeforces.com/profile/itsmeharshkumarsingh"><img src="https://img.shields.io/badge/Codeforces-Specialist%20(1436)-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" /></a>
  <a href="https://leetcode.com/u/itsmeharshkumarsingh/"><img src="https://img.shields.io/badge/LeetCode-Knight%20(2031)-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="https://www.codechef.com/users/itsmehks"><img src="https://img.shields.io/badge/CodeChef-3%20Star%20(1635)-5B4638?style=for-the-badge&logo=codechef&logoColor=white" /></a>
  <a href="https://atcoder.jp/users/itsmehks"><img src="https://img.shields.io/badge/AtCoder-6%20Kyu%20(800)-222222?style=for-the-badge" /></a>
</p>

</div>

---

## 30-Second Pitch

> I am a **Systems & Backend Engineer** with a strong foundation in **Competitive Programming** and **Distributed AI Infrastructure**. Rather than building high-level wrapper apps, I engineer low-latency backend systems from first principles—combining **Go (Gin) concurrent microservices**, **ACID-compliant transactional databases (`FOR UPDATE` row-level locking)**, and **FAISS vector similarity pipelines** backed by rigorous $O(n \log n)$ algorithmic optimization in **C++**.

---

## TL;DR for Recruiters

| Dimension | Highlights |
| :--- | :--- |
| **Target Roles** | **Software Development Engineer (SDE)** · **Backend & Distributed Systems** · **Applied AI Infrastructure** |
| **Core Architecture** | Sub-millisecond Go (Gin) proxies ($82\mu s$ overhead) · MySQL `START TRANSACTION` & row-level locking · FAISS vector search ($L_2 \le 0.05$) · FastAPI & Docker |
| **Algorithmic Pedigree** | [**Codeforces Specialist (1436)**](https://codeforces.com/profile/itsmeharshkumarsingh) · [**LeetCode Knight (2031)**](https://leetcode.com/u/itsmeharshkumarsingh/) ·  [**CodeChef 3-Star (1635)**](https://www.codechef.com/users/itsmehks) · **ICPC Prelims Global Rank 955** |
| **Global Recognition** | **ThAT Fellow '26 (Top 100 Globally)** — AE Global Summit 2026 (London), collaborating with researchers from Google DeepMind, Microsoft, NVIDIA & Oxford |
| **Experience** | **Problem Setter Intern @ AskSenior** (Authoring CP problems, test cases & editorials) · [**Technical Creator**](https://www.youtube.com/@itsmeharshkumarsingh) (25+ C++ & OA optimization breakdowns) |
| **Education** | **B.Tech in Information Technology**, National Institute of Technology (NIT) Raipur (2024–2028 · **CGPA: 8.38/10.0**) |
| **Direct Contact** | [harshkumarsinghofficial@gmail.com](mailto:harshkumarsinghofficial@gmail.com) · [LinkedIn](https://www.linkedin.com/in/itsmeharshkumarsingh/) · +91-9631462130 |

---

## 🏗️ Flagship Systems & Architecture

```mermaid
flowchart LR
    Client([Merchant Traffic]) --> Proxy[Go / Gin Edge Proxy<br/>82µs Routing · HS256 JWT]
    Proxy --> Engine[FastAPI Core Compute<br/>Async Worker Pool]
    Engine --> FAISS[(FAISS Vector Index<br/>L2 Distance ≤ 0.05)]
    Engine --> Gemini[Gemini 2.5 Flash<br/>Dispute Adjudicator]
    Engine --> DB[(PostgreSQL / MySQL<br/>ACID · Row-Level Locks)]
```

| System | Architecture & Engineering Constraints | Tech Stack |
| :--- | :--- | :--- |
| [**PayPal Merchant AI Gateway & Dispute Adjudicator**](https://github.com/itsmeharshkumarsingh/fintech-polyglot-platform) | • Decoupled ingress proxy routing from core compute for PayPal Sandbox v2 orders.<br/>• Achieved **$82\mu s$ routing overhead** via concurrent Go (Gin) goroutines & stateless **HS256 JWT** auth.<br/>• Engineered an async retrieval pipeline using **FAISS vector search ($L_2 \le 0.05$)** and **Gemini 2.5 Flash** to query historical fraud precedents. | `Go` `Gin` `Python` `FastAPI` `FAISS` `Gemini 2.5 Flash` `PostgreSQL` `Docker` |
| [**HKS Bank & Co.**](https://github.com/itsmeharshkumarsingh/HKS-Bank-Co)<br/>*(Enterprise SPA Banking)* | • High-frequency financial portal guaranteeing strict **ACID compliance** during system failures via **MySQL Stored Procedures** and `START TRANSACTION` protocols.<br/>• Eliminated multi-user race conditions during concurrent fund transfers using **`FOR UPDATE` row-level database locking** and dynamic REST data isolation. | `Node.js` `Express.js` `MySQL` `JavaScript (ES6+)` `HTML5/CSS3` `Chart.js` |
| [**SegDPVisualizer**](https://github.com/itsmeharshkumarsingh/Flat-Subsequence-Segment-Tree-DPVisualizer)<br/>*(Algorithmic Engine)* | • Interactive visualizer demonstrating how **Dynamic Programming**, **Coordinate Compression**, and a **Segment Tree** optimize an $O(n^2)$ recurrence down to **$O(n \log n)$**.<br/>• Features real-time, step-by-step **SVG rendering** of range queries and point updates for the Longest Flat Subsequence problem. | `JavaScript (ES6+)` `HTML5` `TailwindCSS` `SVG` |

---

## 📌 Pinned Repositories

<p align="center">
  <a href="[https://github.com/itsmeharshkumarsingh/fintech-polyglot-platform](https://github.com/itsmeharshkumarsingh/fintech-polyglot-platform)">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=itsmeharshkumarsingh&repo=PayPal-Merchant-AI-Gateway&theme=tokyonight&hide_border=true&border_radius=10" width="48%" />
  </a>
  <a href="[https://github.com/itsmeharshkumarsingh/HKS-Bank-Co](https://github.com/itsmeharshkumarsingh/HKS-Bank-Co)">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=itsmeharshkumarsingh&repo=HKS-Bank-And-Co&theme=tokyonight&hide_border=true&border_radius=10" width="48%" />
  </a>
</p>
<p align="center">
  <a href="[https://github.com/itsmeharshkumarsingh/Flat-Subsequence-Segment-Tree-DPVisualizer](https://github.com/itsmeharshkumarsingh/Flat-Subsequence-Segment-Tree-DPVisualizer)">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=itsmeharshkumarsingh&repo=SegDPVisualizer&theme=tokyonight&hide_border=true&border_radius=10" width="48%" />
  </a>
</p>

---

## 🏆 Honors & Competitive Milestones

- **ThAT Fellow '26 (Top 100 Globally):** Selected by *Thinking About Thinking* for the **AE Global Summit 2026 (London)**, collaborating with researchers from **Google DeepMind, Microsoft, NVIDIA, and Oxford**.
- **National Semifinalist — Flipkart GRiD 8.0:** Advanced among **1,65,729+ registrations** nationwide in a multi-stage software engineering crucible.
- **Winner — CodeRush '25:** 1st Place at the national-level competitive programming contest during **Infotsav '25 at ABV-IIITM Gwalior**.
- **Global Rank 955 — ICPC 2025–26 Prelims:** Led team to secure AC solutions across complex algorithmic challenges.
- **100th Percentiler (Physics) — JEE Mains 2024:** Secured a perfect 100 percentile in Physics (**98.82 Percentile Overall**).

---

## Experience & Technical Leadership

- **Problem Setter Intern @ AskSenior** *(Sep 2026 – Mar 2027)*
  - Authored and curated original competitive programming problems, rigorous corner-case test suites, and algorithmic breakdowns using **Obsidian**.
- [**Technical Content Creator @ YouTube (`@itsmeharshkumarsingh`)**](https://www.youtube.com/@itsmeharshkumarsingh) *(Aug 2025 – Present)*
  - Produced **25+ deep-dive video breakdowns** analyzing C++ execution efficiency ($10^8\text{ ops/sec}$), bitwise optimizations, and advanced **DP, Graphs, and Segment Tree** paradigms for Tier-1 OA preparation.

---

## 🛠️ Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,go,python,java,js,nodejs,express,fastapi,mysql,postgres,docker,git,github,linux,tailwind,html,css,obsidian&perline=10" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go%20(Gin)-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS%20Vector%20Search-4267B2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Gemini%202.5%20Flash-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/ACID%20%26%20Row--Level%20Locking-003545?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/HS256%20JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms-FFA116?style=for-the-badge" />
</p>

---

## 📊 GitHub Telemetry

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itsmeharshkumarsingh&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</p>
