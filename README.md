# Document QA System - Technical Assessment

## Overview

This technical assessment evaluates your expertise in Python development with a focus on AI integration, specifically working with LLMs, vector databases, and autonomous agents.

You'll be building a document question-answering system with the following high-level capabilities:
1. Document upload and processing
2. Vector similarity search
3. Question answering using LLMs
4. AI agent-based complex query handling

## Core Requirements

### 1. Document Processing
- Accept document uploads (PDF, TXT files)
- Extract and process text from documents
- Split documents into appropriate chunks
- Create and maintain relevant metadata

### 2. Vector Database
- Create document embeddings using an embedding model
- Store embeddings in a vector database (FAISS)
- Implement efficient similarity search
- Track and manage document-chunk relationships

### 3. AI Integration
- Integrate with OpenAI or equivalent LLM
- Implement a RAG (Retrieval-Augmented Generation) pattern
- Create a context-aware conversation system
- Format prompts to maximize answer quality

### 4. Agent System
- Create at least two specialized AI agents
- Implement agent communication/orchestration
- Create a workflow for complex queries
- Handle agent failures gracefully

### 5. FastAPI Application
- Create RESTful API endpoints
- Implement proper error handling
- Include performance optimization (caching) (optional)

## Technical Specifications

- Python 3.11.11
- Implement a FastAPI application
- Use LangChain for LLM integration
- Use FAISS for vector database
- Use CrewAI or AutoGen for agent implementation (optional)
- Include proper error handling and logging
- Provide comprehensive API documentation

## API Endpoints

Your API should include at least these endpoints:

- `POST /documents/upload`: Upload and process documents
- `GET /documents`: List available documents
- `POST /questions/ask`: Ask a question about documents
- `POST /agents/complex-query`: Process a complex query using agents

## Assessment Criteria

Your submission will be evaluated on:

1. **Functionality** - Does the system work as specified?
2. **Code Quality** - Is the code well-structured, documented, and maintainable?
3. **Architecture** - Are components properly separated with clean interfaces?
4. **Performance** - Is the system reasonably efficient and responsive?
5. **Innovation** - Any clever solutions or improvements to the specified requirements?

## Getting Started

This repository provides a basic structure to get you started. You can modify it as needed.

1. Clone this repository
2. Create a virtual environment and install dependencies
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your OpenAI API key
4. Implement the required functionality
5. Test your implementation

## Submission

Please provide:

1. Your complete source code in a GitHub repository
2. A README with:
   - Setup instructions
   - API documentation 
   - Brief explanation of your architecture
   - Design decisions and trade-offs
   - Ideas for future improvements

Good luck!