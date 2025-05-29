# 🤖 Chatbot Assistant with PDF & Image Support

A minimal yet powerful chatbot that can read your **PDFs and images**, extract context, and answer questions using **LLaMA 3**, **Pinecone**, and **Groq**! Perfect for reading lecture notes, scanned documents, or any reference material.

---

## 🚀 Features

- 🧠 LLaMA 3 (via Groq) for intelligent responses
- 📄 PDF & 🖼️ image (OCR) text extraction
- 🧩 Context chunking and semantic embeddings
- 🔍 Fast similarity search using Pinecone
- 🖥️ Interactive & clean CLI for chatting

---

## 🛠️ Tech Stack

| Tech         | Purpose                        |
| ------------ | ------------------------------ |
| 🦙 Groq      | Chat completions (LLaMA 3)     |
| 🌲 Pinecone  | Vector DB for fast similarity  |
| 🧠 SBERT     | SentenceTransformer embeddings |
| 🧾 PDFMiner  | PDF text extraction            |
| 🧿 Tesseract | OCR for scanned PDFs/images    |
| 🪄 LangChain | Text splitting utility         |

---

## 📥 Installation

```bash
git clone https://github.com/MaazDev7/chatbot-assistant.git
cd chatbot-assistant
pip install -r requirements.txt
```

## 📜 License

MIT License © MaazDev7
