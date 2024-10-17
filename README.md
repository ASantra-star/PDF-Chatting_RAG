# Multiple PDF Chatbot using Retrieval-Augmented Generation (RAG)

This project implements a chatbot capable of interacting with users and answering questions based on multiple PDF documents. It leverages Retrieval-Augmented Generation (RAG) to enhance the response quality by retrieving relevant information from the provided documents.

## Features
- **Multi-PDF Support**: Engage with a chatbot that can reference multiple PDF documents for accurate information.
- **Dynamic Query Processing**: Utilizes advanced techniques for parsing and understanding user queries.
- **Real-time Responses**: Provides quick and relevant answers by retrieving and generating responses on-the-fly.

---

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.x
- Required libraries (install via pip):
  ```bash
  pip install langchain faiss-cpu transformers

## Implementation Steps

### Step 1: Load Multiple PDFs
Extract text from multiple PDF files to build a knowledge base.

### Step 2: Split the Extracted Data into Text Chunks
Process the extracted text into manageable chunks for better retrieval.

### Step 3: Download and Create Embeddings
Utilize pre-trained models to convert text chunks into embeddings.

### Step 4: Create a Vector Store
Store the embeddings in a vector database for efficient retrieval during conversations.

### Step 5: Initialize the Language Model
Load the appropriate language model for generating responses based on user queries.

### Step 6: Implement the Chatbot Loop
Set up an interactive loop to handle user input and generate responses.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to the developers of LangChain for providing the foundational tools for building this chatbot.  
Special thanks to Hugging Face for their powerful models.

