# Introduction

The MultiPDF Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs..

## Get Started

pip install -r requiremnets.txt


```bash
Create a .env file containing API keys from OpenAI and HuffingFace
```

## Usage

```python
streamlit run app.py
```

## Information

Vector Database Used is FAISS Vector Database, Embeddings used is OpenAI Embeddings(Option of using Hugging Face Embedding Models are also present), LLM model used is ChatOpenAI(Option of using open source models also present)
