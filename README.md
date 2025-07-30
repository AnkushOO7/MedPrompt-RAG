# MedPrompt-RAG
**MedIntel-RAG** is an AI-powered Retrieval-Augmented Generation (RAG) system built to assist healthcare professionals in accessing reliable, up-to-date medical knowledge from *The Merck Manuals*. It helps streamline clinical decision-making, reduce information overload, and improve patient care outcomes.

---

## 🚀 Features

- **Diagnostic Assistance**: Get key symptoms, signs, and treatments for various conditions.
- **Drug Information**: Look up trade names, usage, and dosages for medications.
- **Treatment Plans**: Retrieve evidence-based first-line and alternative treatment options.
- **Specialty Knowledge**: Access structured diagnostic steps for specialty areas like endocrinology.
- **Critical Care Protocols**: Quickly access emergency care protocols like those for sepsis.

---

## 🏗️ Architecture

- **Retrieval-Augmented Generation (RAG)**
- **Vector Store (e.g., FAISS) for semantic search**
- **Large Language Model (e.g., GPT-4 or similar)**
- **PDF Parsing & Chunking (Merck Manual)**
- **Frontend UI (Streamlit or FastAPI)**

---

## 📚 Data Source

- **The Merck Manuals** (PDF, over 4,000 pages, 23 sections)
  - Used as the trusted, centralized medical knowledge base.
  - Chunked and indexed for semantic retrieval.

> *Note: Ensure usage complies with copyright and licensing terms.*

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/MedIntel-RAG.git
cd MedIntel-RAG
pip install -r requirements.txt
