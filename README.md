# Job Description Analyzer

> Paste a job posting URL — get a full technical analysis, fit score, and interview prep in seconds.

Built with **Ollama (llama3.2)** + **BeautifulSoup** + **OpenAI-compatible SDK**. Runs 100% locally — no API costs.

## What It Does

- Scrapes any job posting URL and strips navigation noise
- Analyzes required skills, nice-to-haves, and red flags against your profile
- Scores candidate fit out of 10 with honest justification
- Generates a tailored application pitch
- Produces 5 likely interview questions with answer hints

## Quick Start

Prerequisites: Python 3.10+, Ollama installed and running

```bash
ollama pull llama3.2
pip install openai requests beautifulsoup4
jupyter lab job_description_analyzer.ipynb
```

## Tech Stack

| Component | Purpose |
|-----------|---------|
| Ollama (llama3.2) | Local LLM inference — free, private |
| BeautifulSoup | HTML scraping and noise removal |
| OpenAI SDK | API client pointed at Ollama |
| Jupyter | Interactive output with markdown rendering |

---
Built by [Muazzam Hussain](https://www.linkedin.com/in/moazzam-hussain) — Agentic AI & RAG Systems Builder