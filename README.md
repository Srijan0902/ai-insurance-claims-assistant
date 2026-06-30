# AI Insurance Claims Assistant

An AI-powered assistant that helps process and analyze insurance claims, built with Spring Boot and integrated with LLM capabilities.

## 🛠️ Tech Stack
- Java
- Spring Boot
- LangChain4j
- OpenAI API
- REST APIs

## ✨ Features
- AI-powered claims analysis and assistance
- Natural language query handling for claims data
- REST API integration with LLM backend
- Context-aware responses using RAG (Retrieval-Augmented Generation)

## 📂 Project Structure

    src/main/java/com/srijan/aiclaimsassistant/
    ├── controller/    # REST endpoints
    ├── service/       # Business logic & AI integration
    ├── config/        # LangChain4j / OpenAI configuration
    ├── dto/           # Data transfer objects
    └── exception/     # Custom exceptions & handlers

## 🤖 How It Works
1. User submits a claims-related query via the API
2. The system processes the query using LangChain4j
3. OpenAI API generates a contextual, relevant response
4. Response is returned to the user via REST endpoint

## 🚀 Getting Started
*Setup instructions coming soon as development progresses.*

## 📋 Status
🚧 In active development
