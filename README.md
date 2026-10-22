# AI Automation Workflows

A collection of end-to-end AI automation workflows built with **n8n**, **LLMs**, **RAG**, APIs, and productivity tools.

These projects focus on using AI to automate real-world tasks such as customer support, document processing, knowledge retrieval, and social media content generation.

---

## 🚀 Projects

### 1. 🤖 Customer Support AI Agent

An AI-powered customer support workflow that combines email processing, document-based knowledge retrieval, and an AI agent to generate responses.

**Workflow:**

Google Drive → Document Processing → Pinecone Vector Store  
↓  
Gmail Trigger → Text Classification → AI Agent → Gmail Response

**Technologies**
- n8n
- AI Agents
- Ollama
- Pinecone
- RAG
- Google Drive
- Gmail

🎥 **[Watch Demo](https://drive.google.com/file/d/17w1Y1TqYpGZySi3oMGRBrwlhWXiWk9BO/view?usp=sharing)**  
📂 **[View Workflow](./customer-support-agent/)**

---

### 2. 📱 Social Media Post Agent

An AI workflow that generates social media content and image prompts from user-provided input.

The workflow uses AI agents for content generation and image prompting, along with web search and image generation.

**Workflow:**

Form Submission  
↓  
Social Media Post Agent  
↓  
Image Prompt Agent  
↓  
Image Generation + Social Media Post

**Technologies**
- n8n
- Google Gemini
- AI Agents
- Prompt Engineering
- Web Search
- Image Generation
- X / Twitter

🎥 **[Watch Demo](https://drive.google.com/file/d/1LTZYECP0a50FTqWinNRktWzHUWMc8u9M/view?usp=sharing)**  
📂 **[View Workflow](./social-media-agent/)**

---

### 3. 🧾 Invoice Parser & Email Automation

An automated document-processing workflow that extracts information from invoices and stores the extracted data in Google Sheets.

**Workflow:**

Google Drive Trigger  
↓  
Download File  
↓  
Extract Data from PDF  
↓  
AI Information Extraction  
↓  
Google Sheets  
↓  
Email Notification

**Technologies**
- n8n
- Google Gemini
- AI Information Extraction
- PDF Processing
- Google Drive
- Google Sheets
- Gmail

🎥 **[Watch Demo](https://drive.google.com/file/d/1jMIakcSJ6bRunjV8x6K6Jp3CqJVm2UQW/view?usp=sharing)**  
📂 **[View Workflow](./invoice-parser/)**

---

### 4. 📚 RAG Chatbot

A document-based question-answering workflow using Retrieval-Augmented Generation (RAG).

Documents are processed and stored as embeddings in a vector database, allowing the AI agent to retrieve relevant information when answering questions.

**Workflow:**

Google Drive  
↓  
Document Processing  
↓  
Embeddings → Pinecone Vector Store  
↓  
Chat Message  
↓  
AI Agent → Retrieved Knowledge → Response

**Technologies**
- n8n
- RAG
- Ollama
- Pinecone
- Hugging Face Embeddings
- Google Drive
- AI Agents

🎥 **[Watch Demo](https://drive.google.com/file/d/1Krq9UfmPiabNSK4Mp4qw9buk-r2CtBrB/view?usp=sharing)**  
📂 **[View Workflow](./rag-chatbot/)**

---

## 🛠️ Tech Stack

### AI & GenAI
- LLMs
- AI Agents
- Prompt Engineering
- RAG
- Embeddings
- Image Generation

### Automation
- n8n
- Workflow Automation
- API Integrations
- Event-driven Workflows

### AI Models & Tools
- Google Gemini
- Ollama
- Hugging Face
- Pinecone

### Integrations
- Google Drive
- Google Sheets
- Gmail
- X / Twitter

---

## 📂 Repository Structure

```text
AI-Automation-Workflows/
│
├── README.md
│
├── customer-support-agent/
│   ├── README.md
│   ├── workflow.json
│   └── workflow.png
│
├── social-media-agent/
│   ├── README.md
│   ├── workflow.json
│   └── workflow.png
│
├── invoice-parser/
│   ├── README.md
│   ├── workflow.json
│   └── workflow.png
│
└── rag-chatbot/
    ├── README.md
    ├── workflow.json
    └── workflow.png