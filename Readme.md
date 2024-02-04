# Ollama on Google colab

This repository contains starter Google Colab notebooks for working with LLMs on Ollama.
It runs with GPU installed on Google Colab (but not mandatory).

## rag_on_colab.ipynb

This notebook contains a starter for doing RAG using :
- a single file chunked in characters as corpus
- HugginfFace as embedding model
- Qdrant as vector store
- Mistral as generation LLM
- Ollama as LLM serving backend
- langchain as integration framework

The notebook natively runs on GPU on Google Colab.

## fastchat_on_colab.ipynb

This notebook contains a starter to :
- run a fastchat LLM in colab
- send query to the LLM through an API
- use the openai syntax to send queries

The notebook natively runs on GPU on Google Colab.
