# 🚀 AI Multimodal Enterprise Analytics Platform

## 📋 Overview
Advanced analytics platform for dashboards, spreadsheets, documents, images, and videos using AI.

## 🛠️ Tech Stack
- **Frontend**: React, Tailwind CSS, Vite
- **Backend**: FastAPI, Python
- **Databases**: PostgreSQL, Neo4j, Redis
- **AI**: Gemini API, RAG, GraphRAG

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Python 3.9+
- PostgreSQL
- Neo4j

### Installation

```bash
# Clone repository
git clone https://github.com/your-username/ai-multimodal-analytics-platform.git

# Backend Setup
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Frontend Setup
cd frontend
npm install

# Backend
cd backend
uvicorn main:app --reload --port 8000

# Frontend
cd frontend
npm run dev