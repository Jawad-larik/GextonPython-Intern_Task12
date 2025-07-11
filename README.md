# GextonPython-Intern_Task12

````markdown
# 🧠 AI-Based Resume Screening System

This project is a smart resume screening tool built using Python and Streamlit. It helps automatically compare multiple resumes against a job description using modern Natural Language Processing (NLP) techniques. Resumes are ranked based on how closely they match the job description.

---

## 🚀 Features

- Upload resumes in **PDF** or **DOCX** format
- Upload job descriptions in **TXT** format
- Automatically extract and clean resume text
- Match resumes using **semantic similarity** with BERT embeddings
- Extracts key sections: **Skills, Education, Experience**
- Ranks resumes based on relevance (% match)
- Displays results in a sortable table
- Allows you to **download ranked results as CSV**
- Lightweight and easy to run using **Streamlit**

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** (GUI)
- **sentence-transformers** (for semantic similarity)
- **PyMuPDF (fitz)** for PDF parsing
- **python-docx** for DOCX parsing
- **NLTK** for text preprocessing

---

## 📁 How to Run

### 1. Clone the Repository
```bash
git clone [https://github.com/Jawad-larik/GextonPython-Intern_Task12.git]/resume-screening-app.git
cd resume-screening-app
````

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Start the App

```bash
streamlit run app.py
```

---

## 📂 Input Format

* 📄 **Job Description**: `.txt` file (plain text)
* 📁 **Resumes**: `.pdf` or `.docx` files

---

## 📤 Output

* 📊 Table showing match percentage, resume name, and extracted sections
* 📥 Option to download the results as `ranked_resumes.csv`

---

## 🔐 Note

This project is intended for educational purposes and small-scale HR simulations. It doesn't replace professional HR software or detailed human analysis.

---

## 👨‍💻 Author

**Jawad Larik**
BS Information Technology, University of Sindh
[LinkedIn](https://linkedin.com/in/jawad-larik01) | [GitHub](https://github.com/Jawad-larik/GextonPython-Intern_Task12.git)

---

## 📜 License

This project is open-source and free to use for non-commercial and educational purposes.

```
