# ApplyAssist AI: The Universal Application Copilot

ApplyAssist AI is a comprehensive, multi-agent SaaS platform designed to help users successfully navigate complex, document-heavy processes including scholarships, university admissions, job applications, and government schemes. 

Built with Next.js, FastAPI, and PostgreSQL, the system utilizes advanced OCR and Retrieval-Augmented Generation (RAG) to extract requirements, determine eligibility, validate user uploads, and dynamically generate actionable steps to ensure application success.

## Core Features
- **Form Intelligence Engine**: Generates plain-English explanations, eligibility summaries, and deadline information from complex application forms.
- **Missing Document Detection**: Automatically compares required documents against user uploads to identify missing, expired, or invalid files.
- **Application Readiness Score**: Calculates a score based on document completeness, deadlines, and upload compliance.
- **Opportunity Discovery**: Recommends scholarships, benefits, and grants based on user profile and uploaded documents.
- **Context-Aware Chatbot**: Provides real-time assistance grounded in retrieved document context (no hallucinated answers).

## Tech Stack
- **Frontend**: Next.js 15, TypeScript, TailwindCSS, ShadCN UI, React Query, Zustand
- **Backend**: FastAPI, Python, PostgreSQL (pgvector), AWS S3
- **AI Layer**: PaddleOCR, LangChain/LlamaIndex, specialized ReAct Agents
- **Infrastructure**: Docker, Redis, Celery
