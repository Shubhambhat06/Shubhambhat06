<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&section=header&text=Shubham%20Bhat&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI/ML%20Enthusiast%20%C2%B7%20Security%20Researcher%20%C2%B7%20PES%20University&descAlignY=55&descSize=18&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=C44FFF&center=true&vCenter=true&width=650&lines=Building+NL-SIEM+%40+PESU+C-ISFCR;91.4%25+Syntactic+Validity+%7C+241-Record+Benchmark;Turning+%22looks+correct%22+into+%22is+correct%22" />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-bhat-aab037344/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhambhat003@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shubhambhat06)
![Profile Views](https://komarev.com/ghpvc/?username=Shubhambhat06&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 👋 About

I like problems where the answer that *looks* right and the answer that *is* right quietly diverge. Most recently that's meant a year inside a SOC watching detection rules pass every check and catch nothing — so I built a framework that makes that failure structurally impossible.

<div align="center">

![Status](https://img.shields.io/badge/SELF--SCAN-VERIFIED-brightgreen?style=for-the-badge)
![Confidence](https://img.shields.io/badge/CONFIDENCE-94%25-blue?style=for-the-badge)
![Hallucination](https://img.shields.io/badge/HALLUCINATION-NONE_DETECTED-ff69b4?style=for-the-badge)

*ran my own MITRE ATT&CK classifier on this bio. it verified clean.*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🧭 Coverage Map

Same principle my research runs on, applied to myself — claims broken out by how verified they actually are, not flattened into one badge wall.

| Domain | Status | Evidence |
|---|:---:|---|
| Security / Detection Engineering | ![](https://img.shields.io/badge/-VERIFIED-brightgreen?style=flat-square) | NL-SIEM in production SOC use, live Elastic + Wazuh connectors |
| Machine Learning / Retrieval | ![](https://img.shields.io/badge/-VERIFIED-brightgreen?style=flat-square) | CodeBERT fine-tuning, FAISS @ 51K vectors, 0.80 MRR@10 |
| Full-Stack (React/FastAPI/Flask) | ![](https://img.shields.io/badge/-VERIFIED-brightgreen?style=flat-square) | 3 shipped projects, working frontend + API each |
| Geospatial Analysis | ![](https://img.shields.io/badge/-VERIFIED-brightgreen?style=flat-square) | UIDAI pipeline, GeoPandas, fuzzy entity resolution |
| Large-scale distributed systems | ![](https://img.shields.io/badge/-FAMILIAR-yellow?style=flat-square) | Coursework + personal-project scale |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 🔬 Featured Research — NL-SIEM

> **Detecting What You Think You Detect: Cross-Platform SIEM Query Generation and Prevention of ATT&CK Coverage Drift using Intermediate Representation and LLMs**
> *Bhat, S.D. & Swetha P. — preprint under review, PESU C-ISFCR*

A coverage heatmap can show green while the detection behind it silently stops working the moment it's ported to another SIEM. I named that failure mode **ATT&CK Coverage Drift** and built a multi-agent LLM framework that prevents it structurally — ATT&CK classification (including cases where one description maps to more than one technique) happens *before* any query is generated, folded into a platform-agnostic IR, then handed to independent translation agents.

<div align="center">

![](https://img.shields.io/badge/Syntactic_Validity-91.4%25-brightgreen?style=for-the-badge)
![](https://img.shields.io/badge/BLEU--4-0.67-blue?style=for-the-badge)
![](https://img.shields.io/badge/Dataset-241_Records-orange?style=for-the-badge)
![](https://img.shields.io/badge/Platforms-5_SIEMs-9c27b0?style=for-the-badge)
![](https://img.shields.io/badge/Execution--Backed-Validated_in_SOC-critical?style=for-the-badge)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🚀 Projects

<details>
<summary><b>🔎 Semantic Code Search Engine</b> — CodeBERT bi-encoder + FAISS retrieval at 51K-snippet scale</summary>
<br>

**Problem:** keyword search doesn't understand code semantics — "sort a list" misses idiomatic implementations sharing no vocabulary with the query.

**Approach:** fine-tuned a CodeBERT bi-encoder with an InfoNCE contrastive objective on CodeSearchNet pairs (Python, Java, Go), indexed with FAISS `IndexFlatIP`.

**Result:** 8.06ms median / 9.76ms P95 retrieval latency, 0.80 MRR@10 — competitive with commercial code search. Shipped with FastAPI + React (ranked results, inline previews, per-language filtering).

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-4B8BBE?style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
</details>

<details>
<summary><b>🗺️ Geospatial Analysis of Aadhaar Service Demand & Infrastructure Stress</b> — resolving 42/58 inconsistent district names nationally</summary>
<br>

**Problem:** UIDAI's datasets use inconsistent state/district naming across sources, breaking joins against GeoJSON boundaries.

**Approach:** Unicode normalization + RapidFuzz `token_sort_ratio` (threshold=85); four ratio-based infrastructure stress metrics with z-score/IQR outlier detection.

**Result:** auto-resolved 42 of 58 name variants. Finding: high-volume districts do *not* uniformly show high update pressure — surfaced non-obvious policy-relevant gaps.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat-square)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
</details>

<details>
<summary><b>🛡️ Web Vulnerability Scanner</b> — multi-threaded BFS crawler with LLM-generated remediation reports</summary>
<br>

**Problem:** vulnerability scan output is usually a raw findings dump a developer has to interpret themselves.

**Approach:** multi-threaded BFS crawler with a thread-safe visited-set; SQLi/XSS payload injection with pattern-matched response analysis to cut false positives.

**Result:** OpenAI API turns findings into readable explanations with prioritized remediation, output as structured JSON for CI/CD gating.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
</details>

<details>
<summary><b>🎬 Movie Box Office Revenue Prediction</b> — XGBoost + Random Forest ensemble on right-skewed TMDB data</summary>
<br>

**Problem:** box office revenue is heavily right-skewed, breaking naive regression and letting tail blockbusters dominate the loss.

**Approach:** log-scale transform, cross-validated XGBoost + Random Forest ensemble with grid-search tuning; multi-hot genre encoding, cyclical seasonality, budget normalization.

**Result:** minimized RMSE while mitigating overfitting on outlier blockbuster revenue.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-006ACC?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
</details>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 🧰 Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,java,c,js,react,fastapi,flask,tailwind,git,docker,linux,postgres" />
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🎯 Currently

- 🔭 Extending NL-SIEM's multi-technique ATT&CK classification + Splunk/QRadar/Sentinel connectors
- 🛡️ SOC Intern at **PESU C-ISFCR** — detection engineering, incident triage, cross-platform coverage
- 🎤 Running competitive programming workshops for **Aura Club** (50+ participants)
- 📚 Presenting deep-dives on transformers & LLM alignment for **AIML SIG**

<div align="center">

🏅 **MRD Scholarship** (2025 & 2026) &nbsp;·&nbsp; **CNR Scholarship** (2025) — PES University

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Shubhambhat06&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shubhambhat06&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-profile-trophy.vercel.app/?username=Shubhambhat06&theme=radical&no-frame=true&row=1&column=6" />
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&section=footer&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

<div align="center">

**Thanks for stopping by — let's continue building !.**

</div>
