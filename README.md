# RAG From Scratch  

This repository demonstrates how to implement a Retrieval-Augmented Generation (RAG) pipeline from scratch using LangChain, HuggingFace, and Groq APIs. The pipeline integrates document retrieval with language model capabilities to answer questions based on relevant retrieved documents.  

## Features  
- **Web Content Loading**: Retrieves and processes content from a specified URL using `WebBaseLoader`.  
- **Text Splitting**: Splits large documents into smaller chunks for embedding and retrieval using `RecursiveCharacterTextSplitter`.  
- **Vector Storage**: Utilizes Chroma for efficient vector storage and retrieval.  
- **Question Answering**: Implements an end-to-end RAG pipeline to answer questions based on retrieved documents.  

  
