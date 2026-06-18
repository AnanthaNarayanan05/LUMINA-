# 💡 LUMINA – Retrieval-Augmented Generation Assistant

<div align="center">

### Illuminating Context Through Retrieval-Augmented Generation

A browser-based intelligent document assistant that enables users to upload PDF documents, perform semantic search, and obtain context-aware responses using Large Language Models.

---

![HTML](https://img.shields.io/badge/Frontend-HTML5-orange?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript)
![TensorFlow](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow)
![PDF.js](https://img.shields.io/badge/PDF.js-red?style=for-the-badge)
![Claude](https://img.shields.io/badge/LLM-Claude-blue?style=for-the-badge)
![RAG](https://img.shields.io/badge/Architecture-RAG-purple?style=for-the-badge)

</div>

---

# 🚀 Overview

**LUMINA** is a Retrieval-Augmented Generation (RAG) assistant designed to provide accurate, document-grounded responses from uploaded PDFs.

Instead of relying solely on the language model's internal knowledge, LUMINA retrieves relevant document chunks through semantic similarity search and supplies them as context to Claude, ensuring reliable and source-aware answers.

The system runs entirely inside the browser and combines:

- PDF text extraction
- Semantic chunking
- Universal Sentence Encoder embeddings
- Vector retrieval using cosine similarity
- Guardrail-based hallucination prevention
- Context-aware response generation with Claude
- Revision question generation

---

# ✨ Features

## 📄 Intelligent PDF Processing
- Upload PDF documents
- Automatic text extraction using PDF.js
- Cleaning and preprocessing of text
- Page-aware chunking with overlap

## 🧠 Embedding Generation
- Universal Sentence Encoder (TensorFlow.js)
- Semantic representation of document chunks
- Query embedding generation

## 🔍 Vector Search
- Cosine similarity based retrieval
- Top-K chunk ranking
- Page-aware context retrieval

## 🛡 Guardrail System
- Adjustable similarity threshold
- Hallucination prevention
- Trust score generation
- Confidence visualization

## 💬 Conversational Interface
- ChatGPT-style UI
- Multi-turn conversation memory
- Typing indicators
- Context-preserving interactions

## 📊 Metadata Display
- Source page tracking
- Similarity scores
- Trust score visualization

## 📝 Revision Question Generator
- Automatically creates revision questions
- Extracts important concepts
- Supports active learning

---

# 🏗 Architecture

```text
                PDF Upload
                     │
                     ▼
              PDF Text Extraction
                     │
                     ▼
              Text Cleaning
                     │
                     ▼
            Chunking with Overlap
                     │
                     ▼
         Universal Sentence Encoder
                     │
                     ▼
               Vector Embeddings
                     │
                     ▼
            Cosine Similarity Search
                     │
                     ▼
              Context Retrieval
                     │
                     ▼
              Guardrail Filtering
                     │
                     ▼
              Claude LLM Response
                     │
                     ▼
                User Interface
```

---

# ⚙️ Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript (ES6)

## Libraries
- PDF.js
- TensorFlow.js
- Universal Sentence Encoder

## Language Model
- Anthropic Claude

## Retrieval System
- Cosine Similarity Search

## Architecture
- Retrieval-Augmented Generation (RAG)

---

# 🧩 Core Modules

## Module 1 – Document Processing

Responsible for:

- PDF extraction
- Text cleaning
- Page segmentation
- Chunk generation

---

## Module 2 – Embedding Generation

Uses Universal Sentence Encoder to transform:

- Document chunks
- User queries

into semantic vectors.

---

## Module 3 – Vector Store

Implements:

- Cosine similarity
- Top-K retrieval
- Relevance ranking

---

## Module 4 – Retrieval & Guardrails

Provides:

- Similarity thresholding
- Trust score calculation
- Context filtering
- Hallucination reduction

---

## Module 5 – LLM Generation

Integrates with Claude to:

- Generate grounded answers
- Restrict responses to document context
- Prevent external information leakage

---

## Module 6 – Conversation Memory

Maintains:

- User history
- Multi-turn context
- Recent interactions

---

# 🎯 Key Capabilities

✔ Document-grounded answers

✔ Semantic search

✔ Source page citations

✔ Trust score calculation

✔ Adjustable guardrails

✔ Multi-turn conversations

✔ Revision question generation

✔ Browser-based execution

✔ Interactive UI

---

# 📸 User Interface

The application includes:

- Configuration panel
- API key management
- Drag-and-drop PDF upload
- Progress tracking
- Similarity visualization
- Trust score bar
- Chat interface
- Typing indicators
- Revision question panel

---

# 🔒 Hallucination Prevention

LUMINA employs a guardrail mechanism based on semantic similarity.

If the retrieved context does not meet the specified threshold, the assistant avoids generating unsupported information and informs the user that relevant information could not be found within the document.

---

# 📈 Future Improvements

- Support for DOCX and TXT files
- Persistent vector databases
- Hybrid search
- Reranking models
- Streaming responses
- Multi-document retrieval
- Citation highlighting
- User authentication
- Cloud deployment
- Milvus or Pinecone integration

---

# 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/LUMINA.git
```

Navigate to the project:

```bash
cd LUMINA
```

Run:

```bash
open LUMINA_1.html
```

or simply launch it through a browser.

---

# 📚 Concepts Used

- Retrieval-Augmented Generation (RAG)
- Embeddings
- Semantic Search
- Vector Similarity
- Prompt Engineering
- Large Language Models
- Context Grounding
- Hallucination Mitigation
- Conversational Memory

---

# 👨‍💻 Author

### Anantha Narayanan A

AI/ML Engineer | B.Tech CSE (AI/ML)

CHRIST (Deemed to be University), Bengaluru

LinkedIn:
www.linkedin.com/in/anantha-narayanan-66a0bb2aa

---

# ⭐ If you found this project useful, consider giving it a star!
