
# AutoNoteRAG

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge\&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Framework-orange?style=for-the-badge\&logo=chainlink)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-green?style=for-the-badge\&logo=meta)
![OpenRouter](https://img.shields.io/badge/OpenRouter-LLM%20API-lightgrey?style=for-the-badge\&logo=openai)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

---

## Application Preview

<img alt="AutoNoteRAG - AI-powered meeting summarizer demo" src="assets/demo_meeting_summary.png"></img>

---

## Project Insight

**AutoNoteRAG** is an intelligent meeting summarization system powered by **Retrieval-Augmented Generation (RAG)** and modern **LLMs**.
It automatically extracts, retrieves, and summarizes meeting transcripts to produce concise summaries highlighting key decisions and action items.
This project addresses the challenge of information overload in team discussions and applies retrieval-based reasoning for accurate contextual synthesis.

---

## Why This Project Exists

The project was inspired by the growing need for **automated note-taking** in hybrid workplaces where long meeting transcripts are difficult to process manually.
Conventional summarizers often lose decision-critical context; AutoNoteRAG solves this by grounding the generation process in semantically relevant transcript chunks.
It bridges the gap between **retrieval precision** and **language generation fluency**, providing structured insights from unstructured dialogue data.

---

## Architecture & Technologies

| Component             | Technology                  | Purpose                                   |
| --------------------- | --------------------------- | ----------------------------------------- |
| Transcript Processing | Python (Regex, NLTK)        | Cleans and segments meeting text          |
| Embedding & Indexing  | FAISS, SentenceTransformers | Creates semantic vector representations   |
| Retrieval Pipeline    | RAG Framework               | Finds the most relevant transcript chunks |
| Summarization Engine  | OpenRouter API (LLM)        | Generates structured summaries            |
| Interface             | Google Colab / CLI          | Runs summarization and displays outputs   |

**Runtime Requirements:** Python 3.10+, `faiss-cpu`, `langchain`, `sentence-transformers`, `requests`, `openai`

---

## Run It Locally

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/AutoNoteRAG.git
   ```
2. Navigate into the folder

   ```bash
   cd AutoNoteRAG
   ```
4. Add your OpenRouter API key in `.env`

   ```bash
   export OPENROUTER_API_KEY=your_api_key_here or add in colab
   ```
---

## Key Takeaways

* Implements an end-to-end **Retrieval-Augmented Generation** pipeline for meeting summarization.
* Demonstrates **context-aware LLM prompting** with grounding in retrieved evidence.
* Provides modular, extendable code for integrating custom embeddings or LLM endpoints.
* Offers practical insight into combining **vector search** and **language generation**.

---

## Roadmap

* Add speaker diarization and emotion-aware summarization.
* Integrate real-time transcription from meeting APIs (e.g., Zoom, Google Meet).
* Extend support for multilingual meeting summaries.

---

**Keywords:** RAG, Meeting Summarization, LLMs, FAISS, LangChain, Python, Information Retrieval, AI Note-Taking

؟
