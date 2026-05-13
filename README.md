# StudyMind – Multi-Agent RAG Based AI Academic Assistant

StudyMind is a Multi-Agent AI Academic Assistant designed to provide intelligent and context-aware academic support using Retrieval-Augmented Generation (RAG). The system processes uploaded PDFs, notes, and syllabus documents to help students with doubt clarification, study planning, and personalized academic assistance.

## Features

* Multi-Agent AI Workflow
* Retrieval-Augmented Generation (RAG)
* PDF & Document-based Question Answering
* Context-Aware Responses
* Semantic Search using Vector Databases
* Study Plan Generation
* Intelligent Query Routing
* Personalized Learning Assistance

## Tech Stack

* Python
* LangChain / LangGraph
* FAISS / ChromaDB
* Large Language Models (LLMs)
* Streamlit
* Pandas & NumPy

## System Architecture

The system uses multiple AI agents working together:

* **Retriever Agent** – Retrieves relevant content from uploaded documents
* **Planner Agent** – Generates structured study plans
* **Orchestrator Agent** – Routes user queries to suitable workflows
* **Support/Motivation Agent** – Provides adaptive learning assistance

## How It Works

1. User uploads syllabus PDFs or study materials
2. Documents are processed and converted into vector embeddings
3. Relevant information is retrieved using semantic similarity search
4. AI agents coordinate to generate context-aware responses
5. The system provides answers, summaries, and study guidance

## Applications

* Academic Assistance
* Personalized Learning
* Study Planning
* Educational AI Systems
* Intelligent Knowledge Retrieval

## Future Improvements

* Voice-based interaction
* Adaptive learning analytics
* Student progress tracking
* AI-generated learning content
* Multi-modal support

## Installation

```bash
git clone <your-repository-link>
cd studymind
pip install -r requirements.txt
streamlit run app.py
```

## Author

Shreya Egurla
