# AI Recruitment System (Microservices Architecture)

A distributed system that processes resumes, analyzes candidates using AI, and ranks them based on job fit.

## Architecture
[Diagram Image]

## Services
- Backend API (Go): handles orchestration and routing
- AI Service (Python): processes resumes and scoring
- Frontend (React): user interface
- Redis: caching and rate limiting
- Webhooks: for communication between the AI services and the Backend

## Repositories
- Backend: [link](https://github.com/Mohmmad-ow/smart-hiring-go)
- Frontend: [link](https://github.com/Mohmmad-ow/Smart-Hiring-UI)
- AI Service: [link](https://github.com/Mohmmad-ow/interview-analysis-service) _switch brances for Document/Interview Processing_

## Demo
[Video Link]

## Key Features
- Microservices-based architecture
- Asynchronous job processing
- Redis-based rate limiting
- AI-powered candidate ranking
- Audits for both AI servies to keep track of User actions kept in the Database
- Theme/Language Switching in the Frontend
