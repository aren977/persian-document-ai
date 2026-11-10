# 🇮🇷 Persian Document AI Assistant

### An AI-powered Question Answering System for Persian Documents

A Persian-language AI assistant that enables users to upload PDF and TXT documents and ask natural-language questions about their content.

Built using **Retrieval-Augmented Generation (RAG)**, semantic search, and Large Language Models (LLMs), this project aims to make information retrieval from Persian documents faster and easier.

---

## ✨ Features

- 📄 **PDF & TXT Support** – Upload and process PDF and text documents.
- 💬 **Intelligent Question Answering** – Ask questions about document content.
- 🔍 **Semantic Search** – Retrieve relevant information using vector embeddings.
- 🧠 **LLM Integration** – Generate context-aware answers using Qwen 2.5 3B.
- 🇮🇷 **Persian Language Processing** – Support for Persian text and document content.
- 🖥️ **Interactive UI** – User-friendly interface powered by Gradio.

---

## 🛠️ Technologies & Tools

| Technology | Description |
|---|---|
| Python | Core programming language |
| Qwen 2.5 3B | Large Language Model |
| FAISS | Vector similarity search |
| Sentence Transformers | Text embedding generation |
| Multilingual E5 | Multilingual embeddings |
| PyMuPDF | PDF text extraction |
| Hazm | Persian text processing |
| Gradio | Interactive web interface |
| Google Colab | Development environment |

---

## ⚙️ How It Works

The system follows a Retrieval-Augmented Generation (RAG) pipeline:

1. **Document Upload:** Users upload PDF or TXT files.
2. **Text Extraction:** Document content is extracted.
3. **Text Processing:** Extracted text is prepared for processing.
4. **Embedding Generation:** Text is converted into numerical vector representations.
5. **Semantic Retrieval:** FAISS searches for relevant document segments.
6. **Answer Generation:** Qwen 2.5 3B generates answers based on the retrieved context.

---

## 🚀 Getting Started

### Requirements

- Google Account
- Google Colab
- Internet Connection

### Run the Project

1. Open `rezome_1.ipynb` using Google Colab.
2. Execute the notebook cells in order.
3. Upload a PDF or TXT document.
4. Enter your question.
5. Get an AI-generated answer based on the uploaded document.

---

## 📁 Project Structure

```text
persian-document-ai/
│
├── rezome_1.ipynb
└── README.md
```

---

## 🎯 Project Goals

This project demonstrates practical applications of:

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Natural Language Processing (NLP)
- Semantic Search
- Vector Databases
- Persian Text Processing

---

## 👨‍💻 Author

**AI & Machine Learning Developer**

