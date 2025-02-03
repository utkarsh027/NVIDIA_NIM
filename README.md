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
   ```
2. **Install the required packages:
 ```bash
pip install -r requirements.txt
```
3. **Set up the .env file:
   NVIDIA_API_KEY=your_nvidia_api_key_here
   
4. **Place your PDF documents in the ./us_census directory (or any directory you specify in the code):

5. **Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
   
   
   
