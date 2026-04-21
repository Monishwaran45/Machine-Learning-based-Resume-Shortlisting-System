# Machine-Learning-based-Resume-Shortlisting-System
An intelligent machine learning system that automates resume screening by analyzing candidate resumes and matching them with job descriptions using advanced NLP techniques and hybrid scoring.

---

## 🔥 Key Features

* 📄 **Multi-format Resume Parsing**
  Extracts and processes resumes from PDF and DOCX formats.

* 🧠 **Semantic Matching (NLP)**
  Uses transformer-based embeddings (Sentence-BERT) to measure similarity between resumes and job descriptions.

* 🎯 **Smart Skill Extraction (NER)**
  Identifies relevant skills using NLP techniques for accurate candidate profiling.

* ⚖️ **Hybrid Scoring System**
  Combines:

  * NLP similarity score
  * Weighted skill matching
  * Semantic skill relevance

* 🔍 **Explainable AI (XAI)**
  Provides:

  * Matched skills
  * Missing skills
  * Transparent scoring breakdown

* 🏆 **Candidate Ranking System**
  Automatically ranks candidates based on final score.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **Sentence Transformers (BERT)**
* **spaCy (NLP & NER)**
* **pdfplumber / python-docx**

---

## ⚙️ Workflow

```text
Resume (PDF/DOCX)
   ↓
Text Extraction
   ↓
Preprocessing (Cleaning + Stopword Removal)
   ↓
Skill Extraction (NER)
   ↓
Embedding Generation (BERT)
   ↓
Similarity + Weighted Scoring
   ↓
Ranking + Explainability
```

---

## 📊 Output

* Candidate ranking
* Match score (0–1)
* Skill match analysis
* Selection decision

---

## 🚀 Future Enhancements

* 🌐 Web App (FastAPI + React)
* 🤖 LLM-based reasoning for candidate evaluation
* 📊 Interactive recruiter dashboard
* 🔍 Fake experience detection
* 📈 Model optimization & tuning

---

## 💡 Use Cases

* Automated recruitment systems
* HR tech platforms
* Resume screening tools
* Talent acquisition analytics

---
Dataset Kaggle : https://www.kaggle.com/datasets/palaksood97/resume-dataset/data
## 🧠 Project Highlights

This project demonstrates:

* End-to-end ML pipeline design
* NLP-based semantic understanding
* Feature engineering & scoring strategies
* Explainable AI for decision transparency

---

## 📌 Author

**Monish**
AI & ML Enthusiast | Building intelligent systems 🚀
