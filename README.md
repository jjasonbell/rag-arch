# rag-arch

RAG Architecture Pipeline Tester and Code Generator

rag-arch is an updated version of https://github.com/AI-ANK/RAGArch

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Set up API keys:
   - Copy `.env.example` to `.env`
   - Add your API keys for the LLMs you want to use (OpenAI, Google, Cohere)
   - Add your vector store API key if using Pinecone

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Features

- Configure and test RAG pipelines with custom parameters
- Choose from multiple LLMs (GPT-3.5, GPT-4, Gemini, Cohere)
- Select from various embedding models
- Configure node parsers with custom parameters
- Choose vector stores (Simple, Pinecone, Qdrant)
- Generate plug-and-play implementation code based on your configuration
