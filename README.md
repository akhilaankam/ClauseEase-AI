# ClauseEase-AI
1. Overview
ChatBot is an AI-powered tool that lets you upload PDFs (in any language), extracts all text, translates it into English, and provides a clear, concise summary. It also supports interactive Q&A — you can ask follow-up questions about the document to explore details seamlessly.
2. Features
PDF Processing:
Upload and parse PDF files of any language
Extract text from multi-page documents
TXT Processing:
Accept plain text files for quick summarization
Language Detection & Translation
Detects the document’s original language
Translates entire content into English
Summarization & Document Q&A:
Produces easy-to-read English summaries
Allows user to ask questions about the uploaded content
Responses are generated from the translated text using a local LLM
3. Model & Local Inference
Uses Ollama to run language models locally
Supports lightweight models suitable for modest hardware (e.g. 8 GB RAM) such as TinyLlama or equivalent small-scale models
No external cloud API required — all processing happens on your machine
4. Streamlit Interface
Simple and clean web UI with upload area and chat window
Sidebar shows upload controls and chat history
Status indicator shows whether Ollama is running or not
Minimalistic design for ease of use
5. Running the Project
Install Ollama from the official site
Pull a small model:
ollama pull tinyllama
Install Python dependencies:
pip install -r requirements.txt
Start Ollama server:
ollama serve
Run the Streamlit app:
streamlit run app.py
