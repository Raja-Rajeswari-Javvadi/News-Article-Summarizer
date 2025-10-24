# 🧠 Text & URL Summarizer App

A simple yet powerful **Flask web application** that can summarize either:
- Custom user-input text, or
- Full-length news articles from any **URL**.

It uses the **Facebook BART-Large-CNN** model from **Hugging Face Transformers** for generating concise summaries, and **Newspaper3k** for extracting article content from news websites.

---

## 🌟 Features

- 📰 **Summarize Articles** – Automatically extracts and summarizes article text from any valid URL.  
- ✍️ **Summarize Custom Text** – Paste any paragraph or essay and get a clear summary instantly.  
- ⚡ **Transformer-powered** – Uses the pre-trained `facebook/bart-large-cnn` model for high-quality results.  
- 💻 **Flask Web App** – Clean and simple web interface built using Flask.  
- ☁️ **ngrok Support** – Easily run and expose your app online for demos or testing.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, CSS, Jinja2 |
| **Backend** | Flask (Python) |
| **Model** | Hugging Face Transformers (`facebook/bart-large-cnn`) |
| **Article Extraction** | Newspaper3k |
| **Hosting (optional)** | ngrok / Render / Vercel |

---
