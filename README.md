# 🧠 Resume-JD Matcher

This project uses **Natural Language Processing (NLP)** to compute the similarity between a **resume** and a **job description (JD)** using **TF-IDF** and **Cosine Similarity**. It's a smart and simple way to see how well a resume aligns with a job post — great for both **job seekers** and **recruiters**!

---

## 🚀 Features

- Resume and JD text preprocessing
- TF-IDF vectorization
- Cosine similarity match scoring
- Keyword-based analysis
- Easily extensible for multiple resumes or JDs

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- NLTK
- Scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- Regex (for text cleaning)

---

## 📂 File Structure

```bash
resume-jd-matcher/
│
├── resume_jd_matcher.py       # Main script
├── resume.txt                 # Sample resume text
├── job_description.txt        # Sample job description
├── requirements.txt           # Required libraries
└── README.md                  # Project overview
