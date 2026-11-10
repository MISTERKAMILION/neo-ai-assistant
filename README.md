# NEO - Personal AI Assistant & Job Hunter

NEO is a fully self-hosted, local AI assistant built on n8n, Docker, and Groq.

## Features
- **AI Job Hunter**: Scrapes jobs daily, filters them against a CV using Groq (Llama 3), and emails matches.
- **Chat Agent**: A personal assistant with Web Search (SearXNG) and Website Reader capabilities.
- **Local & Private**: Runs entirely on your own machine via Docker.

## Tech Stack
- **n8n**: Workflow automation
- **Groq**: LLM inference (Llama 3)
- **SearXNG**: Self-hosted web search
- **Docker Compose**: Infrastructure orchestration
- **Gmail API**: Notifications

## Quick Start
1. Ensure Docker and Docker Compose are installed.
2. Clone this repository.
3. Copy `.env.example` to `.env` and add your API keys.
4. Run `docker compose up -d`.
5. Open `http://localhost:5678` and import the `.json` workflow files.

## Workflows
- `job-hunter-workflow.json`: The daily AI job scraper and emailer.

