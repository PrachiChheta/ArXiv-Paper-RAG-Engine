# **<span style="font-size:32px">Arxiv RAG Engine</span>**

**A complete research assistant that:**

* **Runs automated data ingestion pipelines**
* **Downloads and parses 100+ academic PDFs (e.g., arXiv papers) through APIs**
* **Searches across papers with keywords and embeddings**
* **Answers questions using local or foundational LLMs (Ollama, OpenAI, etc.)**
* **Shows sources, provides feedback, and maintains privacy**

### **A complete real production‑grade system!**

This is the **Arxiv RAG Engine** — an AI system that transforms the flood of new AI research into structured, searchable knowledge.

---

# **<span style="font-size:28px">Technical Breakdown</span>**

A fully local, API‑integrated, production‑grade RAG system with:

* **Data Ingestion:** Auto-download PDFs daily from arXiv using Airflow
* **Dual Parsing:** Extract structured content via GROBID + Docling fallback
* **Metadata Storage:** Store authors, titles, abstracts, and metadata in PostgreSQL
* **Search Engine:** OpenSearch with BM25 + semantic vectors (hybrid)
* **Chunking Engine:** Semantic‑aware chunking (evaluate multiple strategies)
* **Embedding Store:** SentenceTransformers + LlamaIndex indexing
* **RAG Pipeline:** Query expansion, retrieval, and prompt templating
* **Local LLM:** Answer questions using Ollama or APIs (LLaMA3, OpenAI, etc.)
* **Observability:** Langfuse for prompt versioning, tracing, and quality monitoring
* **Evaluation:** RAGAS metrics, nDCG scoring, accuracy, and latency tracking
* **Frontend:** Query and visualization via Streamlit or Gradio
* **FastAPI Backend:** Async API server for integration and module extensions
* **Dev Best Practices:** uv, ruff, pre-commit, pydantic, pytest, logging, and more

<img width="696" height="735" alt="Research Paper Processing Flowchart - visual selection" src="https://github.com/user-attachments/assets/259d5808-3639-4d52-a197-92f0f43d0afe" />

<img width="936" height="369" alt="Retrieval Augmented Generation (RAG) Flowchart - visual selection" src="https://github.com/user-attachments/assets/c2d4f1bc-0ca7-45be-b691-476609e2f2ec" />


