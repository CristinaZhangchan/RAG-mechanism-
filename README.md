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

## ⚙️ Environment Configuration

1.  **Create an Environment File**: In the project root directory, create a file named `.env`.
2.  **Add your API Key**: Insert the following content into the `.env` file:
    ```text
    GEMINI_API_KEY=xxx
    ```
    *Replace `xxx` with your actual Google Gemini API key. You can apply for a key at [Google AI Studio](https://aistudio.google.com/apikey).*

---

## 📦 Installation

Use `uv` to install the necessary Python dependencies. This stack is optimized for vector search and generative AI:

```bash
uv add sentence_transformers chromadb google-genai python-dotenv
