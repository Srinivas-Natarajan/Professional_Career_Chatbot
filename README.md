# Personalized Chatbot about Professional Experience - Srinivas Natarajan

## Overview

Content Engine is a Retrieval Augmented Generation (RAG) system designed to process multiple PDF documents, enabling analysis, comparison, and differentiation. It utilizes advanced techniques to retrieve relevant information, evaluate content, and generate meaningful insights. This project integrates various machine learning models and libraries to facilitate efficient document embedding and querying.

## Features

    - Analyzes the personal documents supplied and answers questions about my professional experience

    - Utilize Retrieval Augmented Generation (RAG) for effective information retrieval and generation.

    - Maintain chat history for contextual conversation.

    - Streamlit interface for an interactive user experience.

## Technologies Used

- **PyPDFLoader** is responsible for loading and extracting text from PDF files, ensuring structured data processing.
- **RecursiveCharacterTextSplitter** splits long text into manageable chunks, optimizing retrieval and embedding performance.
- **Hugging Face Embeddings** generate high-quality document embeddings, transforming textual data into vector representations for efficient retrieval.
- **FAISS (Facebook AI Similarity Search)** acts as the vector database, efficiently storing and retrieving relevant document embeddings.
- **LlamaCpp** serves as the core language model, handling natural language processing and response generation.
- **LangChain** facilitates the conversational retrieval chain, enabling dynamic interactions and intelligent query processing.
- **ConversationBufferMemory** maintains chat history, allowing seamless contextual understanding across multiple interactions.
- **Streamlit** powers the interactive web interface, providing a user-friendly platform for document uploads, analysis, and conversational interactions

## Prerequisites

- Python 3.10 or higher

- Streamlit

- LangChain

- HuggingFace Transformers

- FAISS

- LlamaCpp

- PyPDFLoader
