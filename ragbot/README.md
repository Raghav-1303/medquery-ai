# 🩺 MedQuery AI-Chatbot UI

A modern AI-powered medical chatbot interface built with React and TypeScript, featuring Markdown support and seamless integration with a RAG-based backend.

## Overview

MedQuery AI is a simple and responsive medical chatbot interface designed to answer health-related questions. It connects to a FastAPI backend powered by OpenAI, LangChain, and Qdrant to generate context-aware responses.

## Getting Started

1. Clone the repository
```bash
git clone [Repo](https://github.com/Raghav-1303/medquery-ai)
cd medquery-ai/ragbot
```

### 2. Install Dependencies

```bash
pnpm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the `ragbot` folder.

```env
VITE_PUBLIC_API_URL=http://127.0.0.1:8000
VITE_STREAMING_SUPPORT=yes
```

### 4. Start the Development Server

```bash
pnpm run dev -- --host 127.0.0.1 --port 3000
```

Open http://127.0.0.1:3000 in your browser.

**Note:** The FastAPI backend must be running for the chatbot to generate answers.

## Features

- AI-powered medical question answering
- Modern and responsive chat interface
- Markdown support
- Streaming AI responses
- FastAPI backend integration
- Dark mode support

## Technologies Used

- React
- TypeScript
- Vite
- FastAPI
- OpenAI
- LangChain
- Qdrant

## Credits

This project was built by:
- [Raghava M](https://github.com/Raghav-1303) 



