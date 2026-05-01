# OpsMind AI - Enterprise SOP RAG Agent

OpsMind AI is a premium, production-grade intelligence engine that transforms your corporate Standard Operating Procedures (SOPs) into a context-aware, verifiable knowledge base.

## 🚀 Key Features

- **High-Fidelity UI**: Cinematic landing page with slow-motion animations and glassmorphism.
- **RAG Architecture**: Powered by Gemini Pro and MongoDB Atlas Vector Search.
- **Real-time Streaming**: Instant feedback using Server-Sent Events (SSE).
- **Verifiable Citations**: Every response includes exact page numbers and snippet citations from your PDF sources.
- **Secure Ingestion**: Robust pipeline for parsing, chunking, and embedding PDFs.
- **Advanced Auth**: Enterprise-grade authentication with JWT and OTP support.

## 🛠️ Technology Stack

- **Frontend**: React, Vite, Tailwind CSS (v4), Framer Motion, Lucide React.
- **Backend**: Node.js, Express, MongoDB Atlas, Gemini AI SDK.
- **ML/AI**: Vector Embeddings (text-embedding-004), Gemini Pro LLM.

## 🚦 Getting Started

### 1. Prerequisites
- Node.js (v18+)
- MongoDB Atlas cluster with Vector Search enabled.
- Gemini API Key.

### 2. Installation
```bash
# Install dependencies for both root, client and server
npm install
npm install --prefix client
npm install --prefix server
```

### 3. Configuration
Create a `.env` file in the `server/` directory (refer to `.env.example`).

### 4. Running the App
```bash
# Run both frontend and backend concurrently
npm run dev
```

The app will be available at `http://localhost:3000`.
The backend will be running at `http://localhost:5000`.

---
*Built with ❤️ for High-Performance Enterprise Teams.*