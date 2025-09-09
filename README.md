# Context-Aware Chatbot Using RAG

## Project Description
A conversational AI system that uses Retrieval-Augmented Generation (RAG) architecture to provide context-aware responses. The chatbot maintains conversation memory and retrieves relevant information from a knowledge base using semantic search.

---

## Key Features
- Retrieval-Augmented Generation implementation  
- Conversation context memory  
- Semantic search with FAISS  
- Multi-source knowledge integration  
- Web interface deployment  
- Real-time response generation  

---

## Technologies Used
- Python  
- Sentence Transformers  
- FAISS  
- Requests  
- BeautifulSoup  
- HTTP server  

---

## Dataset
Custom knowledge base including:
- AI and machine learning concepts  
- Wikipedia integration capability  
- Web content retrieval  
- Custom text documents  

---

## Installation
```bash
pip install sentence-transformers faiss-cpu requests beautifulsoup4 numpy
Usage
bash
Copy code
python chatbot.py
Web interface available at:

arduino
Copy code
http://localhost:8000
Results
Real-time context-aware responses

Semantic similarity search

Multi-turn conversation support

Web deployment capability

Files
chatbot.py - Main chatbot implementation

knowledge_base/ - Directory for knowledge documents

requirements.txt - Project dependencies

Methodology
Knowledge base creation and embedding

FAISS vector store setup

Semantic search implementation

Response generation with context

Web interface deploymen
