

---

### 4. `rag-chatbot/README.md`

```markdown
# 📚 RAG Chatbot

A document-based question-answering workflow built with **n8n** using **Retrieval-Augmented Generation (RAG)**. The workflow processes documents, generates embeddings, stores them in a vector database, and retrieves relevant information when answering user questions.

## 🚀 Workflow

```text
Google Drive
     ↓
Document Processing
     ↓
Embeddings
     ↓
Pinecone Vector Store
     ↓
Chat Message
     ↓
AI Agent
     ↓
Retrieved Knowledge
     ↓
Response