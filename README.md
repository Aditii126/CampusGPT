# CampusGPT
CampusGPT is a multilingual AI-powered RAG chatbot that helps students access college and university information through natural-language queries. It uses semantic search, vector embeddings, ChromaDB, and Google Gemini to provide document-grounded answers in multiple languages.

# CampusGPT – Multilingual RAG Chatbot

CampusGPT is an AI-powered multilingual chatbot designed to simplify access to college and university information. Built using Retrieval-Augmented Generation (RAG), it retrieves relevant information from institutional documents, such as admission rule books, eligibility guidelines, and fee structures, and generates context-aware responses to students' queries.

The system uses **Sentence Transformers** for multilingual text embeddings, **ChromaDB** for vector storage and semantic search, **Google Gemini 3.5 Flash-Lite** for natural-language response generation, and **Streamlit** for the interactive user interface.

CampusGPT allows students to ask questions in supported languages, including English, Hindi, Marathi, Bengali, and Tamil, and receive answers based on the available institutional documents, along with source references where available.

### Key Features
- Multilingual question answering.
- Retrieval-Augmented Generation (RAG) architecture.
- Semantic search using vector embeddings.
- Document-based information retrieval.
- Context-aware AI response generation.
- Source document and page references where available.
- Interactive Streamlit chatbot interface.

### Technology Stack
- Python
- Streamlit
- PyMuPDF
- Sentence Transformers
- ChromaDB
- Google Gemini API
- python-dotenv

**Goal:** To make institutional information more accessible, searchable, and understandable through a multilingual AI-powered chatbot.
