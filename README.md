[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,30:1a1a4e,70:1e3a5f,100:0f3460&height=200&section=header&text=Ishan%20Hirani&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineer%20%26%20AI%2FML%20Engineer&descAlignY=58&descSize=20&animation=fadeIn&fontAlign=50)](https://github.com/Ishanhirani11)

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&multiline=false&width=700&lines=Building+Data+Pipelines+that+process+2%2C300%2B+records+daily+%F0%9F%97%84%EF%B8%8F;Training+Diffusion+Models+from+scratch+in+PyTorch+%F0%9F%8E%A8;Engineered+a+9-stage+offline+Voice+Assistant+in+12+weeks+%F0%9F%8E%99%EF%B8%8F;Open+to+Data+Engineer+%26+AI%2FML+Engineer+roles+%7C+June+2026+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-hirani)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/hiraniishan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hiraniishan17@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ishanhirani11)
[![Profile Views](https://komarev.com/ghpvc/?username=Ishanhirani11&color=58A6FF&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Ishanhirani11)

</div>

---

## 🧠 About Me

```python
class IshanHirani:
    def __init__(self):
        self.name        = "Ishan Hirani"
        self.role        = ["Data Engineer", "AI/ML Engineer"]
        self.education   = "B.Tech AI & DS @ GEC Rajkot · CGPA 7.20 · 2026"
        self.location    = "Gujarat, India 🇮🇳"
        self.building    = {
            "DE"   : "Job Market Pipeline — Airflow + PostgreSQL + 3 scrapers → 2,322+ records/day",
            "AI"   : "Latent Diffusion Model — VAE + U-Net + DistilBERT + DDPM/DDIM from scratch",
            "SYS"  : "HIK Voice Assistant — 9-stage pipeline, offline-first, ChromaDB memory"
        }
        self.stack       = ["Python", "PostgreSQL", "Apache Airflow", "PyTorch", "Hugging Face"]
        self.open_to     = ["Data Engineer", "AI/ML Engineer", "Data Analyst"]
        self.available   = "15 days notice · GEC Rajkot, June 2026"
        self.fun_fact    = "Taught an AI to report potholes 🕳️ → trained a model to draw them 🎨"

    def philosophy(self):
        return "I don't just study systems — I build them, break them, and make them better. 🚀"
```

---

## ⚡ What I Build

<table>
<tr>
<td width="50%" valign="top">

**🗄️ Data Engineering**
- Multi-source ETL: REST API · Selenium · RapidAPI
- PostgreSQL schema design + Airflow DAG orchestration
- NLP skill extraction from unstructured job text
- Automated pipelines with deduplication & retry logic

</td>
<td width="50%" valign="top">

**🤖 AI / Machine Learning**
- Latent Diffusion Models (VAE + U-Net + DDPM) from scratch
- LLM integration (Gemini, Groq) + ChromaDB vector memory
- Offline-first AI with hybrid cloud/local architecture
- Multi-stage NLP pipelines with intent classification

</td>
</tr>
</table>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📊 [Job Market Intelligence Pipeline](https://github.com/Ishanhirani11/job-market-pipeline)
![](https://img.shields.io/badge/Data%20Engineering-0066cc?style=flat-square)
![](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

Multi-source pipeline monitoring the DE job market **every day**.

| Metric | Value |
|---|---|
| Records | **2,322+** cleaned jobs |
| Sources | Naukri · LinkedIn · Indeed |
| Orchestration | **7-task Airflow DAG** |
| Storage | PostgreSQL · 4-table schema |
| Skills extracted | **47+ DE skills** via NLP |
| Exports | 6 Google Sheets datasets |

`Python` `PostgreSQL` `Airflow` `Selenium` `SQLAlchemy` `RapidAPI`

</td>
<td width="50%" valign="top">

### 🎨 [Text-to-Image LDM from Scratch](https://github.com/Ishanhirani11/text-to-image-ldm)
![](https://img.shields.io/badge/AI%20%2F%20ML-7c3aed?style=flat-square)
![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

Complete Latent Diffusion Model in PyTorch — **zero APIs used**.

| Component | Detail |
|---|---|
| VAE | 64×64 → 8×8×4 latent **(64× compression)** |
| U-Net | Cross-attention · 3 resolution scales |
| Text encoder | DistilBERT frozen · 768-dim |
| Training | **1000-step DDPM** · AMP · cosine LR |
| Inference | **50-step DDIM** · CFG scale 7.5 |
| Dataset | Flickr30k via Hugging Face |

`PyTorch` `DistilBERT` `DDPM/DDIM` `VAE` `U-Net` `Colab T4`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [HIK — Voice-Based Assistant](https://github.com/Ishanhirani11/hik-voice-assistant)
![](https://img.shields.io/badge/AI%20%2F%20Systems-059669?style=flat-square)
![](https://img.shields.io/badge/Offline--First-black?style=flat-square)

Zero-cost, offline-capable assistant — **12 weeks, 40+ files QA'd**.

| Feature | Detail |
|---|---|
| Pipeline | **9 stages**: Mic→Wake→VAD→STT→... |
| STT | Whisper (primary) + Vosk (fallback) |
| TTS | **4-level**: Piper → gTTS → System → GUI |
| Memory | ChromaDB · MiniLM · long-term recall |
| Skills | System · Calendar · Search · Weather |
| Platforms | macOS + Windows · **one codebase** |

`Python` `Whisper` `Vosk` `ChromaDB` `Electron` `Silero VAD`

</td>
<td width="50%" valign="top">

### 🌦️ [Weather Data ETL Pipeline](https://github.com/Ishanhirani11/weather-etl-pipeline)
![](https://img.shields.io/badge/Data%20Engineering-0066cc?style=flat-square)
![](https://img.shields.io/badge/Automated-3fb950?style=flat-square)

Production-style ETL — **fully automated, zero manual intervention**.

| Metric | Value |
|---|---|
| Cities | **10+** monitored |
| Volume | **~5,000 records/day** |
| Schedule | Every **6 hours** via Cron |
| History | **30+ days** for ML forecasting |
| Error handling | Retry + rate-limit logic |
| Storage | MySQL + SQLite |

`Python` `Pandas` `OpenWeatherMap API` `MySQL` `SQLite` `Cron`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Data Engineering**

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-3C873A?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**AI & Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat-square&logo=python&logoColor=white)

**LLM & Vector**

![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat-square&logo=python&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat-square&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F54B27?style=flat-square&logo=python&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## 💼 Experience

**🤖 AI & ML Intern — UNIKWORK** &nbsp;`Jan 2026 – Apr 2026`

Built data-driven backend systems, ETL pipelines, and ML workflows for production applications.

- Built web scraping + ETL pipelines with MySQL storage, deduplication, and schema design
- Developed REST APIs using Flask and Django for data-driven web applications
- Applied supervised ML workflows — EDA, feature engineering, model evaluation

---

**🤖 AI Intern — IBM Skillbox** &nbsp;`Jul 2025`

Built **Water Guardian** — a multi-turn AI chatbot using Gemini 1.5 API for automated civic complaint routing across 5 categories via NLP-based intent classification.

---

## 📈 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Ishanhirani11&show_icons=true&theme=transparent&hide_border=true&title_color=58A6FF&icon_color=58A6FF&text_color=555555&include_all_commits=true&count_private=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishanhirani11&layout=compact&langs_count=8&theme=transparent&hide_border=true&title_color=58A6FF&text_color=555555"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Ishanhirani11&theme=transparent&hide_border=true&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=555555&dates=555555&currStreakNum=58A6FF&sideNums=58A6FF)](https://git.io/streak-stats)

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Ishanhirani11&theme=github-compact&hide_border=true&color=58A6FF&line=58A6FF&point=ffffff&area=true&area_color=58A6FF)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏆 Achievements

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=Ishanhirani11&theme=flat&no-frame=true&no-bg=true&margin-w=8&column=6)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📜 Certifications

| Certificate | Issuer | Status |
|---|---|---|
| IBM Data Engineering Professional Certificate | IBM / Coursera | 🔄 In Progress |
| AWS Cloud Quest: GenAI Practitioner | Amazon Web Services | 🔄 In Progress |
| GenAI Powered Data Analytics Job Simulation | Tata Group / Forage | ✅ Completed |
| Data Visualisation: Empowering Business With Insights | Tata Group / Forage | ✅ Completed |
| Prompt Design in Vertex AI | Google Cloud | ✅ Completed |

---

## 🎓 Education

| Degree | Institution | Score | Year |
|---|---|---|---|
| B.Tech — Artificial Intelligence & Data Science | Government Engineering College, Rajkot (GTU) | CGPA: 7.20 | 2026 |
| 12th Science | SGVP International School, Ahmedabad | 80% | 2022 |

---

## 🌐 Let's Connect

<div align="center">

> *"The best data engineers are the ones who build before they're ready."*

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-hirani)
[![Kaggle](https://img.shields.io/badge/Follow%20on%20Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/hiraniishan)
[![Gmail](https://img.shields.io/badge/Send%20a%20Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hiraniishan17@gmail.com)

</div>

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation" />

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,30:1e3a5f,70:1a1a4e,100:0f0c29&height=100&section=footer&animation=fadeIn)](https://github.com/Ishanhirani11)
