# Generative-AI-with-

# 📄 Resume Parser & LLM Experiments

This repository contains:
1. **LLM Experiments Notebook** — A Jupyter notebook exploring different Large Language Models (LLMs) and their capabilities.
2. **Resume Parser App** — A Streamlit-based application that uses Google's Gemini model to parse resumes into structured JSON format.

---

## 🚀 Features

- **Multiple LLM Integration**: Test and compare different models in the notebook.
- **Resume Parsing**: Upload resumes in PDF, DOCX, or TXT formats and extract:
  - Name
  - Email
  - Phone
  - LinkedIn
  - Skills
  - Education
  - Experience
  - Projects
  - Certifications
  - Languages
- **Automatic JSON Output**: Returns clean, structured JSON output for easy integration into other systems.

---

## 🛠 Technologies Used
- LangChain — LLM orchestration
- Google Gemini API — AI model for parsing
- Streamlit — Web app interface
- [PyPDFLoader, Docx2txtLoader, TextLoader] — Resume document loaders
- Python 3.9+

## 📂 Project Structure
.
├── 1_working_with_different_LLMs.ipynb   # LLM experiments notebook
├── 2_Resume_Parser_app.py                # Streamlit resume parser app
├── requirements.txt                       # Python dependencies
└── README.md                              # Project documentation


## 🔑 Environment Variables
- Create a `.env` file in the root directory and add your Google API Key:
- GOOGLE_API_KEY=your_google_api_key_here


## 📦 Installation

pip install langchain_openai langchain-google-genai python-dotenv streamlit
pip install -U langchain-community
pip install pypdf


```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# Install dependencies
pip install -r requirements.txt
