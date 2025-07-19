# 📄 Resume Checker — ATS Score & Role Matcher

An AI-powered resume analyzer built with **Gradio** that evaluates how well a resume matches a given job description (JD). It uses **OCR**, **NLP**, and predefined skill sets to score your resume and recommend the most suitable job roles.

---

## 🚀 Features

- 🔍 **Text Extraction** from PDF resumes using OCR (Tesseract + pdf2image)  
- 🧠 **Keyword Matching** against 10+ tech roles like AI/ML, Web Dev, Cybersecurity, etc.  
- 📊 **ATS Match Score** visualization with a pie chart  
- 💼 **Role Suggestions** based on skills found in the resume  
- 🧾 **Smart Feedback** for resume improvement  
- 🌐 **Gradio UI** for easy and interactive use  

---

## 🔧 Tech Stack

- Python  
- Gradio  
- Tesseract OCR  
- PyMuPDF  
- pdf2image  
- NLTK  
- Matplotlib  

---

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install poppler-utils
