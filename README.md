# telegram-genai-bot
Hybrid GenAI Telegram Bot with Mini-RAG and Vision AI — Built with Python, Groq LLM, and sentence-transformers
🤖 Hybrid GenAI Telegram Bot

A lightweight Generative AI Telegram Bot that combines 
Mini-RAG (Retrieval-Augmented Generation) and Vision AI 
in a single bot.

✅ Features:
- /ask  → Answers questions from a local knowledge base using RAG
- /image → Describes uploaded images with captions and tags
- /summarize → Summarizes your last 3 interactions
- /help → Shows all commands

🧠 Tech Stack:
- Bot Framework  : python-telegram-bot
- Embeddings     : all-MiniLM-L6-v2 (runs locally, no API needed)
- LLM            : Groq llama-3.3-70b-versatile (free)
- Vision Model   : Groq llama-4-scout-17b (free)
- Vector Store   : SQLite (local database)
- Cache          : In-memory query cache
- History        : Per-user message history (last 3)

📁 Knowledge Base:
- AI & Machine Learning basics
- Python programming tips
- Company HR policy
- Tech FAQ
- Indian recipes

🚀 Run locally:
pip install -r requirements.txt

python bot.py
