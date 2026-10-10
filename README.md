# Multi-Agent Project

Welcome to your custom multi-agent workflow project!

This repository contains standalone agent implementations that run in LangGraph Studio.
It is completely decoupled from any template and ready for your custom logic.

## Project Structure
- **agents/**: Standalone agents for LangGraph Studio.
- **notebooks/**: Development and experimentation notebooks.
- **utils/**: Shared utilities and model configurations.

## Getting Started

1. Copy `.env.example` to `.env` and fill in your API keys (like `OPENAI_API_KEY` or others).
2. Install dependencies:
   ```bash
   pip install uv
   uv sync
   source .venv/bin/activate
   ```
3. Run the development server locally:
   ```bash
   langgraph dev
   ```
   This will start the API endpoint and LangGraph Studio UI (typically at http://localhost:2024).

Happy building!
