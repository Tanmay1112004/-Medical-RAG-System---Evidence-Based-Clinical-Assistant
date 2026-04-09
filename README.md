# 🏥 Medical RAG System — Evidence-Based Clinical Assistant

> **Production-ready Retrieval-Augmented Generation (RAG) system for accurate, source-backed medical intelligence.**

A full-stack **Generative AI application** that eliminates hallucinations by grounding responses in verified medical documents using **Google Gemini AI + vector search**.

---

## 🚀 Demo Preview

> *(Add UI screenshots: upload → query → answer with citations)*

---

## 💡 Problem Statement

Modern AI tools fail in critical domains like healthcare:

❌ Hallucinated medical advice
❌ No traceable sources
❌ Information overload from large documents

👉 This system fixes that by making AI **evidence-driven, not opinion-driven**.

---

## 🎯 Solution

This project implements a **RAG pipeline**:

* 📄 Ingest medical PDFs (WHO, research papers, protocols)
* 🔍 Convert into semantic embeddings
* 📚 Retrieve relevant context
* 🤖 Generate answers strictly from that context

👉 Result: **Accurate, explainable, citation-backed responses**

---

## ✨ Key Features

### 🧠 Evidence-Based AI

* Answers strictly from uploaded documents
* No external hallucinated knowledge

### 📌 Source Citations

* Every response includes traceable references
* Transparency for medical decision support

### 📄 PDF Intelligence

* Extracts and processes medical documents
* Supports guidelines, research papers, protocols

### 🔎 Semantic Search

* Vector-based similarity search
* Context-aware retrieval (not keyword matching)

### 🎨 Streamlit UI

* Clean, interactive interface
* Real-time feedback and results

### 🗂️ Document Management

* Track uploaded files
* View chunk stats
* Reset database anytime

---

## 🏗️ System Architecture

```
User Query
    ↓
Embedding Generation
    ↓
Vector Search (ChromaDB)
    ↓
Top-K Context Retrieval
    ↓
Prompt + Context Injection
    ↓
Gemini LLM
    ↓
Answer + Citations
```

---

## 🧠 Core Technologies

| Layer              | Technology             |
| ------------------ | ---------------------- |
| **LLM**            | Google Gemini          |
| **Embeddings**     | Gemini embedding model |
| **Vector DB**      | ChromaDB               |
| **Backend Logic**  | Python                 |
| **Frontend**       | Streamlit              |
| **PDF Processing** | PyPDF                  |
| **Text Chunking**  | LangChain              |

---

## ⚡ Quick Start

### 🔹 1. Clone Repository

```bash
git clone https://github.com/Tanmay1112004/medical-rag-system.git
cd medical-rag-system
```

---

### 🔹 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 🔹 3. Run Application

```bash
streamlit run medical_rag_system.py
```

👉 Open: `http://localhost:8503`

---

### 🔹 4. Setup API Key

Get your Gemini API key and paste it in the sidebar
or use `.env`:

```env
GOOGLE_API_KEY=your_api_key_here
```

---

## 📊 How It Works (Step-by-Step)

### 1️⃣ Document Ingestion

* Upload PDFs
* Extract text
* Split into chunks (~1000 chars)

### 2️⃣ Vectorization

* Convert text → embeddings
* Store in ChromaDB

### 3️⃣ Query Processing

* Convert user query → embedding
* Retrieve top-k relevant chunks

### 4️⃣ Answer Generation

* Inject context into prompt
* Generate grounded response
* Attach citations

---

## 📌 Example Queries

```text
"What are first-line treatments for hypertension?"

"What are contraindications of Metformin?"

"Recommended pediatric fever dosage?"
```

---

## 📂 Project Structure

```
medical-rag-system/
├── medical_rag_system.py
├── requirements.txt
├── chromadb_storage/
└── README.md
```

---

## 🔥 Key Highlights

✔ Real-world **RAG implementation**
✔ Handles **unstructured medical data**
✔ End-to-end **GenAI pipeline**
✔ Built with **production mindset**
✔ Focus on **trust, accuracy, explainability**

---

## 🛡️ Safety Disclaimer

> ⚠️ This system is for **educational & research purposes only**
> Not a substitute for professional medical advice

---

## 🔒 Privacy

* Runs locally
* Documents not stored externally
* Vector DB stored on-device
* API key not persisted

---

## 🧪 Challenges Solved

* Reducing **LLM hallucinations**
* Designing **retrieval pipelines**
* Handling **large document parsing**
* Maintaining **context relevance**

---

## 🚀 Future Roadmap

* 📄 OCR support for scanned PDFs
* 🧠 Chat memory (multi-turn conversations)
* 📊 Explainability (confidence scoring)
* 🌐 Deployment (Render / AWS)
* 🏥 Integration with medical APIs

---

## 💼 Why This Project Stands Out

This is NOT a basic ML project.

It shows you understand:

👉 **RAG architecture (hot skill 🔥)**
👉 **LLM limitations & mitigation**
👉 **Vector databases**
👉 **AI system design (not just models)**

This is exactly what companies hiring for **AI/ML roles want right now**.

---

## 🤝 Contributing

PRs welcome — let’s build safer AI systems 🚀

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
💼 Data Science | ML | GenAI Engineering

---

## ⭐ Support

If this helped you, drop a ⭐ — helps reach more devs

---

🔥 If you want next level move (seriously high ROI for you):

I can help you:

* Turn THIS into a **LinkedIn viral post (100k+ reach style)**
* Add **system design diagram (interview-ready)**
* Create **perfect explanation for HR + tech round**

Just say: **“make it interview ready”** 🚀

