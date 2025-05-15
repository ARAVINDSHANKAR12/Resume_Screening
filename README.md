# 📄 AI-Powered Resume Screening System

An intelligent resume screening tool that automates the evaluation of job applicants based on skills, experience, and relevance to job descriptions using Natural Language Processing (NLP) and Machine Learning.

## 🚀 Project Overview

This project streamlines the recruitment process by ranking resumes against job descriptions. It reduces manual effort, minimizes human bias, and increases the efficiency of identifying top candidates for a role.

## 🎯 Features

- ✅ **Resume Parsing**: Extracts key details (skills, education, experience) from PDF or DOCX resumes.
- 🤖 **NLP-Based Matching**: Compares resumes with job descriptions using techniques like TF-IDF, cosine similarity, or BERT embeddings.
- 📊 **Candidate Ranking**: Automatically scores and ranks candidates based on how well they match the job description.
- 🔍 **Keyword Highlighting**: Highlights matched and missing skills for transparency.
- 📥 **Batch Resume Screening**: Upload and process multiple resumes at once.
- 📤 **Export Results**: Download screening results as a CSV file.

## 🛠️ Tech Stack

### 🧠 Programming Language:
- **Python 3.x**

### 📚 Libraries & Frameworks:
- **NLP & Text Processing**:
  - `spaCy` – Named Entity Recognition (NER) and linguistic features
  - `NLTK` – Text cleaning and preprocessing
  - `transformers` (Hugging Face) – BERT and other pre-trained models for semantic understanding
  - `scikit-learn` – TF-IDF vectorizer, cosine similarity, and ML algorithms
- **File Handling**:
  - `PyMuPDF (fitz)` – Parsing text from PDF resumes
  - `python-docx` – Parsing DOCX format resumes
- **Data Handling & Visualization**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – (Optional) for visualization
- **Web Application** (optional):
  - `Streamlit` – For interactive user interface
  - `Flask` or `FastAPI` – For backend APIs (if using custom frontend)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/resume-screening.git
cd resume-screening

# Install dependencies
pip install -r requirements.txt
