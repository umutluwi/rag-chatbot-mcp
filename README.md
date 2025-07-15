# RAG Chatbot with MCP Integration

A sophisticated RAG (Retrieval-Augmented Generation) chatbot system built with Model Context Protocol (MCP), n8n workflow automation, PostgreSQL vector store, and modern web technologies.

## 🏗️ Architecture Overview

- **PostgreSQL + pgvector**: Vector store for document embeddings and chat history
- **n8n**: Workflow orchestration and webhook handling
- **Claude MCP**: Programmatic system management and integration
- **GitHub**: Version control and CI/CD
- **Docker**: Container orchestration

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/umutluwi/rag-chatbot-mcp.git

# Start services
docker-compose up -d

# Initialize database
psql -U postgres -d rag_chatbot < init.sql
```

## 📡 Integration Points

- **Webhook**: `http://n8n.luwi.dev:5678/webhook/rag-chatbot`
- **PostgreSQL**: `localhost:5432/rag_chatbot`
- **n8n Workflow ID**: `2NhTSbSyaBRaSPqG`

## 🤝 Claude + ChatGPT Collaboration

This project leverages both Claude's MCP capabilities and ChatGPT's strategic planning for optimal development workflow.

See [MCP_INTEGRATION_GUIDE.md](./MCP_INTEGRATION_GUIDE.md) for detailed MCP usage.

## 📊 Project Status

| Component | Status | Progress |
|-----------|--------|----------|
| Backend Setup | ✅ | 100% |
| n8n Workflow | ✅ | 100% |
| Frontend | 🔄 | 20% |
| Deployment | ⏳ | 0% |

## 🔧 Technologies

- PostgreSQL 15.13 + pgvector
- n8n workflow automation
- OpenAI embeddings (text-embedding-ada-002)
- GPT-4 Turbo
- React/Next.js (planned)
- Docker & Kubernetes

## 📝 License

MIT