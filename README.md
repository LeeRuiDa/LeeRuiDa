ChatGPT




alright, you have access to my github repo, I'm wiling to generate a github profile that shows my profile, and this through GPRM

Worked for 1m 34s

Analyzed
from pathlib import Path

readme = """<h1 align="center">Hi 👋, I'm Rida Boubakr</h1>

<h3 align="center">Software Engineering Graduate · AI Security · Machine Learning · Backend Development</h3>

<p align="center">
  <a href="mailto:ridaboubakr@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/LeeRuiDa">
    <img src="https://img.shields.io/badge/GitHub-LeeRuiDa-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

## 👨‍💻 About Me

I am a **Software Engineering graduate from Sichuan University** focused on building reliable AI and data-driven software systems.

- 🛡️ Interested in **AI safety, LLM security, jailbreak detection, and prompt-injection defence**
- 🤖 Experienced with **machine learning, RAG systems, computer vision, and explainable AI**
- ⚙️ Build backend applications and APIs with **FastAPI, Python, SQL, Docker, and Kubernetes**
- 🌍 Based in **Morocco** and open to software, AI/ML, data, backend, and AI-security opportunities
- 🗣️ Arabic (native) · English (B2+) · French (B1+) · Chinese (HSK 4)
- 📫 Reach me at **ridaboubakr@gmail.com**

## 🚀 Featured Projects

### 🛡️ [LLM Jailbreak & Prompt-Injection Detector](https://github.com/LeeRuiDa/llm-jailbreak-detector)

Offline prompt-layer guardrail combining deterministic rules with a LoRA-adapted DeBERTa-v3 classifier. Built a leakage-aware evaluation pipeline and achieved **0.9958 AUROC** on the main stress split while analysing threshold instability under distribution shift.

**Tech:** Python · PyTorch · Hugging Face · LoRA · DeBERTa-v3 · NumPy

---

### 📚 [University Knowledge Base RAG Assistant](https://github.com/LeeRuiDa/University-Knowledge-Base-RAG-Assistant)

Citation-grounded RAG assistant over official university documents using hybrid Qdrant + BM25 retrieval and reranking. Achieved a **0.949 top-1 hit rate**, **0.983 citation hit rate**, and **100% correct refusal rate**.

**Tech:** Python · FastAPI · Streamlit · Qdrant · BM25 · LangChain

---

### 📊 [Customer Churn Prediction System](https://github.com/LeeRuiDa/Customer-Churn-Prediction-System)

End-to-end churn scoring system with batch inference, risk bands, SHAP explanations, experiment tracking, and retention suggestions. XGBoost achieved **0.845 ROC-AUC** and **0.659 average precision**.

**Tech:** Python · SQL/SQLite · scikit-learn · XGBoost · SHAP · MLflow · FastAPI

---

### 🍌 [Banana Shelf-Life Predictor](https://github.com/LeeRuiDa/banana-shelf-life-predictor)

Explainable computer-vision application for banana ripeness classification and day-to-rotten prediction. Achieved **97.56% classification accuracy** and a **1.57-day regression MAE**.

**Tech:** Python · PyTorch · EfficientNet-B0 · Captum · Streamlit · FastAPI

## 🧰 Tech Stack

### Programming & Data

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

### Machine Learning & AI

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" alt="XGBoost">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/SHAP-6A5ACD?style=for-the-badge" alt="SHAP">
</p>

### Backend, RAG & Tooling

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

## 🎓 Education

**Bachelor of Engineering in Software Engineering**  
Sichuan University, Chengdu, China · 2022–2026  
Medium of instruction: English

---

<p align="center">
  <i>Building safer AI systems and practical software that turns data into useful decisions.</i>
</p>
"""

output_path = Path("/mnt/data/LeeRuiDa_Profile_README.md")
output_path.write_text(readme, encoding="utf-8")
print(f"Created {output_path}")
STDOUT/STDERR
Created /mnt/data/LeeRuiDa_Profile_README.md
Great choice. I checked your GitHub: the special LeeRuiDa/LeeRuiDa profile repository already exists, but its README currently only displays “Hi there.” Your six public repositories are also visible, including the LLM detector, RAG assistant, churn system, and banana predictor. 

GitHub automatically displays this repository’s root README.md because its name matches your username and it is public. 

I created a recruiter-focused, GPRM-compatible README using your strongest project results, education, languages, and technical stack from your CV. 


Download
LeeRuiDa_Profile_README.md

How to publish it
Open the LeeRuiDa/LeeRuiDa repository.

Edit the existing README.md.

Delete “Hi there.”

Paste the content from the file.

Commit the changes.

GPRM supports social links, technology badges, statistics, trophies, visitor counters, and other widgets, and its generated Markdown can be pasted into the same repository. 
 I intentionally excluded trophies, memes, donation buttons, visitor counters, and excessive statistics because your projects and measurable results create a more professional job-hunting profile.

The profile currently highlights:

AI safety and LLM security

Machine learning and explainable AI

RAG and backend development

Four featured projects with performance metrics

Python, PyTorch, FastAPI, Docker, Kubernetes, Qdrant, and related tools

Arabic, English, French, and Chinese HSK 4

Availability for opportunities in Morocco

Send your LinkedIn profile URL next, and I’ll add a matching LinkedIn contact badge. 


i think there is no need for the part that syas 🚀 Featured Projects, it mostly just took too much space where projects are actually just at the button public to be shown no need to write about them.
also  About Me part it looks like a it's exctracted from my cv , no need to include too many words and no need to mention lnguages i can speak, just keeep it simple and not too serious

Done. I removed the entire Featured Projects section and made About Me shorter, more natural, and less CV-like. I also removed the languages and reduced the number and size of the badges.

LeeRuiDa_Profile_README_v2.md

It now contains only:

A simple introduction

Email and GitHub links

A brief About Me section

A compact tech stack

Education

A casual closing message 


Library
/
job hunt
/
LeeRuiDa_Profile_README_v2.md


<h1 align="center">Hi, I'm Rida 👋</h1>

<p align="center"> Software Engineering graduate interested in AI, backend development, and building useful software. </p>

<p align="center"> <a href="mailto:ridaboubakr@gmail.com"> <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"> </a> <a href="https://github.com/LeeRuiDa"> <img src="https://img.shields.io/badge/GitHub-LeeRuiDa-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"> </a> </p>

About Me
I enjoy working with Python, machine learning, APIs, and data-focused applications.
Lately, I have been exploring AI security, RAG systems, and backend development.

Based in Morocco.

Tech Stack
<p> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/Git-FF4500?style=flat-square&logo=git&logoColor=white" alt="Git"> </p>

Education
Bachelor of Engineering in Software Engineering
Sichuan University · 2022–2026

<p align="center"> Thanks for stopping by 🙂 </p>

