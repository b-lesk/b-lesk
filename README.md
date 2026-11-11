# Benjamin Lesko

Data and AI engineer in New Orleans. I build SQL and Python pipelines, LLM workflows, and the checks that keep both honest.

- Senior Analyst, Data Engineer at Accenture, supporting Meta as a client (May 2025 to present). 
- Data Scientist at North (May 2022 to March 2025).
- B.S. Statistics, University of Michigan. M.S. Analytics at Georgia Tech, in progress.

**Portfolio:** [b-lesk.github.io](https://b-lesk.github.io/)
**LinkedIn:** [benjamin-lesko](https://www.linkedin.com/in/benjamin-lesko/)

## What I work on

- Data models and daily summary tables for reporting
- Production pipelines with monitoring, retries and row-count verification
- Data quality checks: deduplication, JSON extraction, missing and duplicate detection
- Privacy cleanup workflows with approval gates and post-run checks

## AI and LLM work

- **Backfill agent.** Built an agent workflow with chat, Claude Code skill and web entry points. It takes an approved backfill request, submits it, monitors it, retries within limits and verifies rows landed before closing.
- **Contract retrieval (RAG).** Designed an Azure, OpenAI and Cosmos DB solution over 60+ statements of work, with a semantic layer for contract value by period and deal discovery.
- **Internal AI platform.** Co-built a full-stack Next.js platform for a practitioner community of 250+: onboarding, discovery, review and an assistant.
- **Human-in-the-loop review.** Prototyped a dry-run recommendation workflow for privacy reviews where a reviewer approves every change. It was a prototype and was not deployed.
- **LLM extraction in SipTrack.** Gemini and a local open model (Qwen via Ollama) read bar websites and return schema-constrained JSON. A deterministic validator then checks each price, item and time against the source page before anything goes live.

## Projects

| Project | What it is | Links |
|---|---|---|
| **SipTrack** | Happy-hour discovery platform. SwiftUI iOS app, Next.js on Cloudflare, Supabase/Postgres, Gemini venue-data extraction, Sentry and scheduled health checks. Live. | [siptrack.app](https://siptrack.app/) and [overview](https://github.com/b-lesk/siptrack-overview) |
| **PaperTrade** | Paper-trading web app. FastAPI, SQLAlchemy and Alembic, strategies written in plain English and parsed with Claude. Source is private. | [papertrade.dev](https://papertrade.dev/) |
| Blackjack Casino Plugin | Older learning project. Python desktop app using YOLOv5 card detection. | [repo](https://github.com/b-lesk/blackjack-casino-plugin) |

## Tools

**Data:** SQL, Python, Presto, Hive, Snowflake, Airflow, Postgres, Supabase

**AI:** OpenAI, Gemini, Claude and Claude Code, RAG, vector databases, AI agents, Azure, Cosmos DB, Ollama

**Apps:** Next.js, Swift and SwiftUI, Cloudflare, GitHub Actions, Git
