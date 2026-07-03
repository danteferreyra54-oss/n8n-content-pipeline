# n8n Content Pipeline — Medio Independiente

Automated content pipeline built with n8n for a sports media outlet.

## What it does

1. Fetches content inputs from Notion
2. Sends them to GPT-4o-mini for processing (summarizing, formatting, adapting tone)
3. Routes the output via Gmail with a human-in-the-loop approval step before publishing

## Stack

- n8n (workflow automation)
- GPT-4o-mini (AI processing)
- Notion (content database)
- Gmail (approval + delivery)

## File

`Pipeline de contenido - Independiente.json` — import this directly into n8n to run the workflow.
