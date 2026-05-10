# ARYMA • RAG Agent (GenAI) | **https://aryma.art/**
ARYMA is an **Art + AI platform** that combines visual art discovery with a **RAG Agent for GENAI**.
The project includes artist-facing gallery experiences and an AI assistant that answers artwork and policy questions in natural language.

## Core Platform Focus
- **ARYMA info**: Art + AI experience for semantic artwork discovery and recommendations.
- **Artist**: Gallery and artist pages integrated into the web app.
- **RAG Agent for GENAI**: Conversational assistant powered by retrieval + LLM reasoning.
- **Django app**: Full backend and web UI implemented with Django 5.

## AI / ML Stack
- **Text Embedding Model**: `all-MiniLM-L6-v2` (384 dimensions)
- **Image Embedding Model**: `clip-ViT-B-32` (512 dimensions)
- **LLM Model**: Perplexity **Sonar** via LangChain `ChatPerplexity`
- **Retrieval**: PostgreSQL + pgvector semantic search

## Runtime & Deployment
- **Framework**: Django 5
- **Orchestration**: LangChain + LangGraph
- **Database**: PostgreSQL (pgvector-ready), SQLite fallback for local development
- **Containerization**: Single custom Docker image for Django app
- **Production target (current phase)**: Docker-based deployment with managed services (Postgres/Redis/Storage)

## This is a FullStack AI system, fully automated with:
- **IDE:** VS Code
- **Remotes:** Github & Gitlab (Private Repositories)
- **CI/CD:** Gitlab
- **Server:** Digital Ocean
- **Domain:** Spaceship



## Author
**Juan David Arroyave Ramirez**  
AI Specialist  
Email: `juan.arroyaver@outlook.com`  
Website: https://davidarroyave.github.io
