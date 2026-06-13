🎥 YouTube Video Chatbot using LangChain

An AI-powered YouTube Chatbot that allows users to interact with any YouTube video by asking natural language questions about its content. Simply provide a YouTube Video ID, and the application extracts the transcript, creates embeddings, stores them in a vector database, and uses a Large Language Model (LLM) to answer questions based on the video's content.

🚀 Features:
Extract transcripts directly from YouTube videos
Automatic text chunking using LangChain Text Splitters
Semantic search using vector embeddings
FAISS vector database for efficient retrieval
Retrieval-Augmented Generation (RAG) architecture
Context-aware question answering
Supports multiple user queries for the same video
Easy integration with OpenAI or Google Gemini models

🛠️ Tech Stack:
Python
LangChain
YouTube Transcript API
FAISS Vector Store
Hugging Face Embeddings
Google Gemini
Jupyter Notebook

📂 Project Workflow:
User enters a YouTube Video ID.
The application fetches the video transcript.
Transcript text is cleaned and converted into chunks.
Chunks are transformed into embeddings.
Embeddings are stored in a FAISS vector database.
User asks a question about the video.
Relevant transcript chunks are retrieved using similarity search.
Retrieved context and user question are passed to the LLM.
The chatbot generates an accurate answer based on the video content.

🧠 RAG Architecture:
YouTube Video
      │
      ▼
Transcript Extraction
      │
      ▼
Text Chunking
      │
      ▼
Embeddings Generation
      │
      ▼
FAISS Vector Store
      │
      ▼
Retriever
      │
      ▼
Prompt Template
      │
      ▼
LLM (Gemini)
      │
      ▼
Generated Answer
