# Parent Document Retriever

This project demonstrates how to load, process, and retrieve information from PDF documents using LangChain. The script processes PDF files, splits them into chunks, embeds the text, and enables question-answering (QA) capabilities through a retrieval system.

## Features

- **PDF Document Loading**: Load and process PDF documents from a specified folder.
- **Text Splitting**: Break down large documents into smaller chunks for efficient processing.
- **Embedding**: Use HuggingFace's sentence transformer model to embed document chunks.
- **Vector Store**: Store the embedded chunks in a vector store (Chroma) for efficient retrieval.
- **Retrieval System**: Retrieve relevant information from documents using LangChain's ParentDocumentRetriever.
- **Question Answering**: Perform QA on the documents using the Ollama language model.
