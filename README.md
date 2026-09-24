# 📊 AI Financial & Business Document Analyser

An AI-powered financial document analysis system that allows users
to upload annual reports and ask natural-language questions about
financial information.

## 🚀 Features

- PDF document upload
- Page-aware text extraction
- Semantic document chunking
- Sentence Transformer embeddings
- FAISS vector search
- Retrieval-Augmented Generation (RAG)
- Local FLAN-T5 model
- Financial question answering
- Source-page retrieval
- Gradio interface
- Runs in Google Colab

## 🏗️ Architecture

PDF
↓
PyMuPDF
↓
Text Chunking
↓
Sentence Transformers
↓
FAISS
↓
Semantic Retrieval
↓
FLAN-T5
↓
Financial Answer
↓
Gradio Interface

## 🛠️ Technologies

- Python
- Google Colab
- PyMuPDF
- SentenceTransformers
- FAISS
- Hugging Face Transformers
- FLAN-T5
- Gradio

## 🎯 Project Objective

The system is designed to make large financial and business
reports easier to understand by allowing users to ask
natural-language questions and retrieve relevant information
from the uploaded document.

## 🔍 Example Questions

- What was the total income?
- What was the net profit?
- What were the current liabilities?
- What was the cash position?
- What are the major financial risks?

## 📌 Project Status

Working prototype with semantic retrieval and local
language-model-based answer generation.
