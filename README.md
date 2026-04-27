# Ishan Hirani

**Data Engineer · AI/ML Engineer**
&nbsp;·&nbsp; Government Engineering College, Rajkot &nbsp;·&nbsp; B.Tech AI & DS, 2026
&nbsp;·&nbsp; Gujarat, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ishan-hirani)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/hiraniishan)
[![Gmail](https://img.shields.io/badge/hiraniishan17%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hiraniishan17@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=flat-square&logo=googledrive&logoColor=white)](YOUR_RESUME_LINK)
![Profile Views](https://komarev.com/ghpvc/?username=Ishanhirani11&style=flat-square&color=grey)

---

I build data pipelines and AI systems — the kind that run on a schedule, process real data, and don't break when no one is watching.

On the engineering side, I've built multi-source ETL pipelines with Airflow orchestration, PostgreSQL storage, and three different ingestion strategies. On the AI side, I've implemented a Latent Diffusion Model from scratch — every component written by hand, no generation APIs. I care about systems that are modular, fault-tolerant, and actually work in production.

Open to **Data Engineer** and **AI/ML Engineer** roles. Available in 15 days.

---

## Projects

### [Job Market Intelligence Pipeline](https://github.com/Ishanhirani11/job-market-pipeline)
Multi-source pipeline that monitors the Data Engineer job market daily. Scrapes **Naukri** via Selenium, **LinkedIn** via Requests, and **Indeed** via RapidAPI — three different ingestion strategies for three different site architectures. Cleans and stores 2,300+ records into a 4-table PostgreSQL schema. Orchestrated by a 7-task **Apache Airflow DAG** that runs every day at 09:00. Extracts 47+ DE skills from unstructured job descriptions using an NLP regex pipeline. Pushes 6 reporting datasets to Google Sheets.

`Python` `PostgreSQL` `Apache Airflow` `Selenium` `SQLAlchemy` `RapidAPI` `Pandas` `loguru`

---

### [Text-to-Image Generation — LDM from Scratch](https://github.com/Ishanhirani11/text-to-image-ldm)
Full Latent Diffusion Model implemented in PyTorch without any external generation API. Built a VAE that compresses 64×64 images into an 8×8×4 latent space (64× reduction), a U-Net denoiser with self-attention and cross-attention, and a frozen DistilBERT text encoder producing 768-dim token embeddings for conditioning. Trained with a 1000-step DDPM scheduler using mixed precision and cosine LR. Inference runs in 50 steps via DDIM with classifier-free guidance at scale 7.5. Dataset: Flickr30k via Hugging Face. Device-agnostic: CUDA → MPS → CPU.

`PyTorch` `Hugging Face` `DistilBERT` `DDPM/DDIM` `VAE` `U-Net` `Mixed Precision` `Colab T4`

---

### [HIK — Voice-Based Virtual Assistant](https://github.com/Ishanhirani11/hik-voice-assistant)
Zero-cost, offline-capable voice assistant built over 12 weeks across 9 engineering phases with 40+ files QA-audited. 9-stage pipeline: microphone capture (sounddevice, 16kHz) → wake word (OpenWakeWord, "Hey Jarvis") → VAD (Silero neural) → dual STT (Whisper primary, Vosk fallback) → intent classification (9 types) → skill execution (6 skills) → TTS (4-level fallback: Piper → gTTS → System → GUI). ChromaDB vector memory with MiniLM embeddings for long-term semantic recall. Electron GUI with WebSocket bridge. Runs on macOS and Windows from a single codebase.

`Python` `Whisper` `Vosk` `Piper` `ChromaDB` `Electron` `Silero VAD` `SQLite` `WebSocket`

---

### [Automated Weather ETL Pipeline](https://github.com/Ishanhirani11/weather-etl-pipeline)
Production-style ETL pipeline that extracts weather data for 10+ cities every 6 hours via the OpenWeatherMap REST API. Transforms raw JSON with Pandas — normalization, deduplication, null handling. Loads ~5,000 records/day into MySQL. Cron-scheduled, no manual intervention. 30+ days of history available for downstream ML forecasting.

`Python` `Pandas` `OpenWeatherMap API` `MySQL` `SQLite` `Cron`

---

## Experience

**AI & ML Intern — UNIKWORK** &nbsp; `Jan 2026 – Apr 2026`
Built ETL pipelines, REST APIs (Flask/Django), and ML workflows — EDA, feature engineering, model evaluation — for production data-driven applications.

**AI Intern — IBM Skillbox** &nbsp; `Jul 2025`
Built Water Guardian, a multi-turn AI chatbot using Gemini 1.5 API for automated civic complaint routing via NLP-based intent classification.

---

## Tech Stack

**Data Engineering**
`Python` `PostgreSQL` `MySQL` `SQLite` `Apache Airflow` `Selenium` `BeautifulSoup` `Pandas` `NumPy` `SQLAlchemy` `ETL Pipelines` `REST APIs` `Google Sheets API`

**AI / ML**
`PyTorch` `Scikit-learn` `Hugging Face Transformers` `DistilBERT` `DDPM/DDIM` `ChromaDB` `Gemini API` `Groq` `NLP` `Deep Learning` `LLM Integration`

**Tools**
`Git` `GitHub` `Flask` `Django` `Jupyter` `VS Code` `Linux`

---

## GitHub Stats

<p align="left">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=Ishanhirani11&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true&title_color=0366d6&icon_color=0366d6"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ishanhirani11&layout=compact&langs_count=6&theme=default&hide_border=true&title_color=0366d6"/>
</p>
