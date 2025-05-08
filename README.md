ext Summarizer using Flask & Groq API
A simple and efficient web app that summarizes long pieces of text using Groq LLM API via LangChain. Built with Flask, it provides a user-friendly interface for fast, accurate text summarization.

🚀 Features
🔍 Summarize long texts into concise summaries

⚡ Fast and lightweight Flask backend

🌐 Clean, minimal UI

🤖 Uses LangChain + Groq API for high-performance LLMs

🔐 API key managed securely with .env

🛠️ Tech Stack
Python

Flask

LangChain

Groq API

Python-dotenv

📦 Installation
bash
Copy
Edit
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
pip install -r requirements.txt
🔐 Setup
Create a .env file in the root directory:


touch .env
Add your Groq API key to .env:


Edit
GROQ_API_KEY=your_groq_api_key_here
▶️ Run the App


python app.py
Open http://localhost:5000 in your browser.

📄 Example
Paste any long text, hit Summarize, and get a clean, short summary instantly.

📌 To-Do
Add support for file uploads (PDF, DOCX)

Add history/log of previous summaries

Deploy on PythonAnywhere or Render

🧠 Credits
LangChain

Groq
