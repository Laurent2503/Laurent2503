# Laurent Julia Calac

### Data Science · Machine Learning · NLP · AI

**M.S. Data Science & Analytics (AI) · Georgetown University**
**AI R&D Intern · Foerster Group, Germany**
**Former NCAA Division I Tennis Player · Georgia Southern**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-333333?style=flat\&logo=gmail\&logoColor=white)](mailto:YOUR-EMAIL)

---

## 👋 About Me

I'm a **Data Science & Analytics master's student at Georgetown University**, focused on machine learning, NLP, and building data systems around messy real-world problems.

I like projects where the answer isn't obvious at the start — whether that's turning **20 years of industrial inspection files into a searchable data platform**, comparing deep learning architectures for **ECG classification**, or analyzing **half a million Wikipedia biographies for gender bias**.

I especially enjoy the space between the technical and business sides: figuring out what problem actually needs to be solved, building something that answers it, and communicating the results clearly to the people who will use them.

Before data science, I spent most of my time on a tennis court. I played **NCAA Division I tennis** while earning my B.S. in Information Technology and now help Georgetown's tennis programs as a volunteer graduate assistant. Competitive tennis taught me how to work through problems, adapt quickly, and stay composed when the first approach doesn't work — skills that translate surprisingly well to data science.

I graduate in **May 2027** and am currently looking for **Data Science and Machine Learning roles**.

---

## 🚀 Featured Projects

### 🏭 Inspection Data Platform

**Foerster Group · AI R&D Internship · Summer 2026**

> Turning 20 years of fragmented industrial inspection data into one searchable platform.

Foerster's inspection teams test tubes inside industrial reformer furnaces, with each job producing database backups, Excel files, and customer reports. The data existed, but searching or analyzing historical inspections required significant manual work.

I built an end-to-end pipeline and analytics application that consolidated **4,000+ files from 2,000+ inspections spanning 20 years**.

* 🔄 **Import pipeline:** Automatically restores proprietary SQL Server backups and loads their tables into a centralized SQLite archive while handling schema changes across software versions
* 📊 **Excel parser:** Dynamically identifies headers and defect columns across inconsistent report formats and extracts flagged tubes and bending measurements
* 🔎 **Interactive dashboard:** Built a Streamlit application with drill-down filters for customer, region, year, furnace, and inspection type, with inspection status based on the API 579-1 fitness-for-service standard
* 🤖 **LLM experiments:** Tested local open-source models including Qwen and SQLCoder through Ollama and Hugging Face for translating natural-language questions into SQL queries

**Tech:** `Python` `SQL Server` `SQLite` `pandas` `pyodbc` `Streamlit` `Ollama` `Hugging Face`

> 🔒 Built for Foerster Group — source code and company data are private.

---

### 🫀 [ECG Arrhythmia Detection](https://github.com/Laurent2503/ecg-arrhythmia-detection)

> Can a Transformer read a heartbeat better than a CNN?

My team and I compared multiple deep learning architectures for ECG arrhythmia classification using the MIT-BIH Arrhythmia Database: a spectrogram-based CNN, a Transformer operating directly on raw waveforms, and a hybrid architecture.

Because arrhythmia classes are heavily imbalanced, we also experimented with **focal loss and SMOTE** to improve minority-class performance.

**Key results:**

* 📈 Spectrogram CNN achieved **99.0% accuracy** and **0.93 macro F1**
* 🧠 On raw waveforms, the Transformer increased macro F1 from **0.71 to 0.86** compared with a comparable CNN
* 🔬 Compared how different representations — raw signals and spectrograms — affect deep learning performance on time-series data

**Tech:** `PyTorch` `EfficientNet` `Transformers` `NumPy` `Google Colab`

---

### 📚 [Gender Bias in Wikipedia Biographies](https://github.com/Laurent2503/wikipedia-gender-bias-nlp)

> Are Wikipedia biographies of women written differently than biographies of men?

We scraped and processed **573,000+ Wikipedia biographies** and used NLP and statistical testing to investigate whether writing patterns differed by gender.

We compared three sentiment approaches — **VADER, TextBlob, and RoBERTa** — and tested whether the observed differences were statistically significant.

**Key findings:**

* 📝 All three sentiment models identified differences in tone between biographies of men and women
* 📊 Biographies of women showed measurably more positive and subjective language
* 🧪 Statistical testing was used to determine whether observed differences were likely to reflect systematic patterns rather than sampling noise
* ⚙️ Built a large-scale scraping, cleaning, NLP, and analysis pipeline for **573K+ documents**

**Tech:** `Python` `Hugging Face` `RoBERTa` `BeautifulSoup` `SciPy` `pandas` `pytest`

---

## 🛠️ Tech Stack

### Languages & Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat\&logo=mysql\&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat\&logo=numpy\&logoColor=white)

### Machine Learning & AI

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat\&logo=pytorch\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat\&logo=scikitlearn\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat\&logo=ollama\&logoColor=white)

### Databases & Tools

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat\&logo=sqlite\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat\&logo=git\&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat\&logo=streamlit\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat\&logo=jupyter\&logoColor=white)

**Also:** SQL Server · SciPy · BeautifulSoup · pyodbc · pytest · Poetry · Google Colab

---

## 🤝 Let's Connect

I'm always happy to talk about **data science, machine learning, AI, or tennis**.

I'm graduating from Georgetown in **May 2027** and am currently exploring **Data Science and Machine Learning opportunities**.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Send_me_an_Email-333333?style=for-the-_)]()
