# Personal PDF Q&A with Google Gemini
This repository contains a Streamlit-based web application that lets users upload PDF files, ask questions about their content, and receive AI-generated answers. By combining Google Gemini's generative AI capabilities with ChromaDB's powerful vector search, this app makes document exploration easy and intuitive.

## Features
PDF Upload: Upload multiple PDF files for processing.

Text Chunking: Automatically splits large documents into smaller chunks for efficient querying.

ChromaDB Integration: Stores and retrieves document embeddings for accurate context retrieval.

Google Gemini AI: Generates intelligent and context-aware answers to user queries.

Live Web App: Deployed using Streamlit and accessible via localtunnel.

## Usage
### 1.Upload PDF Files
Drag and drop your PDF files into the app.

### 2.Process Documents
The app will split the content into chunks and store embeddings in ChromaDB.

### 3.Ask Questions
Enter a question in the text box. The app retrieves the most relevant chunks and uses Google Gemini to generate an answer.

### 4.View Answers
The AI-generated answer will be displayed below the input field.
