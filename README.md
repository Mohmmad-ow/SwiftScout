# AI Recruitment System (Microservices Architecture)

A distributed system that processes resumes, analyzes candidates using AI, and ranks them based on job fit.

## Architecture

<img width="690" height="697" alt="Architecture Image" src="https://github.com/user-attachments/assets/b38f0d52-c065-4606-ad9e-4715fdc5eb2e" />

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

https://github.com/user-attachments/assets/20750c9a-ca41-4a21-8f1b-396a02b7cde8

## Key Features
- Microservices-based architecture
- Asynchronous job processing
- Redis-based rate limiting
- AI-powered candidate ranking
- Audits for both AI servies to keep track of User actions kept in the Database
- Theme/Language Switching in the Frontend
