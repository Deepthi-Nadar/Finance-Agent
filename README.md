# Finance-Agent

A simple finance assistance agent built with **google-adk**.

## Local run

1) Install dependencies

```bash
pip install -r requirements.txt
```

2) Set your Gemini/GCP API key (env var name depends on google-adk / google-generativeai)

```bash
set GOOGLE_API_KEY=YOUR_KEY
```

3) Run

```bash
python main.py
```

## Deployment

Push to GitHub and deploy using your preferred platform (Render/Fly/VPS/etc.) with the same environment variables.

## Project structure

- `main.py` - entry point
- `finance_assistance_agent/agent.py` - main assistant agent
- `investment_plan_agent/agent.py` - assistant with Google search tool

