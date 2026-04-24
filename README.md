<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="100%"/>
</div>

<h1 align="center">
  Ishan Hirani
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28px"/>
</h1>

<p align="center">
  <b>Data Engineer · AI/ML Engineer · Builder</b><br/>
  <i>I don't just study data systems — I build them.</i>
</p>

<div align="center">
  <a href="https://linkedin.com/in/ishan-hirani">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;
  <a href="https://www.kaggle.com/hiraniishan">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  </a>&nbsp;
  <a href="mailto:hiraniishan17@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>&nbsp;
  <a href="https://drive.google.com/drive/folders/1AkJAQzplxSfbAlx23I4iIo9OwBXo6Vyy">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white"/>
  </a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=Ishanhirani11&color=blueviolet&style=for-the-badge&label=VIEWS"/>
</div>

<br/>

---

## 👨‍💻 About Me

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="360"/>

- 🎓 Final-year **B.Tech AI & Data Science** @ Government Engineering College, Rajkot — **2026**
- 🔧 Experienced building **end-to-end ETL pipelines**, REST API integrations & data orchestration with Airflow
- 🧠 Built a **Latent Diffusion Model from scratch** in PyTorch — VAE, U-Net, DistilBERT, DDPM/DDIM — zero APIs
- 🎙️ Engineered **HIK**, a production-grade offline voice assistant — 9-stage pipeline, ChromaDB memory, Electron GUI
- 💬 Ask me about **ETL Pipelines · PostgreSQL · PyTorch · LLM Integration · Apache Airflow**
- 🌱 Currently learning **Apache Spark · dbt · Docker · Agentic AI**
- 💼 Open to **Data Engineer** and **AI/ML Engineer** roles — available in **15 days**
- ⚡ Fun fact: I taught an AI to report potholes, then built a model that can draw them 🕳️

<br clear="right"/>

---

## 📊 Quick Numbers

<div align="center">

| 🗄️ 2,322+ Records | ⚙️ 7-Task DAG | 🧬 1,000-Step DDPM | 🎙️ 9-Stage Pipeline | 🏢 3 Internships | 📦 4 Live Projects |
|:---:|:---:|:---:|:---:|:---:|:---:|
| ingested daily | Airflow orchestration | diffusion training | voice AI system | completed | on GitHub |

</div>

---

## 🚀 Featured Projects

### 📊 Job Market Intelligence Pipeline
> *The most complete DE project I've built — monitors the data job market every single day.*

[![Repo](https://img.shields.io/badge/GitHub-job--market--pipeline-181717?style=flat-square&logo=github)](https://github.com/Ishanhirani11/job-market-pipeline)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

Multi-source pipeline that scrapes **Naukri** (Selenium), **LinkedIn** (Requests) and **Indeed** (RapidAPI), stores clean data in a **4-table PostgreSQL schema**, orchestrates the full flow via a **7-task Apache Airflow DAG**, extracts **47+ DE skills** via NLP, and pushes **6 reporting datasets** to Google Sheets — all running daily.

```
Naukri (Selenium) ──┐
LinkedIn (Requests) ─┼──► PostgreSQL ──► Airflow DAG ──► Google Sheets (6 datasets)
Indeed (RapidAPI) ───┘     4 tables      7 tasks daily    top_skills · salary_by_city · ...
```

---

### 🎨 Text-to-Image Generation — LDM from Scratch
> *No Stable Diffusion, no APIs. Every component written from ground up in PyTorch.*

[![Repo](https://img.shields.io/badge/GitHub-text--to--image--ldm-181717?style=flat-square&logo=github)](https://github.com/Ishanhirani11/text-to-image-ldm)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Colab](https://img.shields.io/badge/Colab%20T4-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)

Implemented a complete **Latent Diffusion Model** — VAE (64×64 → 8×8×4, 64× compression) · U-Net denoiser with cross-attention · DistilBERT text encoder (frozen, 768-dim) · **1000-step DDPM** training + **50-step DDIM** fast inference · classifier-free guidance (scale 7.5) · trained on Flickr30k.

```python
# What I built from scratch:
VAE encoder/decoder  →  U-Net denoiser  →  DistilBERT text conditioning
DDPM scheduler       →  DDIM inference  →  CFG guidance  →  Real-ESRGAN upscale
```

---

### 🎙️ HIK — Voice-Based Virtual Assistant
> *Zero-cost, offline-capable, cross-platform — 12 weeks, 40+ files QA'd.*

[![Repo](https://img.shields.io/badge/GitHub-hik--voice--assistant-181717?style=flat-square&logo=github)](https://github.com/Ishanhirani11/hik-voice-assistant)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat-square&logo=python&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)

9-stage pipeline: **wake word** (OpenWakeWord) → **VAD** (Silero) → **dual STT** (Whisper + Vosk fallback) → intent classification → **6 skill modules** → **4-level TTS** (Piper → gTTS → System → GUI) · **ChromaDB vector memory** for long-term recall · Electron GUI with 7 animated states · runs on **macOS + Windows, same codebase**.

---

### 🌦️ Automated Weather ETL Pipeline
> *My first production-style pipeline — still runs daily without touching it.*

[![Repo](https://img.shields.io/badge/GitHub-weather--etl--pipeline-181717?style=flat-square&logo=github)](https://github.com/Ishanhirani11/weather-etl-pipeline)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

Extracts weather data for **10+ cities every 6 hours** via OpenWeatherMap API → transforms with Pandas (dedup, null handling, normalization) → loads ~**5,000 records/day** into MySQL → Cron-automated. 30+ days of history ready for ML forecasting.

---

## 💼 Experience

**🤖 AI & ML Intern — UNIKWORK** &nbsp;&nbsp; `Jan 2026 – Apr 2026 · Surat`

Built ETL pipelines, REST APIs (Flask/Django), and ML workflows (EDA, feature engineering, model evaluation) for production data-driven applications. Worked with Pandas, NumPy, Scikit-learn, MySQL.

**🤖 AI Intern — IBM Skillbox** &nbsp;&nbsp; `Jul 2025 · 1 month`

Built **Water Guardian** — a multi-turn AI chatbot using Gemini 1.5 API for automated civic complaint routing via NLP-based intent classification and prompt engineering.

---

## 🎓 Education

| Degree | Institution | Score | Year |
|---|---|---|---|
| **B.Tech — Artificial Intelligence & Data Science** | Government Engineering College, Rajkot (GTU) | CGPA: 7.20 | 2022 – 2026 |
| 12th Science | SGVP International School, Ahmedabad | 80% | 2022 |

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

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=for-the-badge&logo=python&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge)

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📈 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Ishanhirani11&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishanhirani11&layout=compact&langs_count=7&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Ishanhirani11&theme=tokyonight&hide_border=true"/>
</div>

---

## 🐍 Contribution Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>
</div>

---

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>
</div>

<br/>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%"/>
</div>
