# NVIDIA NIM Demo with Streamlit

This repository contains a Streamlit application that demonstrates the use of NVIDIA's NIM (NVIDIA Inference Microservices) to create a document-based question-answering system. The application uses LangChain for document processing, NVIDIA Embeddings for vector embeddings, and FAISS for vector storage and retrieval.

## Features

- **Document Ingestion**: Loads PDF documents from a specified directory.
- **Text Splitting**: Splits documents into smaller chunks for processing.
- **Vector Embeddings**: Uses NVIDIA Embeddings to convert text chunks into vectors.
- **Vector Storage**: Stores vectors using FAISS for efficient similarity search.
- **Question Answering**: Allows users to ask questions based on the ingested documents and retrieves the most relevant answers.

## Prerequisites

Before running the application, ensure you have the following:

- Python 3.8 or higher
- Streamlit
- NVIDIA API key (stored in `.env` file)
- Required Python packages (listed in `requirements.txt`)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/nvidia-nim-demo.git
   cd nvidia-nim-demo
