<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Shubham+Dattatraya+Bhat;AI%2FML+%7C+Security+Research+%7C+Full-Stack;Building+NL-SIEM+%40+PESU+C-ISFCR;9.39+CGPA+%7C+300%2B+LeetCode+%7C+2x+Scholar" alt="Typing SVG" />

### B.Tech CSE (AI & ML) · PES University, Bengaluru · CGPA 9.39/10

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-bhat-aab037344/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhambhat003@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shubhambhat06)

</div>

---

## About Me

I'm an undergraduate researcher and engineer who's drawn to problems where the answer that *looks* correct and the answer that *is* correct quietly diverge. Most recently that's meant a year inside a SOC watching detection rules pass every check and still catch nothing — and building a framework to fix that structurally instead of patching it after the fact.

When I'm not doing that: geospatial data pipelines, retrieval systems, and a slowly shrinking LeetCode backlog.

---

## 🔬 Featured Research — NL-SIEM

> **Detecting What You Think You Detect: Cross-Platform SIEM Query Generation and Prevention of ATT&CK Coverage Drift using Intermediate Representation and LLMs**
> *Bhat, S.D. & Swetha P. — Preprint under review · Research conducted at PESU C-ISFCR*

A coverage heatmap can show green while the detection behind it silently stops working the moment it's ported to a different SIEM. I named that failure mode **ATT&CK Coverage Drift** and built a multi-agent LLM framework that prevents it structurally, rather than checking for it after the fact.

**The core idea:** every detection is classified against the live MITRE ATT&CK taxonomy *before* any query is generated — including cases where one description genuinely maps to more than one technique — folded into a platform-agnostic Intermediate Representation, and only then handed to independent translation agents. ATT&CK identity travels with the detection's logic instead of riding along as a label someone remembered to copy over.

| | |
|---|---|
| 🎯 **91.4%** syntactic validity | vs. 67.8% zero-shot baseline |
| 📊 **0.67 BLEU-4** | vs. 0.40 zero-shot |
| 🗂️ **241 records** | SIEMBench v1 — 8 ATT&CK tactics, CC BY 4.0 |
| 🖥️ **5 SIEM platforms** | Splunk · QRadar · Elastic · Sentinel · Wazuh |
| ✅ **Execution-backed** | live Elastic ES\|QL + Wazuh connectors, validated in a production SOC |

`Python` `FastAPI` `React` `FAISS` `MITRE ATT&CK` `RAG` `Multi-Agent LLM Pipelines`

---

## 🚀 Projects

### Semantic Code Search Engine
Fine-tuned a CodeBERT bi-encoder with an InfoNCE contrastive objective on CodeSearchNet pairs across Python, Java, and Go, and built a FAISS `IndexFlatIP` index over 51,000 snippets.
- **8.06ms** median / **9.76ms** P95 retrieval latency
- **0.80 MRR@10** on held-out queries — competitive with commercial code search
- FastAPI backend + React frontend with ranked results, inline code previews, per-language filtering

`Python` `CodeBERT` `FAISS` `FastAPI` `React.js`

### Geospatial Analysis of Aadhaar Service Demand & Infrastructure Stress
End-to-end pipeline over UIDAI enrolment, demographic, and biometric datasets — solving large-scale name resolution across inconsistent state and district naming with Unicode normalization + RapidFuzz.
- Auto-resolved **42 of 58** state name variants and district renames against GeoJSON boundaries
- Designed four ratio-based infrastructure stress metrics with z-score/IQR outlier detection
- **Finding:** high-volume districts do *not* uniformly show high update pressure — surfaced non-obvious regional gaps with direct policy relevance

`Python` `GeoPandas` `RapidFuzz` `Pandas`

### Web Vulnerability Scanner
Multi-threaded scanner with BFS-based crawling and a thread-safe visited-set for systematic endpoint discovery.
- SQLi/XSS payload injection with pattern-matched response analysis to cut false positives
- OpenAI API integration for developer-readable vulnerability explanations and prioritized remediation
- Structured JSON output built for CI/CD security gating

`Python` `Flask` `BeautifulSoup` `OpenAI API`

### Movie Box Office Revenue Prediction
Cross-validated XGBoost + Random Forest ensemble on heavily right-skewed TMDB financial data.
- Log-scale transformation and grid-search tuning to minimize RMSE
- Engineered multi-hot genre encoding, cyclical release seasonality, and budget normalization features

`Python` `Scikit-learn` `XGBoost` `Pandas` `NumPy`

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / Data**
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B8BBE?style=flat-square)

**Web**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Security & Research**
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C1272D?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elastic&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🎓 Currently

- 🔭 Building out multi-technique ATT&CK classification and the Splunk/QRadar/Sentinel connectors for **NL-SIEM**
- 🛡️ SOC Intern at **PESU C-ISFCR** — detection engineering, incident triage, cross-platform SIEM coverage
- 🎤 Running competitive programming workshops for **Aura Club** (DP, graphs, segment trees — 50+ participants)
- 📚 Presenting deep-dives on transformer architecture and LLM alignment for **AIML SIG**
- 🧩 300+ LeetCode problems deep, still counting

---

## 🏆 Recognition

**MRD Scholarship** (2025 & 2026) · **CNR Scholarship** (2025) — PES University, for academic standing and research contribution.

---

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Shubhambhat06&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shubhambhat06&layout=compact&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Shubhambhat06&hide_border=true" />

</div>

---

<div align="center">

*Building things that hold up when someone actually checks them.*

[![LinkedIn](https://img.shields.io/badge/Let's_connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-bhat-aab037344/)

</div>
