## **ClauseEase-AI**

ClauseEase-AI is an AI-powered chatbot that helps you upload PDF or text files, extract and translate their content, generate summaries, and ask interactive questions — all using a **local LLM** (TinyLlama/Ollama).
No cloud APIs are required; everything runs on your device.

---

## **1. Overview**

ClauseEase-AI allows you to:

* Upload PDFs (any language)
* Extract the full text
* Translate the content into English
* Get clear, concise summaries
* Ask follow-up Q&A about the document

---

## **2. Features**

### **PDF Processing**

* Upload and parse PDF files of any language
* Extracts text from multi-page documents

### **TXT File Processing**

* Accepts `.txt` files for quick summarization
* Detects the original language automatically
* Translates the entire content into English

### **Summarization & Document Q&A**

* Generates easy-to-read English summaries
* Allows users to ask questions about the uploaded document
* Q&A responses are generated using the local LLM

---

## **3. Model & Local Inference**

* Uses **Ollama** to run language models locally
* Supports lightweight models like **TinyLlama** (works on 8GB RAM systems)
* No cloud API or internet required
* All processing happens **offline on your machine**

---

## **4. Streamlit Interface**

* Simple and clean web UI
* Upload section + Chat window
* Sidebar shows:

  * Upload controls
  * Chat history
  * Model status
* Provides real-time responses as you type

---

## **5. How It Works**

1. Start your Ollama model (TinyLlama/recommended lightweight LLM)
2. Run the Streamlit app
3. Upload PDF/TXT files
4. View extracted text, summaries, translations
5. Chat and ask questions about the document

---

