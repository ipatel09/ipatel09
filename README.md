![header](https://capsule-render.vercel.app/api?type=waving&color=0:0A192F,50:112240,100:1A365D&height=200&section=header&text=Ishan%20Hirani&fontSize=56&fontColor=CCD6F6&fontAlignY=38&fontFamily=Nunito&desc=Data%20Engineer%20%7C%20AI%2FML%20Engineer&descSize=20&descAlignY=60&descColor=8892B0)

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-hirani)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/hiraniishan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hiraniishan17@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-0A192F?style=for-the-badge&logo=googledrive&logoColor=white)](YOUR_RESUME_LINK)
![Profile Views](https://komarev.com/ghpvc/?username=Ishanhirani11&style=for-the-badge&color=64FFDA&label=PROFILE+VIEWS)

</div>

---

## 🧠 About Me

```python
class IshanHirani:
    def __init__(self):
        self.name        = "Ishan Hirani"
        self.role        = ["Data Engineer", "AI/ML Engineer"]
        self.education   = "B.Tech AI & DS  ·  GEC Rajkot  ·  CGPA 7.20  ·  2026"
        self.location    = "Gujarat, India 🇮🇳"
        self.experience  = ["UNIKWORK (AI & ML Intern)", "IBM Skillbox (AI Intern)"]
        self.projects    = {
            "pipeline" : "Job Market Intelligence — Airflow + PostgreSQL + 2,300+ records/day",
            "genai"    : "Latent Diffusion Model — VAE + U-Net + DistilBERT + DDPM/DDIM from scratch",
            "system"   : "HIK Voice Assistant — 9-stage pipeline, offline-first, 12 weeks built"
        }
        self.stack       = ["Python", "PostgreSQL", "Apache Airflow", "PyTorch", "HuggingFace"]
        self.open_to     = ["Data Engineer", "AI/ML Engineer", "Data Analyst"]
        self.fun_fact    = "Taught an AI to report potholes 🕳️, then built a model to draw them 🎨"
```

---

## 🚀 Projects

### 📊 [Job Market Intelligence Pipeline](https://github.com/Ishanhirani11/job-market-pipeline)
> Multi-source pipeline monitoring the DE job market — every single day.

Scrapes **Naukri** (Selenium + headless Chrome), **LinkedIn** (Requests + BeautifulSoup), and **Indeed** (RapidAPI) using three completely different ingestion strategies. Stores 2,300+ cleaned records in a **4-table PostgreSQL schema**. Orchestrated by a **7-task Apache Airflow DAG** running daily at 09:00 AM. Extracts **47+ DE skills** from unstructured descriptions using an NLP regex pipeline. Exports 6 live datasets to Google Sheets: `top_skills · salary_by_city · top_companies · jobs_by_city · experience_distribution · jobs_cleaned`.

```
Naukri  (Selenium) ──┐
LinkedIn (Requests) ──┼──▶ PostgreSQL ──▶ Airflow DAG ──▶ Google Sheets
Indeed  (RapidAPI) ──┘    4-table schema   7 tasks/day    6 live reports
```

`Python` `PostgreSQL` `Apache Airflow` `Selenium` `SQLAlchemy` `RapidAPI` `Pandas` `loguru`

---

### 🎨 [Text-to-Image — Latent Diffusion Model from Scratch](https://github.com/Ishanhirani11/text-to-image-ldm)
> Complete LDM in PyTorch. No generation APIs. Every component hand-built.

**VAE** compresses 64×64 images into 8×8×4 latent space (64× reduction). **U-Net denoiser** with self-attention and cross-attention across 3 resolution scales. Frozen **DistilBERT** text encoder producing 768-dim token-level embeddings for conditioning. **1,000-step DDPM** training with mixed precision, cosine LR schedule, EMA, and checkpoint resume. **50-step DDIM** fast inference with classifier-free guidance at scale 7.5 (10% CFG dropout during training). Dataset: Flickr30k via Hugging Face. Fully device-agnostic: CUDA → Apple MPS → CPU.

```
DistilBERT("a sunset over mountains")
         │ 768-dim cross-attention
         ▼
VAE ──▶ Latent Space ──▶ U-Net Denoiser ──▶ DDIM (50 steps) ──▶ VAE Decode ──▶ Image
```

`PyTorch` `Hugging Face` `DistilBERT` `DDPM/DDIM` `VAE` `U-Net` `Mixed Precision` `Colab T4`

---

### 🎙️ [HIK — Voice-Based Virtual Assistant](https://github.com/Ishanhirani11/hik-voice-assistant)
> Zero-cost, offline-capable, cross-platform. 12 weeks. 40+ files QA'd.

**9-stage pipeline**: microphone capture (sounddevice, 16kHz mono) → wake word detection (OpenWakeWord, "Hey Jarvis") → VAD (Silero neural model) → dual STT (Whisper primary ~500MB, Vosk fallback ~40MB with automatic failover) → intent classification (9 types) → skill execution (6 skills: system control, calendar, web search, weather, translation, media) → response → TTS → audio output. **4-level TTS fallback**: Piper (offline ONNX) → gTTS → System TTS → GUI text. **ChromaDB vector memory** (MiniLM embeddings) for long-term semantic recall. Electron GUI with 7 animated states and WebSocket bridge (Python ↔ JS). Platform abstraction: macOS (AppleScript) + Windows (PowerShell/WMI) — one codebase.

`Python` `Whisper` `Vosk` `Piper` `ChromaDB` `Electron` `Silero VAD` `OpenWakeWord` `SQLite`

---

### 🌦️ [Automated Weather ETL Pipeline](https://github.com/Ishanhirani11/weather-etl-pipeline)
> Runs every 6 hours. Processes 5,000 records a day. Never needs touching.

Extracts weather for **10+ cities** via OpenWeatherMap REST API with retry logic for rate limits and failures. Transforms raw JSON using Pandas — normalization, deduplication, null handling, type casting. Loads ~**5,000 records/day** into MySQL with a time-series optimized schema; SQLite for local use. Cron-scheduled. Generates **30+ days of history** for downstream ML forecasting use cases.

`Python` `Pandas` `OpenWeatherMap API` `MySQL` `SQLite` `Cron Scheduling`

---

## 💼 Experience

| | Company | Role | Period |
|:---|:---|:---|:---|
| 🔹 | **UNIKWORK** | AI & ML Intern | Jan 2026 – Apr 2026 |
| 🔹 | **IBM Skillbox** | AI Intern | Jul 2025 |

**UNIKWORK** — Built production ETL pipelines (web scraping → data cleaning → MySQL storage), REST APIs using Flask and Django, and supervised ML workflows — EDA, feature engineering, model evaluation — using Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, and Plotly.

**IBM Skillbox** — Built *Water Guardian*, a multi-turn AI chatbot using Gemini 1.5 API for automated civic complaint routing via NLP-based intent classification and structured prompt engineering.

---

## 🛠️ Tech Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,postgresql,mysql,sqlite,selenium,flask,django,git&theme=dark&perline=8"/>
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,postgresql,mysql,sqlite,selenium,flask,django,git&theme=light&perline=8"/>
  <img src="https://skillicons.dev/icons?i=python,postgresql,mysql,sqlite,selenium,flask,django,git&perline=8"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow,github,vscode,linux,fastapi,docker&theme=dark&perline=8"/>
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow,github,vscode,linux,fastapi,docker&theme=light&perline=8"/>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow,github,vscode,linux,fastapi,docker&perline=8"/>
</picture>

</div>

<div align="center">

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0A192F?style=for-the-badge&logo=python&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Ishanhirani11&show_icons=true&theme=transparent&hide_border=true&title_color=64FFDA&icon_color=64FFDA&text_color=8892B0&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishanhirani11&layout=compact&langs_count=7&theme=transparent&hide_border=true&title_color=64FFDA&text_color=8892B0"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Ishanhirani11&theme=transparent&hide_border=true&ring=64FFDA&fire=0A66C2&currStreakLabel=64FFDA&sideLabels=8892B0&dates=8892B0&sideNums=64FFDA&currStreakNum=CCD6F6)](https://git.io/streak-stats)

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Ishanhirani11&bg_color=transparent&color=64FFDA&line=0A66C2&point=64FFDA&area=true&area_color=112240&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

*"Build before you're ready. Ship before it's perfect. Learn from what breaks."*

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:1A365D,50:112240,100:0A192F&height=120&section=footer&fontFamily=Nunito)
