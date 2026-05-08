# Multi-Agent AI Research System

Production-ready AI research system using FastAPI, LangGraph, OpenAI, Tavily, Redis, and PostgreSQL.

## Features
- Multi-agent orchestration
- Web research
- AI summarization
- Validation
- Docker deployment

## Run

```bash
docker-compose up --build
```

## API

POST /research

```json
{
  "query": "Impact of AI on semiconductor startups"
}
```
