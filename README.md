# Research_paper_app
A Streamlit-based web app that allows users to upload a research paper PDF and ask questions about its content. The app uses Retrieval-Augmented Generation (RAG) powered by FAISS for semantic search and the Groq API (LLaMA 3.3 70B) to generate accurate, natural-language summaries and answers.

🚀 Features
📤 Upload research papers in PDF format

🧠 Extract and chunk text for efficient processing

🔎 Semantic search using FAISS and Sentence Transformers

🤖 AI-generated answers and summaries using Groq's LLaMA 3.3 70B model

📥 Download the generated summary as a text file

🌐 Works in Colab with LocalTunnel for public sharing


🛠️ Tech Stack
Streamlit – Web app framework

pdfplumber – PDF text extraction

FAISS – Fast similarity search over embeddings

Sentence Transformers – Embedding model (all-MiniLM-L6-v2)

LangChain – Text splitting utilities

Groq API – Large language model (LLaMA 3.3 70B) for response generation


Install dependencies:
pip install -r requirements.txt

Set your Groq API key in your environment:

export GROQ_API_KEY="your_groq_api_key"

Run the app locally:

streamlit run app.py




