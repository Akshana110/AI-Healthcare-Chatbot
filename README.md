*MediBot – AI Medical Chatbot (RAG)*

MediBot is an AI-powered medical chatbot built using Retrieval Augmented Generation (RAG).
It loads medical PDFs, creates vector embeddings, stores them in FAISS, and answers user queries using Mistral LLM.

*Features*

1. PDF → Chunking → Embeddings → FAISS
2. RAG pipeline for accurate context-based answers
3. Streamlit chatbot UI
4. Modular 3-phase architecture

*Tech Stack*

1. LangChain
2. HuggingFace (Mistral)
3. FAISS
4. Streamlit
5. Python

*Project Structure*

Phase 1 – Memory Setup
• Load PDFs
• Create chunks
• Generate embeddings
• Store in FAISS

Phase 2 – LLM + Vector DB
• Mistral model (HuggingFace)
• Semantic search
• RAG chain

Phase 3 – UI
• Streamlit chatbot
• Load vector store
• Generate answers
