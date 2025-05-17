# -LangChain-Powered-RAG-Chatbot
AI-driven RAG chatbot using LangChain, Ollama, and FAISS with integrated  document retrieval, code execution, web search, and deployed via Gradio for interactive, context aware conversations
# LangChain RAG Chatbot with Ollama and FAISS

This project builds a Retrieval-Augmented Generation (RAG) chatbot leveraging LangChain, Ollama LLMs, and FAISS vector search.

## Features
- Scrapes official LangChain documentation for relevant content.
- Creates text chunks and embeddings with Ollama's `nomic-embed-text` model.
- Stores embeddings in FAISS for fast similarity search.
- Integrates SerpAPI for web-based knowledge retrieval.
- Supports Python code execution within the chat via Python REPL tool.
- Uses Ollama's `llama3.1:8b` LLM for conversational AI.
- Provides an interactive Gradio web UI for chat.
- Maintains conversation history with buffer memory.

## Installation

```bash
sudo apt install pciutils lshw
curl -fsSL https://ollama.com/install.sh | sh
pip install -U langchain-ollama langchain-community faiss-cpu langchain_experimental google-search-results gradio
