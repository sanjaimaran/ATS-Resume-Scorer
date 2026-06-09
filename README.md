# AI Resume Screening & ATS Scorer

> End-to-end resume screening web app that semantically scores resumes 
> against job descriptions — not just keyword matching.

## 🔑 Key Results
- 88.3% top-5 matching accuracy
- 91.2% ranking precision
- ~15% better than keyword-only baselines

## 🛠️ Tech Stack
Python · Streamlit · Scikit-learn · TF-IDF · 
Named Entity Recognition · Cosine Similarity · Generative AI

## ✨ Features
- Parses resumes and extracts skills, education & experience via NER
- Semantic matching using TF-IDF vectorization + cosine similarity
- Ranks resumes against job descriptions with precision scoring
- Generative AI module for personalized resume improvement feedback

## 📁 Project Structure
├── app.py              # Main Streamlit application
├── parser/             # Resume parsing & NER pipeline
├── scorer/             # TF-IDF & similarity scoring
├── feedback/           # Generative AI feedback module
├── requirements.txt    # Dependencies
└── README.md
