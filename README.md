# StudyEasyBot 🤖

**StudyEasyBot** is a Telegram bot designed to help students understand and simplify complex educational or legal content.  
It can summarize, explain, and answer questions based on either direct text input or uploaded PDF documents.

## ✨ Features
- **Text Summarization** – Condenses large and complex text into clear, concise summaries.
- **Simplified Explanations** – Converts complicated terms and concepts into easy-to-understand language.
- **Q&A System** – Answers user questions using context from provided text or PDF files.
- **Multi-Format Input** – Supports direct text messages or PDF uploads.
- **LLM & NLP Integration** – Powered by Large Language Models and advanced Natural Language Processing.
- **RAG (Retrieval-Augmented Generation)** – Retrieves relevant information to improve answer accuracy.

## 🛠️ Tech Stack
- **Python**
- **Hugging Face Transformers**
- **Sentence Transformers**
- **FAISS** (for vector search)
- **pdfplumber** / **PyPDF2** (PDF parsing)
- **Telegram Bot API**
- **Text Preprocessing & Tokenization**

## 🚀 How It Works
1. User sends text or uploads a PDF to the bot.
2. The bot extracts and processes the content.
3. LLM + RAG pipeline generates summaries, explanations, and answers to user queries.
4. Results are sent back in clear, student-friendly language.
