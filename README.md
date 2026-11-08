<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=240&section=header&text=Shubham%20Bhat&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%2FML%20%C2%B7%20Security%20Research%20%C2%B7%20Detection%20Engineering&descAlignY=58&descSize=18&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=C44FFF&center=true&vCenter=true&width=800&height=45&lines=Black+Hat+Arsenal+India+2026+Presenter;Building+NL-SIEM+%40+PES+University+C-ISFCR;LLMs+%C2%B7+Detection+Engineering+%C2%B7+MITRE+ATT%26CK;Turning+%22looks+correct%22+into+%22is+correct%22" alt="Typing animation" />

<br>

![Black Hat Arsenal](https://img.shields.io/badge/Black_Hat_Arsenal-India_2026_Presenter-000000?style=for-the-badge&labelColor=E4002B)
![PES University](https://img.shields.io/badge/PES_University-B.Tech_CSE_(AI%2FML)-1F6FEB?style=for-the-badge)
![SOC](https://img.shields.io/badge/PESU_C--ISFCR-SOC_Intern-8957E5?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-bhat-aab037344/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhambhat003@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shubhambhat06)
![Profile Views](https://komarev.com/ghpvc/?username=Shubhambhat06&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 👋 About

I'm a B.Tech Computer Science student (AI/ML specialisation) at **PES University**, working at the intersection of **security operations and applied AI**.

I'm drawn to problems where the answer that *looks* right and the answer that *is* right quietly diverge. Working in a SOC, that showed up as detection rules that pass every check yet catch nothing, so I built a framework that makes that failure structurally preventable.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🎤 Featured Talk

<table>
<tr>
<td width="72%">

**NL-SIEM at Black Hat Arsenal India 2026**<br>
📅 30 October 2026 &nbsp;·&nbsp; 🤝 Co-presented with **Dr Swetha P**

Live demonstration of a multi-agent LLM framework that translates detections across SIEM platforms **without losing MITRE ATT&CK coverage**, presented to the international security community on the Black Hat Arsenal stage.

</td>
<td width="28%" align="center">

![Black Hat](https://img.shields.io/badge/BLACK_HAT-ARSENAL-E4002B?style=for-the-badge&labelColor=000000)<br>
![India](https://img.shields.io/badge/INDIA-2026-000000?style=for-the-badge)

</td>
</tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 🔬 Featured Research: NL-SIEM

> **Detecting What You Think You Detect: Cross-Platform SIEM Query Generation and Prevention of ATT&CK Coverage Drift using Intermediate Representation and LLMs**
> *Bhat, S.D. & Swetha P. · preprint under review · PESU C-ISFCR*

A coverage heatmap can stay green while the detection behind it silently stops working once it is ported to another SIEM. I named this failure mode **ATT&CK Coverage Drift** and built a multi-agent LLM framework that prevents it by design. ATT&CK classification, including cases where one description maps to several techniques, happens *before* any query is generated. The result is folded into a platform-agnostic IR and handed to independent translation agents.

```mermaid
flowchart LR
    A["Detection description<br/>(natural language)"] --> B["ATT#38;CK classifier<br/>multi-technique aware"]
    B --> C["Platform-agnostic IR"]
    C --> D1["Splunk"]
    C --> D2["QRadar"]
    C --> D3["Elastic"]
    C --> D4["Sentinel"]
    C --> D5["Wazuh"]
    D1 & D2 & D3 & D4 & D5 --> E["Validated queries<br/>syntactic + execution-backed"]
```

<div align="center">

![](https://img.shields.io/badge/Syntactic_Validity-91.4%25-brightgreen?style=for-the-badge)
![](https://img.shields.io/badge/BLEU--4-0.67-blue?style=for-the-badge)
![](https://img.shields.io/badge/Benchmark-241_Records-orange?style=for-the-badge)
![](https://img.shields.io/badge/Platforms-5_SIEMs-9c27b0?style=for-the-badge)
![](https://img.shields.io/badge/Execution--Backed-Validated_in_SOC-critical?style=for-the-badge)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🧭 Skills & Evidence

Every claim is mapped to the work that backs it, along with an honest level of depth.

| Domain | Level | Evidence |
|---|:---:|---|
| Security / Detection Engineering | ![](https://img.shields.io/badge/-PRACTISED-brightgreen?style=flat-square) | NL-SIEM validated in SOC use, live Elastic + Wazuh connectors |
| Machine Learning / Retrieval | ![](https://img.shields.io/badge/-PRACTISED-brightgreen?style=flat-square) | CodeBERT fine-tuning, FAISS @ 51K vectors, 0.80 MRR@10 |
| Full-Stack (React / FastAPI / Flask) | ![](https://img.shields.io/badge/-PRACTISED-brightgreen?style=flat-square) | 3 shipped projects, each with a working frontend and API |
| Geospatial Analysis | ![](https://img.shields.io/badge/-PRACTISED-brightgreen?style=flat-square) | UIDAI pipeline, GeoPandas, fuzzy entity resolution |
| Large-scale Distributed Systems | ![](https://img.shields.io/badge/-FAMILIAR-yellow?style=flat-square) | Coursework and personal-project scale |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 🚀 Projects

<details>
<summary><b>🔎 Semantic Code Search Engine</b> · CodeBERT bi-encoder + FAISS retrieval at 51K-snippet scale</summary>
<br>

**Problem:** keyword search doesn't understand code semantics. "Sort a list" misses idiomatic implementations that share no vocabulary with the query.

**Approach:** fine-tuned a CodeBERT bi-encoder with an InfoNCE contrastive objective on CodeSearchNet pairs (Python, Java, Go), indexed with FAISS `IndexFlatIP`.

**Result:** 8.06 ms median / 9.76 ms P95 retrieval latency and 0.80 MRR@10, competitive with commercial code search. Shipped with FastAPI + React (ranked results, inline previews, per-language filtering).

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-4B8BBE?style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
</details>

<details>
<summary><b>🗺️ Geospatial Analysis of Aadhaar Service Demand & Infrastructure Stress</b> · resolved 42 of 58 inconsistent district names</summary>
<br>

**Problem:** UIDAI datasets use inconsistent state and district naming across sources, which breaks joins against GeoJSON boundaries.

**Approach:** Unicode normalisation + RapidFuzz `token_sort_ratio` (threshold 85); four ratio-based infrastructure stress metrics with z-score / IQR outlier detection.

**Result:** auto-resolved 42 of 58 name variants. Key finding: high-volume districts do *not* uniformly show high update pressure, which surfaced non-obvious, policy-relevant gaps.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat-square)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
</details>

<details>
<summary><b>🛡️ Web Vulnerability Scanner</b> · multi-threaded BFS crawler with LLM-generated remediation reports</summary>
<br>

**Problem:** scan output is usually a raw findings dump that developers must interpret themselves.

**Approach:** multi-threaded BFS crawler with a thread-safe visited set; SQLi / XSS payload injection with pattern-matched response analysis to cut false positives.

**Result:** the OpenAI API turns findings into readable explanations with prioritised remediation, exported as structured JSON for CI/CD gating.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
</details>

<details>
<summary><b>🎬 Movie Box Office Revenue Prediction</b> · XGBoost + Random Forest ensemble on right-skewed TMDB data</summary>
<br>

**Problem:** box office revenue is heavily right-skewed, which breaks naive regression and lets tail blockbusters dominate the loss.

**Approach:** log-scale transform, cross-validated XGBoost + Random Forest ensemble with grid-search tuning; multi-hot genre encoding, cyclical seasonality, budget normalisation.

**Result:** minimised RMSE while limiting overfitting on outlier blockbuster revenue.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-006ACC?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
</details>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 🧰 Tech Stack

<div align="center">

**Languages & Frameworks**<br>
<img src="https://skillicons.dev/icons?i=python,java,c,cpp,js,react,fastapi,flask,tailwind&theme=dark" alt="Languages and frameworks" />

<br><br>

**ML, Data & Tooling**<br>
<img src="https://skillicons.dev/icons?i=pytorch,elasticsearch,postgres,docker,linux,git,vscode&theme=dark" alt="ML, data and tooling" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:FF6B6B,50:C44FFF,100:4D96FF" />

### 🎯 Currently

- 🔭 Extending NL-SIEM with multi-technique ATT&CK classification and Splunk / QRadar / Sentinel connectors
- 🛡️ SOC Intern at **PESU C-ISFCR**: detection engineering, alert triage, incident investigation, cross-platform coverage
- 🎓 Teaching Assistant for **Digital Logic and Computer Design** at PES University
- 🎤 Running competitive programming workshops for **Aura Club** (50+ participants)
- 📚 Presenting deep-dives on transformers and LLM alignment for **AIML SIG**

### 🏅 Recognition

| | |
|---|---|
| 🎤 **Black Hat Arsenal India 2026** | Presenter, NL-SIEM (30 Oct 2026) |
| 🎓 **MRD Scholarship** | PES University, 2025 & 2026 |
| 🎓 **CNR Scholarship** | PES University, 2025 |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:4D96FF,50:C44FFF,100:FF6B6B" />

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Shubhambhat06&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shubhambhat06&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<img src="https://streak-stats.demolab.com/?user=Shubhambhat06&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Shubhambhat06&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" />

<img src="https://github-profile-trophy.vercel.app/?username=Shubhambhat06&theme=tokyonight&no-frame=true&row=1&column=6" alt="Trophies" />

</div>

<br>

<div align="center">

### 🤝 Let's Connect

Open to conversations on **SIEM, threat detection, MITRE ATT&CK, and applying AI to security problems**.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-bhat-aab037344/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhambhat003@gmail.com)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&section=footer&animation=twinkling&color=0:4D96FF,50:C44FFF,100:FF6B6B" />
