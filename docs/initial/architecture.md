architecture# Architecture

## System Architecture
- Frontend: Next.js
- Backend: Python (FastAPI)
- Database: Supabase (PostgreSQL)
- Authentication: Supabase Auth

## Components
1. Web Application (Next.js)
2. API Server (FastAPI)
3. Database (Supabase)
4. Automation Engine (n8n).md


## Architecture Overview

The system follows a modular, scalable architecture with clear separation of concerns.

## Components

- Frontend (Next.js)
- Backend API (Python / FastAPI)
- Database (Supabase / PostgreSQL)
- AI Services (NLP, Recommendation Models)
- Automation Engine (n8n)
- CI/CD Pipeline (GitHub Actions)
- Deployment (Vercel)

## Data Flow

1. User interacts with frontend
2. Requests sent to backend API
3. Backend processes logic and AI inference
4. Data stored/retrieved from database
5. Response sent back to frontend

## Security Architecture

- OAuth-based authentication
- Role-based access control
- Secure API communication
