# 🚀 Gemini-Powered RAG Assistant

A robust **Retrieval-Augmented Generation (RAG)** pipeline leveraging Google's **Gemini 2.0 Flash** for intelligent synthesis and **ChromaDB** for high-performance vector storage.



---

## ✨ Features

* **LLM Integration**: Powered by the latest `google-genai` SDK and Gemini 2.0 models.
* **Vector Search**: Local vector embeddings using `sentence_transformers` and `ChromaDB`.
* **Modern Tooling**: Managed entirely with **uv** for blazing-fast dependency resolution.
* **Environment Safety**: Secure API key management via `.env` integration.

---

## 🛠 Prerequisites

Before starting, ensure you have the following installed:

* **uv**: The extremely fast Python package manager. ([Installation Guide](https://docs.astral.sh/uv/getting-started/installation/))
* **Jupyter Lab**: For interactive development. ([Installation Guide](https://jupyter.org/install))
* **Google Gemini API Key**: Obtain yours for free at [Google AI Studio](https://aistudio.google.com/apikey).

---

## 🚀 Getting Started

### 1. Clone & Setup
```bash
# Create project directory
mkdir my-rag-project && cd my-rag-project

# Initialize uv environment
uv init