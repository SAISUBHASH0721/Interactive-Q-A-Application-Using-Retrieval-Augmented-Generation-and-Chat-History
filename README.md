Conversational RAG System with PDF Uploads
An AI-driven web application built using Streamlit that allows users to interact with content from uploaded PDF documents via a Q&A chatbot. 
The system leverages Retrieval-Augmented Generation (RAG) to provide accurate, context-aware responses by combining information retrieval and natural language generation.

Key Features
PDF Document Uploads: Easily upload multiple PDF documents for information extraction.
Conversational Q&A Interface: An intuitive chat interface to ask questions about the uploaded documents.
Context-Aware Responses: Maintains session-based chat history to provide relevant and coherent answers.
Advanced RAG Architecture: Combines a retrieval system (Chroma) with natural language generation (OpenAI) for precise answers.
Seamless Integration: Built with Streamlit for a smooth and interactive user experience.
Technology Stack
Python
Streamlit
LangChain
OpenAI API
Chroma
PyPDFLoader
Getting Started
Clone the Repository: Download the project to your local machine.
Install Dependencies: Use a package manager like pip to install all required dependencies.
Environment Setup: Configure your environment with necessary API keys, including OpenAI and Groq API keys.
Run the Application: Launch the Streamlit app and start interacting with your documents.
How It Works
Enter API Key: Input your Groq API key to initialize the language model.
Upload PDFs: Use the upload functionality to add PDFs containing the information you want to query.
Ask Questions: Enter questions in the chat interface. The system retrieves relevant content from the PDFs and generates concise answers.
View Chat History: The interface supports session-based history management to ensure context-aware responses.
