# 📄 AI Resume Analyzer - RAG Chatbot

An AI-powered Resume Analyzer built with Python, RAG (Retrieval-Augmented Generation), FAISS, Sentence Transformers, Groq, and Gradio.

The application allows users to upload any resume PDF, process it, generate a resume summary, and ask questions about the candidate.

## 🚀 Features

- Upload any PDF resume
- Extract resume text using PyPDF
- Split resume text into chunks
- Generate embeddings using Sentence Transformers
- Store embeddings using FAISS
- Retrieve relevant resume information
- Analyze resume information using Groq
- Generate an automatic resume summary
- Ask questions about the uploaded resume
- Interactive Gradio interface
- Supports different resumes without mixing previous resume data

## 🛠️ Technologies Used

- Python
- PyPDF
- Sentence Transformers
- FAISS
- Groq API
- Gradio
- NumPy
- RAG (Retrieval-Augmented Generation)

## 🔄 RAG Workflow

```text
Resume PDF
    ↓
Text Extraction
    ↓
Chunking
    ↓
Embeddings
    ↓
FAISS Vector Database
    ↓
Relevant Information Retrieval
    ↓
Groq LLM
    ↓
AI Resume Analysis
```

## 💬 Example Questions

- What is the candidate's experience?
- What are the candidate's technical skills?
- What programming languages does the candidate know?
- What projects has the candidate completed?
- What internships did the candidate do?
- What is the candidate's educational qualification?
- What certifications does the candidate have?
- Give me a summary of this resume.

## 📁 Project Structure

```text
AI-Resume-RAG/
│
├── app.py
├── requirements.txt
└── README.md
```

## 🔐 API Key Security

The Groq API key should **never** be hard-coded or uploaded to GitHub.

Use an environment variable:

```text
GROQ_API_KEY
```

For deployment, add the API key through the hosting platform's Secrets/Environment Variables settings.

## ▶️ Run Locally

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Set the Groq API key

Windows PowerShell:

```powershell
$env:GROQ_API_KEY="your_groq_api_key"
```

Linux/macOS:

```bash
export GROQ_API_KEY="your_groq_api_key"
```

### 3. Run the application

```bash
python app.py
```

## 🎯 Project Goal

The goal of this project is to demonstrate how Retrieval-Augmented Generation can be used to build an AI application that retrieves relevant information from a user's resume before generating an answer.

## 👨‍💻 Author

AI Resume Analyzer project built as a Python/AI project using RAG.
