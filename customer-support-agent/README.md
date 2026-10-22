
# 🤖 Customer Support AI Agent

An AI-powered customer support automation workflow built with **n8n**. The workflow processes incoming customer emails, classifies them, retrieves relevant information from a knowledge base using **RAG**, and generates an automated response using an AI agent.

## 🚀 Workflow

```text
Google Drive
     ↓
Document Processing
     ↓
Pinecone Vector Store
     ↓
Gmail Trigger
     ↓
Text Classification
     ↓
AI Agent
     ↓
Gmail Response