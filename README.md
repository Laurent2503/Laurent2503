# Hi, I'm Laurent

I'm a Data Science & Analytics master's student at **Georgetown University** (AI concentration), graduating in May 2027. I like projects that start with messy, real-world data and end with an answer you can actually defend, whether that's classifying heartbeats or measuring bias across half a million Wikipedia articles.

Before data science, my life revolved around a tennis court. I played **Division I tennis at Georgia Southern** while earning my B.S. in Information Technology, and I still help out as a volunteer graduate assistant with Georgetown's tennis programs. Tennis taught me to stay patient, adjust mid-match, and keep grinding when something isn't working. That turns out to be pretty useful when a model won't converge.

This past summer I worked as an **AI & Data Science Intern at Foerster Group in Germany**, and I'm now looking for **Data Science and Machine Learning** roles.

---

## What I've been working on

### Inspection Data Platform · Foerster Group (Internship, Summer 2026)
*Built for the company, so the code is private, but here's what I did.*

Foerster's inspection teams test tubes inside industrial reformer furnaces, and every job leaves behind a pile of files: database backups from the inspection software, Excel sheets with hand-marked defects, and customer reports. All that data existed, but you couldn't search or analyze it without a lot of manual digging. I built an end-to-end pipeline and dashboard that brings **20 years of inspection history** into one searchable place: **4,000+ files from 2,000+ inspections**.
- **Import pipeline:** automatically restores each proprietary SQL Server backup and loads every table into a central SQLite archive, handling two decades of schema changes across software versions
- **Excel parser:** finds headers and defect columns dynamically across inconsistent file formats, then extracts every flagged tube and bending measurement
- **Interactive dashboard:** Streamlit app with drill-down filters (customer, region, year, furnace, inspection type) that flags each job as clear, needs monitoring, or critical, based on the API 579-1 fitness-for-service standard
- **LLM experiments:** tested local open-source models (Qwen, SQLCoder via Ollama and Hugging Face) for turning plain-English questions into SQL queries against the archive

`Python` `SQL Server` `SQLite` `pandas` `pyodbc` `Streamlit` `Ollama` `Hugging Face`

### 🫀 [ECG Arrhythmia Detection](https://github.com/Laurent2503/ecg-arrhythmia-detection)
Can a Transformer read a heartbeat better than a CNN? My team and I tested that on the MIT-BIH Arrhythmia Database, comparing a spectrogram-based CNN, a Transformer on raw waveforms, and a hybrid of the two. The data is heavily imbalanced, so we also leaned on focal loss and SMOTE.
- The CNN baseline hit **99.0% accuracy** and **0.93 macro F1**
- On raw waveforms, the Transformer beat a comparable CNN, lifting macro F1 from **0.71 to 0.86**

`PyTorch` `EfficientNet` `Transformers` `NumPy` `Google Colab`

### 📚 [Gender Bias in Wikipedia Biographies](https://github.com/Laurent2503/wikipedia-gender-bias-nlp)
Are Wikipedia biographies of women written differently than those of men? We scraped and cleaned **573,000+ biographies**, ran them through three sentiment models (VADER, TextBlob, and RoBERTa), and tested the differences statistically. All three models agreed: articles about women are written in a measurably more positive and subjective tone.

`Python` `Hugging Face` `RoBERTa` `BeautifulSoup` `SciPy` `pandas` `pytest`

---

## Tools I use

**Languages:** Python, SQL  
**ML / Deep Learning:** PyTorch, scikit-learn, Hugging Face Transformers, Ollama (local LLMs)  
**Data & Databases:** pandas, NumPy, SciPy, SQLite, SQL Server  
**Workflow & Apps:** Git, Streamlit, Jupyter, Google Colab, Poetry, pytest

---

## Let's connect

Always happy to talk about data science, ML, or tennis.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/laurent-julia-calac/)
[![Email](https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:laurent.juliacalac@gmail.com)
