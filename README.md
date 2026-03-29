# Resume-Scanner
An AI-powered Applicant Tracking System (ATS) that uses NLP and Machine Learning to rank resumes, predict job categories, and visualize skill gaps.

# AI-Powered Resume Scanner & ATS Optimizer 📄🤖

An intelligent resume screening system designed to bridge the gap between job seekers and recruiters. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automate the candidate evaluation process.

## 🌟 Key Features
* **ATS Scoring Engine:** Calculates a match percentage between a Resume (PDF) and a Job Description using Cosine Similarity.
* **Job Role Classification:** Automatically classifies resumes into industry categories (e.g., Data Science, Web Dev) using a Random Forest model.
* **Skill Gap Analysis:** Identifies missing keywords from the job description to help candidates optimize their applications.
* **Visual Analytics:** Generates interactive WordClouds and Skill-Match bar charts for instant insights.
* **Web Dashboard:** A clean, user-friendly interface built with Streamlit for real-time analysis.

## 🛠️ Tech Stack
* **Language:** Python 3.9+
* **Framework:** Streamlit (Web UI)
* **NLP:** NLTK, Scikit-learn (TF-IDF Vectorization)
* **Machine Learning:** Random Forest Classifier
* **Data Processing:** Pandas, PyPDF2, PDFPlumber

## 🚀 How to Run Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/resume-scanner.git](https://github.com/yourusername/resume-scanner.git)
   cd resume-scanner
