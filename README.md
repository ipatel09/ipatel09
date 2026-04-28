<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,30:16213e,70:0f3460,100:533483&height=200&section=header&text=Ishan%20Hirani&fontSize=56&fontColor=E8E8F0&fontAlignY=38&fontFamily=Nunito&desc=Data%20Engineer%20%20%7C%20%20AI%2FML%20Engineer&descSize=20&descAlignY=60&descColor=A8B8D8)

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-hirani)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/hiraniishan)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hiraniishan17@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-0F3460?style=for-the-badge&logo=googledrive&logoColor=white)](YOUR_RESUME_LINK)
![Views](https://komarev.com/ghpvc/?username=Ishanhirani11&style=for-the-badge&color=533483&label=PROFILE+VIEWS)

</div>

<br/>

<div align="center">

```
 I build data pipelines and AI systems — end-to-end, production-ready, and built to last.
```

</div>

<br/>

---

## 👨‍💻 About Me

> **B.Tech AI & Data Science** · Government Engineering College, Rajkot · Class of **2026** · Gujarat, India 🇮🇳

I'm an AI & Data Science engineer who enjoys working across the full data stack — from writing scrapers and designing schemas to training deep learning models from scratch. I've shipped a multi-source job market pipeline running on Airflow, a complete diffusion model implemented entirely in PyTorch, and a production-grade offline voice assistant engineered over 12 weeks. I care about writing systems that are modular, observable, and built to run without breaking.

💼 &nbsp;Actively looking for **Data Engineer** and **AI/ML Engineer** roles — available in **15 days**.

---

## 🔢 By the Numbers

<div align="center">

| 📦 **2,322+** | ⚙️ **7-Task** | 🧬 **1,000-Step** | 🎙️ **9-Stage** | 🌐 **3 Sources** | 📁 **4 Projects** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| job records/day | Airflow DAG | DDPM training | voice pipeline | scraping methods | on GitHub |

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 📊 [Job Market Intelligence Pipeline](https://github.com/Ishanhirani11/job-market-pipeline)

![](https://img.shields.io/badge/Data%20Engineering-0F3460?style=flat-square)
![](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

Multi-source pipeline monitoring the DE job market **every day**. Three ingestion strategies — Selenium for Naukri, Requests for LinkedIn, RapidAPI for Indeed. Stores 2,300+ records in a **4-table PostgreSQL schema**, orchestrated by a **7-task Airflow DAG** at 09:00 daily. Extracts **47+ skills** from unstructured text via NLP regex pipeline. Pushes 6 live reporting datasets to Google Sheets.

```
Naukri (Selenium)  ──┐
LinkedIn (Requests) ──┼──► PostgreSQL ──► Airflow DAG ──► Google Sheets
Indeed (RapidAPI)  ──┘    4 tables       7 tasks/day     6 datasets
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

</td>
<td width="50%" valign="top">

### 🎨 [Text-to-Image — LDM from Scratch](https://github.com/Ishanhirani11/text-to-image-ldm)

![](https://img.shields.io/badge/AI%20%2F%20ML-533483?style=flat-square)
![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![](https://img.shields.io/badge/Zero%20APIs-000000?style=flat-square)

Complete **Latent Diffusion Model** in PyTorch — no external generation API. VAE that compresses 64×64 images into 8×8×4 latent space (64× reduction). U-Net denoiser with self-attention and cross-attention. Frozen DistilBERT encoder producing 768-dim token embeddings. **1,000-step DDPM** training with mixed precision, cosine LR, and checkpoint resume. **50-step DDIM** inference with classifier-free guidance at scale 7.5. Flickr30k via Hugging Face. Device-agnostic: CUDA → MPS → CPU.

```python
# Architecture pipeline
VAE encoder → latent space → U-Net denoiser
    ↑ cross-attention ↑
DistilBERT("your prompt") → 768-dim embeddings
→ DDIM 50-step inference → VAE decode → image
```

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![DistilBERT](https://img.shields.io/badge/DistilBERT-FF6F00?style=flat-square)
![DDPM](https://img.shields.io/badge/DDPM%2FDDIM-533483?style=flat-square)
![Colab](https://img.shields.io/badge/Colab%20T4-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [HIK — Voice-Based Assistant](https://github.com/Ishanhirani11/hik-voice-assistant)

![](https://img.shields.io/badge/AI%20%2F%20Systems-0F3460?style=flat-square)
![](https://img.shields.io/badge/Offline--First-222?style=flat-square)
![](https://img.shields.io/badge/12%20Weeks-533483?style=flat-square)

Zero-cost, offline-capable voice assistant — 12 weeks of engineering, 40+ files QA'd. **9-stage pipeline**: microphone capture (16kHz) → wake word (OpenWakeWord) → VAD (Silero) → dual STT (Whisper primary, Vosk fallback) → intent classification (9 types) → skill execution (6 skills) → 4-level TTS (Piper → gTTS → System → GUI). **ChromaDB** vector memory (MiniLM) for long-term recall. Electron GUI with WebSocket bridge (Python ↔ JS). Platform abstraction for macOS and Windows — one codebase.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![Vosk](https://img.shields.io/badge/Vosk-333?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-533483?style=flat-square)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Silero](https://img.shields.io/badge/Silero%20VAD-222?style=flat-square)

</td>
<td width="50%" valign="top">

### 🌦️ [Automated Weather ETL Pipeline](https://github.com/Ishanhirani11/weather-etl-pipeline)

![](https://img.shields.io/badge/Data%20Engineering-0F3460?style=flat-square)
![](https://img.shields.io/badge/Cron%20Automated-3fb950?style=flat-square)

Production-style ETL that runs **without touching it**. Extracts weather data for 10+ cities every 6 hours via OpenWeatherMap REST API — retry logic for rate limits and failures. Transforms raw JSON with Pandas: normalization, deduplication, type casting, null handling. Loads ~**5,000 records/day** into MySQL with a time-series schema. Cron-scheduled. Generates 30+ days of history for downstream ML forecasting.

```
REST API (6hr) → Extract → Transform (Pandas)
              → Load (MySQL) → 5K records/day
              → 30+ days history for ML
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20API-009688?style=flat-square)
![Cron](https://img.shields.io/badge/Cron-555?style=flat-square)

</td>
</tr>
</table>

---

## 💼 Experience

**AI & ML Intern &nbsp;·&nbsp; UNIKWORK** &nbsp;&nbsp;`Jan 2026 – Apr 2026 · Surat`

Built production ETL pipelines with MySQL storage and deduplication. Developed REST APIs using Flask and Django. Applied supervised ML workflows — EDA, feature engineering, model evaluation — using Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, and Plotly.

**AI Intern &nbsp;·&nbsp; IBM Skillbox** &nbsp;&nbsp;`Jul 2025`

Built *Water Guardian* — a multi-turn AI chatbot using Gemini 1.5 API for automated civic complaint routing. Implemented NLP-based intent classification and applied prompt engineering for structured LLM outputs in a real-world automation context.

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-533483?style=for-the-badge&logo=python&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F54B27?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📈 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=g00562&show_icons=true&theme=transparent&hide_border=true&title_color=533483&icon_color=0F3460&text_color=555555&include_all_commits=true&count_private=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishanhirani11&layout=compact&langs_count=7&theme=transparent&hide_border=true&title_color=533483&text_color=555555"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=g00562&theme=transparent&hide_border=true&ring=533483&fire=0F3460&currStreakLabel=533483&sideLabels=555555&dates=888888&sideNums=533483&currStreakNum=0F3460)](https://git.io/streak-stats)

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Ishanhirani11&bg_color=transparent&color=533483&line=0F3460&point=533483&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

*"Build before you're ready. Ship before it's perfect. Learn from what breaks."*

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:533483,50:0f3460,100:1a1a2e&height=120&section=footer&fontFamily=Nunito)

</div>
