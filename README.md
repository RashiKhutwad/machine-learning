# Resume Screening AI Web App

An AI-powered web application that automatically analyzes resumes and predicts how well they match a given job description.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to help recruiters shortlist the most relevant candidates faster and more objectively.

---

## Features

* **Resume Upload:** Users can upload their resume in `.pdf` or `.docx` format.
* **Text Extraction:** Extracts key information like skills, education, and experience using NLP.
* **AI Matching Model:** Compares the extracted text with the job description using vector similarity or classification models (TF-IDF / BERT).
* **Match Score:** Displays how closely the resume aligns with the role (in %).
* **AI Feedback:** Generates improvement suggestions (e.g., missing keywords or weak sections).
* **Web Interface:** Simple, responsive web app built with Flask or Streamlit.

---

## Tech Stack

| Category         | Tools / Libraries                                     |
| ---------------- | ----------------------------------------------------- |
| **Frontend**     | Streamlit UI                                          |
| **Backend**      | Python                                                |
| **NLP / ML**     | Scikit-learn, NLTK, spaCy, TF-IDF, or BERT embeddings |
| **File Parsing** | PyPDF2, docx2txt                                      |


---

## Workflow

1. **User uploads resume** → Extracted and cleaned using `PyPDF2` or `docx2txt`.
2. **Job description** → Entered manually or uploaded.
3. **NLP vectorization** → TF-IDF or SentenceTransformer (BERT).
4. **Model predicts** → Cosine similarity / ML classifier outputs “Match Score.”
5. **Result generated** → Shown on dashboard + AI suggestions for improvement.

---

## Example Output

| Candidate Name | Match % | Missing Keywords      | Verdict              |
| -------------- | ------- | --------------------- | -------------------- |
| Rashi Khutwad  | 86%     | Deep Learning, Docker | Strong Fit ✅         |
| John Doe       | 52%     | Python, NLP           | Needs Improvement ⚠️ |

---

## Future Enhancements

* Integrate **ChatGPT-style feedback bot (ARIS)** for resume advice.
* Add **LinkedIn integration** to auto-fetch profiles.
* Build **Admin Dashboard** for recruiters to manage results.
* Train a **custom BERT model** on resume datasets for better accuracy.

---

## Author

**Rashi Khutwad**
B.Tech in Information Technology | AI & ML Enthusiast


