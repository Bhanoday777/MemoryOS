🧠 MemoryOS — Autonomous Organizational Memory Safeguard
Tagline/Intro: MemoryOS is a premium, multi-agent AI system designed to capture, validate, and secure corporate knowledge from departing employees. Instead of losing critical tribal knowledge to empty handovers, organizations can conduct dynamic AI exit interviews, audit procedures against safety policies using Enkrypt AI, and index facts in Qdrant Vector database for secure citation-backed RAG QA. Built for the Google AI Hackathon 2026.
Key Features:
💬 Dynamic Agentic Exit Interviews: A role-aware AI interviewer (Gemini 1.5) that probes the departing employee for undocumented system configurations, credentials, and setups.
🛡️ Enkrypt AI Prompt Security Gateway: An active governance firewall that intercepts PII leaks, secret credentials, and malicious injection attacks before they reach external LLMs.
⚠️ Compliance & Validation Audit Engine: A validation agent that scans knowledge for vulnerabilities (e.g. plaintext database passwords written on post-it notes) and flags security conflicts.
📄 Notion-Style SOP Generator: Automatically compiles extracted knowledge units and reference documents into highly structured markdown operating procedures and runbooks.
🔎 Qdrant Semantic RAG QA Console: A ChatGPT-style question-and-answer interface using Vertex AI embeddings and Qdrant DB, returning answers with clickable citation source badges.
✨ Sleek Glassmorphic 3D Telemetry: Dark-mode first operations console featuring interactive coordinate particle grids (DotField) and neon GL-filament animations (WebThreads).
Architecture & Tech Stack:
Frontend: Next.js 16 (React, TypeScript, TailwindCSS, Framer Motion, HTML5 Canvas)
Backend: Python 3.12 (FastAPI, Uvicorn, SQLAlchemy, LangGraph)
AI Integration: Google GenAI SDK (gemini-1.5-flash and Vertex AI text-embedding-004)
Database & Security: Qdrant Vector DB & Enkrypt AI Guardrails Gateway
Quick Start Guide:
Backend Setup: cd backend .\.venv\Scripts\activate (or source on linux) pip install -r requirements.txt GEMINI_API_KEY=your_key_here uvicorn app.main:app --reload --port 8000
Frontend Setup: cd frontend npm install npm run dev Open http://localhost:3001 in your browser.
Project Structure:
backend/app/main.py: Primary REST API endpoints.
backend/app/agents/interview_agent.py: Conducts the dynamic, stage-gated chat turns.
backend/app/prompts/interview_prompt.md: System prompt mapping known gaps and security policies.
backend/app/services/rag.py: Manages Qdrant DB vector storage, dimension adaptors, and RAG retrieval.
frontend/src/app/dashboard/page.tsx: The primary three-column operations dashboard.
frontend/src/components/DotField.tsx: Bulging particle vector space matrix background.
This is exactly what the user wants! I will output this single block in one go so they can easily copy-paste it.# 🧠 MemoryOS — Autonomous Organizational Memory Safeguard

MemoryOS is a premium, multi-agent AI system designed to capture, validate, and secure corporate knowledge from departing employees. Instead of losing critical tribal knowledge during handovers, organizations can conduct dynamic AI exit interviews, audit procedures against safety policies using Enkrypt AI, and index facts in a Qdrant Vector database for secure, citation-backed RAG QA.

Built for the Google AI Hackathon 2026.

✨ Key Features
💬 Dynamic Agentic Exit Interviews: A role-aware AI interviewer (Gemini 1.5) that probes the departing employee for undocumented system configurations, credentials, and setup procedures.
🛡️ Enkrypt AI Prompt Security Gateway: An active governance firewall that intercepts PII leaks, secret credentials, and malicious injection attacks before they reach external LLMs.
⚠️ Compliance & Validation Audit Engine: A validation agent that scans knowledge for vulnerabilities (e.g. plaintext database passwords written on post-it notes) and flags security conflicts.
📄 Notion-Style SOP Generator: Automatically compiles extracted knowledge units and reference documents into highly structured markdown operating procedures and runbooks.
🔎 Qdrant Semantic RAG QA Console: A ChatGPT-style question-and-answer interface using Vertex AI embeddings and Qdrant DB, returning answers with clickable citation source badges.
✨ Sleek Glassmorphic 3D Telemetry: A dark-mode first operations console featuring interactive coordinate particle grids (DotField) and neon GL-filament animations (WebThreads).
🛠️ Architecture & Tech Stack
Frontend: Next.js 16 (React, TypeScript, TailwindCSS, Framer Motion, HTML5 Canvas)
Backend: Python 3.12 (FastAPI, Uvicorn, SQLAlchemy, LangGraph)
AI Integration: Google GenAI SDK (gemini-1.5-flash and Vertex AI text-embedding-004)
Database & Security: Qdrant Vector DB & Enkrypt AI Guardrails Gateway
🚀 Quick Start Guide
1. Backend Setup
Navigate to the backend directory:
bash


cd backend
Activate the virtual environment:
powershell


.\.venv\Scripts\activate
Install dependencies:
bash


pip install -r requirements.txt
Configure your environment in .env:
env


GEMINI_API_KEY=your_key_here
GEMINI_MODEL=gemini-1.5-flash
Start the FastAPI server:
bash


uvicorn app.main:app --reload --port 8000
2. Frontend Setup
Navigate to the frontend directory:
bash


cd frontend
Install packages:
bash


npm install
Start the Next.js development server:
bash


npm run dev
Open http://localhost:3001 in your browser.
📂 Project Structure
backend/app/main.py
: Primary REST API endpoints.
backend/app/agents/interview_agent.py
: Conducts the dynamic, stage-gated exit interview chat turns.
backend/app/prompts/interview_prompt.md
: System prompt mapping known gaps and security policies.
backend/app/services/rag.py
: Manages Qdrant DB vector storage, dimension adaptors, and RAG retrieval.
frontend/src/app/dashboard/page.tsx
: The primary three-column operations dashboard.
frontend/src/components/DotField.tsx
: Bulging particle vector space matrix background.
